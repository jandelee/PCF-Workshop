## PCF-Workshop

For a simple demonstration to deploy this app to Cloud Foundry:

1. Download this project to your local workstation. Be sure to keep in its own folder in your file system.

   Navigate to the [OpenLayers Vector Tile project](https://github.com/lnguyen2341/OL_Vector_Tile) in git  
   Click the green **Clone or Download** button, and then click the **Download Zip** icon  
   Extract the download into an appropriate directory in your filesystem.

2. Use the PCF Apps Manager: Log into the desired Cloud Foundry endpoint;

   If using a .io PCF account, navigate to [https://login.system.dev.east.paas.geointservices.io](https://login.system.dev.east.paas.geointservices.io)   
   If using a PWS PCF account, navigate to [https://console.run.pivotal.io](https://console.run.pivotal.io)

3. Use the PCF Command Line Interface (CLI) from your shell tool: Log into the desired Cloud Foundry endpoint;

   If using an .io PCF account:  
   > cf login -a https://api.system.dev.east.paas.geointservices.io

   If using a PWS PCF account:  
   > cf login -a https://api.run.pivotal.io

   for Email>, enter your PCF username  
   for Password>, enter your PCF password  

4. Select an Org (if needed) and a Space;
5. From your project's directory:  
   > cf push
6. Retrieve your app's URI from AppsManager, et voila!
