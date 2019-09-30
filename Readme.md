<!-- default file list -->
*Files to look at*:
* [Form1.cs](./CS/ViewerForm1.cs) (VB: [Form1.vb](./VB/ViewerForm1.vb))
<!-- default file list end -->

# How to Create a Slide Show with Asynchronous Maximize and Restore Methods

This example demonstrates how to call the asynchronous maximize and restore methods to create a slide show with the dashboard items.

![screenshot](/images/screenshot.png)



API in this example:

* [DashboardViewer.AsyncMode](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardViewer.AsyncMode). Switches to the asynchronous mode. The property is set in the **InitializeComponent** method.
* [DashboardViewer.MaximizeDashboardItemAsync](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardViewer.MaximizeDashboardItemAsync(System.String)) method. Maximizes the specified dashboard item asynchronously.
* [DashboardViewer.RestoreDashboardItemAsync](https:/docs.devexpress.devx/Dashboard/DevExpress.DashboardWin.DashboardViewer.RestoreDashboardItemAsync(System.String)) method. Restores the item size if an item is expanded to the entire dashboard size (maximized), asynchronously.


See also:

* [Asynchronous Mode](https://docs.devexpress.com/Dashboard/401305)