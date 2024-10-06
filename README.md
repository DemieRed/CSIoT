# CSIoT
AllERT: Flood disaster management system using IoT for prompt response and recovery efforts

This repository contains the Node-RED JSON flows used for the AllERT Flood Management System, as described in the dissertation "AllERT: Flood disaster management system using IoT for prompt response and recovery efforts". The flows are part of the Decision Support System (DSS), built to optimize resource allocation and improve response time during flood emergencies through real-time data integration. 
Important notice: it is dependent on additional components and cannot stand alone.

IoT sensors, UAV data and GIS-based route planning, using Random Forest machine learning model for decision-making are its main components. The Node-RED flows are used to process incoming data, run the machine learning models and visualize the results through the dashboard.

Repository Contents:
AllERT_flows.json: It contains all the flows of the instance. Processes real-time data from IoT sensors.
README.md: This file, providing instructions for using the repository.

Installation and Setup Prerequisites: 
Node-RED: Ensure that you have Node-RED installed on your machine.
Node-RED Libraries: @flowfuse/node-red-dashboard ~1.16.0, node-red-contrib-influxdb ~0.7.0, @flowfuse/node-red-dashboard-2-ui-iframe ~1.1.0, @colinl/node-red-dashboard-2-ui-gauge-classic ~1.3.1, node-red-pushsafer ~1.0.4, @flowfuse/nr-project-nodes ~0.7.3, node-red-contrib-ui-media ~1.2.0, node-red-dashboard ~3.6.5, node-red-contrib-web-worldmap ~4.9.0 (install via the Node-RED palette manager).
You can download the repository as a ZIP file and extract it.

Import the Node-RED Flows:
Open your local Node-RED editor.
Go to the Menu (top-right corner) > Import > Clipboard
Copy the JSON and paste it into the import dialog.
Click Import to add the flow to your workspace.

Configure the Environment:
Depending on your setup, you may need to modify some environment variables or connection strings.
For example, you can adjust the MQTT broker settings, REST API URLs, or data processing intervals in the Node-RED editor.

Run the Flows:
After configuring, deploy the flows by clicking the "Deploy" button in the Node-RED editor.

Contact
For any questions or issues, please contact the project author:

Dimitra Kokkinou
Email: demiered@gmail.com

Academic Reference
If you use these flows in your research or project, please cite the following thesis:

Dimitra Kokkinou, "AllERT: Flood disaster management system using IoT for prompt response and recovery efforts", University of Thessaly, MSc CSIoT 2024.
