# HackBout-2020

# TEAM: RuntimeTerrorOnIoT
# Team Number : 38


# Website_RuntimeTerror README
# Documentation of runtimeTerrorOnIoT Web App

This is a web app to monitor various key factors in a plantation such as Temperature (of the atmosphere), Humidity (of the atmosphere), Light intensity, Soil Moisture levels, Gas levels (presence of harmful gases such as Methane, etc.

Click here to get redirected to the implementation website. There, you can view the live feed of the data being sent from the Arduino Nano IoT device and it's visualisation in graphs. There is a control button to turn the water pump ON and OFF should the user wish to do so.

Since the implementation of the same was locally hosted, it is not possibe to visualise the same through the above implementation link.

# Planned additions:
Addition of an automation system to automatically trigger the motor pump on detection of soil moisture falling below a threshold level.
Addition of sensors to sense the gases present in atmosphere, in turn advising changes in fertilizations behaviours to control air pollution, thus preventing Global Warming, for a better Climatic condition.





# MICROCONTROLLER_CODE README
The above two folders consist the necessary codes for runninf the IoT project.

In order to make out project more efficient, reliable and consumer friendly, we have taken the approach of a Master_Slave system, wherein the Micro Controllers bearing the sensors, which are present at a Particular Node/ Area in the fiels can communicate with the main master through Serial Communication.

The initial concept was to use LORA and incorporate a wireless system, but, given the time constraints, we were unable to demonstrate the same. The same will be taken and worked on in the future. More updates shall be posted here soon with regard to the same.

Using the Master-Slave Approach, we can minimalize the number of devices that need to be connected to the internet, increasing the overall efficiency in places where the internet connectivity isn't that great.

The custom built website was tailored specifically for the same, thus maximising the performance and user friendliness.

Multiple tasks can be done directly from the website without having to interact with the device, thus making ti a fully Smart Farming. Intuitive Graphs, Manual Override Controls, Weather Forecast and Future Weather prediction are a few things necessary to be implemented in this project.

The custom built website was tailored specifically for the same, thus maximising the performance and user friendliness. More can be understood by visiting the website: https://smartfarmingoniot.github.io/runtimeTerrorOnIoT/index.html

