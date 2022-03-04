# Python-Data-Analytics

Project: Data Analytics project using Python and open-source hardware: Raspberry Pi.
COMPONENTS REQUIRED
1.	Raspberry Pi
2.	Power Cable
3.	WiFi or Internet
Workflow
A. Dataset: Use remote Raspberry Pi to collect data for temperature and humidity sensor.    Measurement and collect multiple datasets.
B. Create channels on Thing Speak for real time data uploading from Raspberry Pi. Download all this Channel's feeds in the CSV format.

C. Data Visualization: Plot data with Python/Pandas.

D. Data Analysis: Perform linear regression for data analysis and check model.

Brief explanation of each step in the workflow:
A. Dataset: Use remote Raspberry Pi to collect data for temperature and humidity sensor. Instructor will provide remote access of Raspberry Pi interfaced with few IoT (internet of things) sensors such as Temperature, Humidity, Air quality and light sensors. Monitor and analyze real time data from remote IoT connected devices
Useful Links:
VNC remote logging:  https://www.realvnc.com/en/connect/download/viewer/ (Links to an external site.)

 ThingSpeak:https://iotdesignpro.com/projects/how-to-send-data-to-thingspeak-cloud-using-raspberry-pi (Links to an external site.)   https://thingspeak.com/

B. HOW TO SEND DATA TO THINGSPEAK CLOUD USING RASPBERRY PI

First step in building any IoT project using Raspberry Pi, that is to upload the data to any cloud server using Raspberry Pi. In this simplest Raspberry Pi IOT project, we will use Thinkspeak as cloud server to store the data. Here Raspberry Pi will read its CPU temperature and send it to ThingSpeak, and it can be monitored from anywhere in the world using internet. This will be useful if you are running the Pi for long time for some application at some remote place and need monitor its CPU temperature.

ThingSpeak is an open IoT platform for monitoring your data online. In ThingSpeak channel you can set the data as private or public according to your choice. ThingSpeak takes minimum of 15 seconds to update your readings. It’s a great and very easy to use platform for building IOT projects.
STEPS FOR BUILDING RASPBERRY PI DATA LOGGER ON CLOUD
Step 1: Signup for ThingSpeak

Step 2: Create a Channel for Your Data
Step 3: Getting API Key in ThingSpeak
Step 4:  Python Code for Raspberry Pi
Step 5: Check ThingSpeak site for Data Logging
Step 6: Download all this Channel's feeds in the CSV format.

C. Data Visualization: When we present data graphically, we can see the patterns and insights we're looking for.  We can use data visualizations to make an argument, or to support a hypothesis, or to explore our world in different ways. Python allows us to create visualizations easily and quickly using Matplotlib and Seaborn.
The approach of the program:
1.	Import required libraries, matplotlib library for visualizing, and CSV library for reading CSV data.
2.	Open the file using open() function with 'r' mode (read-only) from CSV library and read the file using csv. 
3.	Read each line in the file using for loop.
4.	Append required columns into a list.
5.	After reading the whole CSV file, plot the required data as X and Y axis.

D. Data Analysis: Perform linear regression for data analysis and check model.

Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting.


