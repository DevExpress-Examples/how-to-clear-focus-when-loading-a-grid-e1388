<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/Window1.xaml) (VB: [Window1.xaml](./VB/Window1.xaml))
* [Window1.xaml.cs](./CS/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/Window1.xaml.vb))
<!-- default file list end -->
# How to clear focus when loading a grid


<p>The following example demonstrates how to clear a focused cell or row when loading the grid. For this, it is necessary to handle the grid's <strong>Loaded</strong> event and for the <strong>TableView</strong> set the <strong>FocusedRowHandle</strong> property to the  <strong>GridControl.InvalidRowHandle</strong> constant.</p>

<br/>


