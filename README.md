# Cortex Event Driven Automation (EDA) SNMP Device Management flows

This project contains a couple of Service Requests to allow the management of SNMP devices and configuration directly from LivePortal. 
There are some subtasks part of this project that are purely in use by the main Service Requests.
The Service Requests part of this project are:

### 1. ADD-NEW-SERVER-DEVICE-GROUP
This Service Request allows you to create new Server Device Groups. These Device Groups are use for a high load and availability environments. 

### 2. ADD-NEW-SNMP-DEVICE-TYPE
This Service Request allows you to create new SNMP Device Types.
Device Types are a grouping mechanism for multiple (SNMP) devices.

### 3. ADD-NEW-SNMP-DEVICE
This Service Request allows you to create new SNMP Devices. It uses a wizard approach to add the device details.

Besides that this Service Request allows new devices to be uploaded by means of a CSV file. The format of the CVS file is available in the Service Request.

# Installation Instructions
Download the Studio Package file and Import it into your Cortex Environment.
Don't forget to apply rights using the Studio Authorization module.
That package uses subtasks that are supplied with the Cortex Material Design Subtasks Github project [https://github.com/IntelligentAutomationCommunity/CortexMaterialDesignSubtasks](https://github.com/IntelligentAutomationCommunity/CortexMaterialDesignSubtasks)
You require the **material-dashboard-cortex.css** file part of this project to be copied to the Cortex application server.
The last part of this video demonstrates how to do that: [https://vimeo.com/458599158/67a838ef39](https://vimeo.com/458599158/67a838ef39)

:thumbsup: Success! :wink:
