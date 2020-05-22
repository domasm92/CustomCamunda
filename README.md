Custom Camunda Modeler

Camunda Modeler with small changes to allow the use of the SitScope Modeling Plugin.

You require npm for this tool.

To install the whole SitScope environment perform the following steps:

- Create a new folder at a location of your choice
- Clone this repository and the repositories of SitScopePlugin (https://github.com/domasm92/SitScopePlugin) and ChorMe (https://github.com/domasm92/ChorMe) into that folder
- Open a terminal and change the directory into the newly cloned "SitScopePlugin"-folder
- Execute "npm install"
- Execute "npm run build"
- Change the directory to the newly cloned "CustomCamunda"-folder
- Execute "npm install"
- Execute "npm run build"
- If windows/linux:
  - Copy the "SitScopePlugin" folder into "CustomCamunda/dist/{the version you want to use}/resources/plugins
 If Mac:
  - Copy the "SitScopePlugin" folder into /Users/{USER_NAME}/Library/Application Support/camunda-modeler/plugins
- Run Camunda Modeler.exe (Windows), Camunda Modeler.app (Mac) or camunda-modeler (Linux) in the "CustomCamunda/dist/{the version you want to use}/ 

More infos on plugins for Camunda can be found here: https://github.com/camunda/camunda-modeler/blob/master/docs/plugins/README.md
Issues may arise due to os-specific commands

This project is build on the Camunda Modeler (https://github.com/camunda/camunda-modeler) which is licensed under the MIT Licence
