<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
* [XtraReport1.cs](./CS/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/XtraReport1.vb))
<!-- default file list end -->
# How to change the visibility of commands in the End-User Designer


<p>The following example demonstrates how to change the visibility of the menu and smart tag items in the End-User Designer. To do this, the XRDesignPanel.SetCommandVisibility method should be used.</p><p>The code below hides the New with Wizard... menu item and the Design in Report Wizard... item in a report's smart tag. Note that a list of all the commands is represented by the ReportCommand enumeration.</p>

<br/>


