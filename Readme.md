<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/GetThePageNumber/Form1.cs) (VB: [Form1.vb](./VB/GetThePageNumber/Form1.vb))
* [XtraReport1.cs](./CS/GetThePageNumber/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/GetThePageNumber/XtraReport1.vb))
<!-- default file list end -->
# How to obtain the current page number when printing a control


<p>This example demonstrates how to get the current page number when printing a control, by handling the <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRControl_PrintOnPagetopic">PrintOnPage</a> event, which is triggered for every control just before it's printed on a page.</p><p>Note that the XRControl.PrintOnPage event is raised after both the <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRControl_BeforePrinttopic">XRControl.BeforePrint</a> and <a href="http://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXRControl_AfterPrinttopic">XRControl.AfterPrint</a> events.</p>

<br/>


