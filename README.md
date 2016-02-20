# Using Watson Visual Recognition with Node-RED to recognize the content of the image - Step-by-Step Guide

In this lab we will build a travel advisor application that recognizes the content of the image which can be used to provide more information about the destination. 


Overview :
<img src="images/Overview.png" height="270" width ="1000" align="center">

<b>Step 1 : Sign up / Login to Bluemix - https://console.ng.bluemix.net/</b>

<b>Step 2 : Go to Catalog tab and search for Node-RED</b>

<img src="images/node-red-catalog.png" height="270" width ="500" align="center">

<b>Step 3 : Click on Node-Red and give a unique name for the application</b>

<img src="images/create-app.png" height="270" width ="500" align="center">

Staging will take few minutes 

<img src="images/app-staging.png" height="270" width ="500" align="center">

Yayyyy its running now!!

<img src="images/app-running.png" height="270" width ="500" align="center">

You can verify now that a Node-RED application is created with a Cloudant database

<img src="images/nodered-appstatus.png" height="500" width ="200" align="center">

<b>Step 4 : Switch to Catalog tab and search for 'Visual Recognition' service</b>

<img src="images/nodered-appstatus.png" height="270" width ="500" align="center">

<b>Step 5 : Create a Visual Recognition service and bind it with Node-RED application created in the above step.</b>

Select the Node-RED application from the dropdown -
<img src="images/create-visualrecognition-service.png" height="270" width ="500" align="center">
	
To bind the Visual Recognition service to the Node-RED application, click 'Restage' to restart the node-red application.
<img src="images/restage-request.png" height="270" width ="500" align="center">

Your Visual recognition service is now bound to the Node-RED application
<img src="images/app-overview.png" height="270" width ="500" align="center">

Click on Application url and Navigate to node red flow editor 
<img src="images/node-red-editor.png" height="270" width ="500" align="center">	


<b>Step 6 : 
	
	
	
	
