In this demo, the [customShapeTemplate](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/#customShapeTemplate) property defines a common shape template and adds the **Edit** and **Delete** links to a shape. These links allow users to modify and remove employee data from the data source. The **Diagram** UI component reloads modified diagram data whenever the data source changes.

The [onRequestLayoutUpdate](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/#onRequestLayoutUpdate) function specifies whether the UI component must reapply its auto layout once the diagram is reloaded.

The [customDataExpr](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/nodes/#customDataExpr) property links custom employee information from the data source to diagram nodes. Changes made to data are reflected in the diagram’s history. Undo and redo actions (available within the control’s UI) allow users to rollback/reapply changes.

The [CustomShapeToolboxTemplate](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/#customShapeToolboxTemplate) property specifies the template used for a shape within the toolbox.