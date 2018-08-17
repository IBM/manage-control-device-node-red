# Node-RED Starter

### Open IBM Cloud Service Catalog:

> [Click to create the Node-RED boilerplate starter](https://console.bluemix.net/catalog/starters/node-red-starter).

<hr>

![](../images/node-red-catalog.png)

<hr>

* Increase the `GB MEMORY PER INSTANCE` to 1 to avoid deploy failures

![](../images/node-red-running-instance.png)

<hr>

* Click on the `Visit App URL`
* Open the Node-RED editor and setup your own `username` and `password`
* On the top right side of the editor, click on: `Burger Menu` -> `Import` -> `Clipboard`
* Copy the code from the [flow/flow.json](flow/flow.json) in this Github repository
* Paste the code in the `Clipboard` in the Node-RED editor

![](../images/simulate-iot-flow.PNG)

<hr>

### Important Notes that are needed for the service nodes in Node-RED editor:

* Copy and paste into one place all usernames, passwords and hosts of all services for easy access when needed
* `These credentials will be used in the Node-RED editor for each service node, without them your app will not behave as intended in this turorial`
* Each service will automatically create its credentials: `Username` and `Password`
* If you don't see the service credentials, you can create a new one: `Create Credentials`
* Internet of Things Platform will require to create an `api key` and `api token`. [How to generate API key and token in IBM Watson IoT Platform](https://developer.ibm.com/code/howtos/iot-generate-apikey-apitoken).
