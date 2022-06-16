# KasanaShare_App
## ***KasanaShare is a real-time peer to peer energy monitoring, sharing and exchange platform.***

## The Issue
### *KasanaShare is an IBM IoT enabled peer to peer green power sharing and exchange platform to power up households, small and medium enterprises with Smart solar PV system grids for adaptability to clean energy and climate change mitigation especially in decentralized, rural and hard to reach areas. Now is the time that KasanaShare taps into energy poverty especially in resource constrained areas.*

## Solution Architecture
### *KasanaShare is an IBM IoT enabled peer to peer energy sharing and exchange framework to accelerate access to clean energy, reduce GHG & CO2 emissions, eliminate noise and air pollution through use of smart PV Systems. KasanaShare features provision of the necessary technological expertise through integration of IoT technology with both software and hardware for Smart PV Systems using Node-RED MQTT*

![Slide4](https://user-images.githubusercontent.com/107638658/174145569-a0d3f0c1-e6a6-4c0f-8a74-456cfe81a5c5.JPG)
![Slide5](https://user-images.githubusercontent.com/107638658/174145608-7c98f154-83cc-4828-9a85-dfac3158b399.JPG)

https://youtu.be/9IuCdyn7ANc

## The Impact
### *The KasanaShare enhance and expands access to clean energy, custs down green house gas and CO2 emissions,and improoves the quality of adaptation in societities through clean energy sources. It reduces the use of idnividualized access mechanisms building communities resilient as partner for sustainability.*

![Slide6](https://user-images.githubusercontent.com/107638658/174145707-d95cacc6-1cd1-421c-b4c8-f137d4e0b5b0.JPG)

## The USP
![Slide7](https://user-images.githubusercontent.com/107638658/174145751-338a5f49-3346-4c0d-ba31-e99a64da4387.JPG)

## The Current Miletones
**United Nations** Climate Change (2022) "**KasanaShare from Uganda** wants to leverage green affordable shareable energy technologies to build livelihoods and enhance communities. Having established Uganda’s first green renewable energy sharing and exchange platform, the KasanaShare team is powering households and small and medium sized companies through Photovoltaic technology and harnessing the **Internet of Things (IoT)** to bring about the transition to clean energy sources." https://newsroom.unfccc.int/blog/5-green-tech-projects-we-love

Climate Smart Cities Finalists https://challenges.org/blog/climate-smart-cities-challenge-finalists/ https://climatesmart.citieschallenge.org/finalists/ https://climatesmart.citieschallenge.org/2022/01/20/finalists-climate-smart-cities-challenge-2/ https://www.bristolhousingfestival.org.uk/news/cscc-finalists-announced

![Slide8](https://user-images.githubusercontent.com/107638658/174145877-75b4a1ad-c40f-4816-8434-b888bbe16efe.JPG)
![Slide9](https://user-images.githubusercontent.com/107638658/174145915-7394fbde-a8a2-4e19-9caf-17c906dffb61.JPG)

![Slide10](https://user-images.githubusercontent.com/107638658/174145929-e3c337c8-0112-4713-a293-e98a410176dd.JPG)

# **(c) Nabuduwa Sheila





<p align="center">
    <a href="https://cloud.ibm.com">
        <img src="https://cloud.ibm.com/media/docs/developer-appservice/resources/ibm-cloud.svg" height="100" alt="IBM Cloud">
    </a>
</p>
<p align="center">
    <a href="https://cloud.ibm.com">
    <img src="https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg" alt="IBM Cloud">
    </a>
    <img src="https://img.shields.io/badge/platform-node-lightgrey.svg?style=flat" alt="platform">
    <img src="https://img.shields.io/badge/license-Apache2-blue.svg?style=flat" alt="Apache 2">
</p>


Node-RED IBM Cloud Starter Application
====================================


### Node-RED on IBM Cloud

This repository is an example Node-RED application that can be deployed into
IBM Cloud with only a couple clicks. Try it out for yourself right now by clicking:

<p align="center">
    <a href="https://cloud.ibm.com/developer/appservice/starter-kits/nodered">
    <img src="https://cloud.ibm.com/devops/setup/deploy/button_x2.png" alt="Deploy to IBM Cloud">
    </a>
</p>

### How does this work?

When you click the button, you are taken to IBM Cloud where you get a pick a name
for your application at which point the platform takes over, grabs the code from
this repository and gets it deployed.

It will automatically create an instance of the Cloudant service and bind it to
your app. This is where your Node-RED instance will store its data.

When you first access the application, you'll be asked to set some security options
to ensure your flow editor remains secure from unauthorised access.

It includes a set of default flows that are automatically deployed the first time
Node-RED runs.

### Customising Node-RED

This repository is here to be cloned, modified and re-used to allow anyone create
their own Node-RED based application that can be quickly deployed to IBM Cloud.

The default flows are stored in the `defaults` directory in the file called `flow.json`.
When the application is first started, this flow is copied to the attached Cloudant
instance. When a change is deployed from the editor, the version in cloudant will
be updated - not this file.

The web content you get when you go to the application's URL is stored under the
`public` directory.

Additional nodes can be added to the `package.json` file and all other Node-RED
configuration settings can be set in `bluemix-settings.js`.

If you do clone this repository, make sure you update this `README.md` file to point
the `Deploy to IBM Cloud` button at your repository.

If you want to change the name of the Cloudant instance that gets created, the memory
allocated to the application or other deploy-time options, have a look in `manifest.yml`.

### Environment Variables

The following environment variables can be used to configure the application:

 - `NODE_RED_STORAGE_NAME` - the Cloudant service name as exposed in `VCAP_SERVICES`
 - `NODE_RED_STORAGE_DB_NAME` - the name of the database to use on Cloudant
 - `NODE_RED_STORAGE_APP_NAME` - the prefix used in document names, allowing multiple instances
    to share the same database.
 - `NODE_RED_USERNAME`, `NODE_RED_PASSWORD` - if set, used to secure the editor
 - `NODE_RED_GUEST_ACCESS` - if the editor is secured, this will allow anonymous,
    read-only access
 - `NODE_RED_USE_APPMETRICS` - enables the appmetrics dashboard
