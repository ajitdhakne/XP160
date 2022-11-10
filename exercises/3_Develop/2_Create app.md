
**Create an SAP Fiori Application with "Start from template"**


1. Click on Start from template in the Welcome tab to create the project.
Alternative: Open the menu in the top left corner and go to View > Command Palette ... and search for ">new project". Select the command SAP Business Application Studio: New Project from Template

<img src="/exercises/images/BAS_start.png" width="750">

2. In the New Project Wizard select SAP Fiori Application.

Click **Start**.

<img src="/exercises/images/Template_Fiori_app.png" width="750">


3. In the **Floorplan Selection**, choose the following:

For the field **Application Type** choose **SAPUI5 freestyle** from the drop-down.
Select **SAPUI5 Application** as floorplan.

Choose **Next**.

<img src="/exercises/images/Template_UI5.png" width="750">


4. In the **Data Source and Service Selection** choose **None** for Data source, because we just create a "Hello World" without data binding.

5. Choose **Next**.

<img src="/exercises/images/Data_Source.png" width="750">


6. Under **Entity Selection** name your SAPUI5 view. This name will appear in the launchpad service for the app. We keep "View1" for now

Choose **Next**.

<img src="/exercises/images/View1.png" width="750">

7. In the next step, **Project Attributes** choose names and a description for your "Hello World" app (examples see figure):

**Module name**: helloworldui5
**Application title**: Hello World App Title
**Application namespace**: sap.btp
**Description**: A Fiori Hello World application 

**Project folder path** and **Minimum SAPUI5 version** should not be changed

**Add deployment configuration to MTA project**: Yes 
**Add FLP configuration**: Yes
**Configure advanced options**: No

Choose **Next**.

<img src="/exercises/images/Template_Project_Attributes.png" width="750">


8. In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target.

Choose **None** for Destination name.

Choose **Add application to managed application router**?: Yes.
This is the standard html5 repository from launchpad service and eases deployment.

Choose **Next**.

<img src="/exercises/images/Deployment_Config.png" width="750">

9. The launchpad service needs some Fiori Launchpad Configuration data about the app. Choose names for the entries Semantic Object, Action, and Title (examples see figure)
(Optional: For more information about these data and features, see Intent-Based Navigation in a Nutshell).

**Semantic Object**: helloworld
**Action**: show
**Title**: showhelloworld

<img src="/exercises/images/Fiori_Launchpad_config.png" width="750">

10. Choose **Finish**.

*Note*, that it may take some time until all dependencies are installed.

11. Click on **Add Project to Workspace**

<img src="/exercises/images/Workspace.png" width="750">

12. After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5" under HOME.

<img src="/exercises/images/BAS_Project_App_Info.png" width="750">

13. Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects".

<img src="/exercises/images/Open_Projects_folder.png" width="750">
 
14. Click **OK**.

 