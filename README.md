**Start Node-RED**
Node-RED can be started from a terminal by running this command from within the directory of the cloned repository:

$ npm start
Alternatively, if you have Node-RED installed globally with dependencies installed under ~./node-red, you can start Node-RED from any directory:

$ node-red
Stop Node-RED
You can stop Node-RED by closing the terminal window or using Ctrl-C in the terminal.

**Node-RED editor**
The Node-RED editor can be accessed from http://localhost:1880.

However, if Node-RED is on the Raspberry Pi, you can connect to it via http://<Raspberry Pi IP>:1880.
 
**Import the Node-RED flow**
Once installed the node can be added and used in the flow of your Node-RED application. To import the flows available in this repo:

**Make sure Node-RED is running**
Open a browser and go to your Node-RED Editor
Click on the Node-RED Menu
Click on Import
Select the Clipboard tab
Click on select a file to import
Browse to and select one of the flow files in the cloned repo
If trying things out locally on your browser, then use the browser-flow.json.
If using a Raspberry Pi with peripherals, then use the raspberrypi-flows.json.
Select Import to new flow
Click Import
 
**After Import ** 
 Change MQTT broker to LocalHost 
