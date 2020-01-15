Custom Camunda Modeler

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
- Copy the "SitScopePlugin" folder into "CustomCamunda/dist/(the version you want to use)/resources/plugins
- Run Camunda Modeler.exe (Windows), Camunda Modeler.app (Mac) or camunda-modeler (Linux) in the "CustomCamunda/dist/(the version you want to use)/ 


