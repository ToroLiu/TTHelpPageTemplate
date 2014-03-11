### Register the help page area 

In "global.asax.cs", you'll need to add: 

    AreaRegistration.RegisterAllAreas(); 


### Reference the 'Site.css'

In "Areas/HelpPage/Views/Share/_Layout.cshtml", add:

    <link href="~/Content/Site.css" rel="stylesheet" />