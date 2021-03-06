MAppsDefaultApp
===============

The MApps Default App is a BIRT project that is used as a starting guide for building BIRT applications. It contains the following:
- An .rpttemplate file that can be used for all new report designs and is set up for auto-layout, landscape, no masterpage footer and scripts to automatically resize the first chart in the design. It also references the project's ThemesReportItems3.rptlibrary.
- An index.html and associated demo.js file for opening this project as an application on the iHub and displaying a dashboard

To use this repository from github, clone it into your BIRT workspace. 
- Copy the project folder and change the new project app name.
- Use the MApps Default Template.rpttemplate when creating new report designs by right-clicking on it and selecting "Register Template with New Report Wizard". Choose it in the New Report dialog box when creating a new report design.
- Set the project app name in index.html's dashboardName variable and in the <title> tag.
- Create a new dashboard file and set the dashboard name in the dashboardName variable in index.html. 

To learn how to use GitHub in Eclipse with this repository, check out the following link:
http://saleswiki.actuate.com/MApps%20Demo%20Deployment.ashx

To see more BIRT examples and get support from the BIRT community, go to:
http://developer.actuate.com
