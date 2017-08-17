## PCF-Workshop

For a simple demonstration to deploy this app to Cloud Foundry:

1. Download this project to your local workstation. Be sure to keep in its own folder in your file system.

   Navigate to the [OpenLayers Vector Tile project](https://github.com/lnguyen2341/OL_Vector_Tile) in git  
   Click the green **Clone or Download** button, and then click the **Copy to clipboard** icon  
   In PowerShell, type in "git clone " and then paste in the contents of the clipboard and press <Enter>  
   Type in "cd OL_Vector_Tile"  
   Type in "dir" to see the files that were downloaded from git

2. Use the PCF Apps Manager: Log into the desired Cloud Foundry endpoint;

   If using a .io PCF account:  
   Navigate to [https://login.system.dev.east.paas.geointservices.io](https://login.system.dev.east.paas.geointservices.io)

3. Use the PCF Command Line Interface (CLI) from your shell tool: Log into the desired Cloud Foundry endpoint;

   If using an .io PCF account:
   > cf api https://api.system.dev.east.paas.geointservices.io  
   If using a PWS PCF account:  
   > cf api https://api.run.pivotal.io
   
   > cf login  
   for Email>, enter your .io PCF username  
   for Password>, enter your .io PCF password  
   If prompted for an org, select an appropriate org  
   If prompted for a space, enter an appropriate space  

4. Select an Org (if needed) and a Space;
5. From your project's directory, type: cf push
6. Retrieve your app's URI from AppsManager, et voila!
