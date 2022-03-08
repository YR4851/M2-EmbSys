# 1. ABOUT THE PROJECT

   ## Description:
   
   Automated plant watering system is programmed using Arduino IDE software. Arduino microcontroller checks soil moisture level, if low, triggering a water pump on until sensor reaches threshold. After this, the system will re-check the soil moisture between periodic intervals to see if you need more water.

   ## Features:
   
   * LCD Display shall be provided to know the temperature value.
   * soil Temperature shall be displayed on LCD.
   * soil humidity shall be displayed on LCD.
   * pump on or off status shall be displayed on LCD.
   * LED's shall be provided for the funtioning display of embedded system.
   
   ## Working state of art:
   
   The main focus of this project is to control the tempereature and humidity of a perticular soil in which it is being implimented with the help of sensors and the microcontroller. Here an LCD display is being used to display some information for user interfacing purpose. As if we see the growth of the technology around us, these types of technologies are the becoming the future of these industries.
   
   ## SWOT:
   
   ![SWOT analysis](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/1_Requirements/Screenshot%20(107).png)
   
   ## 5W & 1H
   
   ![5W & 1H](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/1_Requirements/Screenshot%20(108).png)
   
# 2. REQUIREMENTS

  ## High level requirements:

  | ID | Description | 
  | ----- | ----- | 
  | HR01 | It shall have a Microcontroller. |
  | HR02 | It shall have Sensors. |
  | HR03 | It shall have Switch. |
  | HR04 | It shall have a Display. |

  ## Low level requirements:


  |LLR_ID|Low Level Requirements|
  ---|---|
 |HLR01_LLR01|It shall have a Microcontroller(ATmega32) to recieve/transmit the data|
 |HLR02_LLR02|It shall have a Soil Moisture Sensor to detect the moisture in the soil|
 |HLR02_LLR03|It shall have a Temperature and Humidity Sensor to detect the humidity in the air|
 |HLR03_LLR04|It shall have a Relay Module which is used as an automatic switch|
 |HLR03_LLR05|It shall have a LED which is uesd to blink when the switch ON|
 |HLR04_LLR06|It shall have a 16x2 LCD which is used to display the moisture of the soil, humidity in  the air|
