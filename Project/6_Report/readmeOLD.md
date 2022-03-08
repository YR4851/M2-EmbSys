# FAN SPEED CONTROL BY SENSING ROOM TEMPERATURE

  - by YASH RASTOGI

# TABLE OF CONTENT

1. About the project
   * Description
   * features
   * Working state of art
   * S.W.O.T and 5W & 1H analysis
2. Requirements
   * High level requirements
   * Low level requirements
3. Block Diagram 
   * Block diagram
   * Sensors
   * Actuators
   * Micro controller and memory
   * Flow chart
4. Architecture
   * Structural Diagram
   * Behavioural Diagram
     * Flowchart.
     * UML diagram.
5. Application and Advantages

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

# 3. BLOCK DIAGRAM

  ## Block diagram:
  
  ![Block diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/7_ImagesAndVideos/BLOCK_DIAGRAM.png)
  
  ## Sensor: 
  
   ### Temperature Sensor (Thermistor):
   
   * This Thermistor is a resistor whose resistance is dependent on temperature here this change in resistence produces change in voltage, this voltage is taken as input to micro controller.
   
   ### Soil moisture sensor:
   
   * Soil moisture sensors measure the volumetric water content in soil. Since the direct gravimetric measurement of free soil moisture requires removing, drying, and weighing of a sample, soil moisture sensors measure the volumetric water content indirectly by using some other property of the soil, such as electrical resistance, dielectric constant, or interaction with neutrons, as a proxy for the moisture content.
   
  ## Actuators:
  
   ### Relay:
   
   * A relay is an electrically operated switch. It consists of a set of input terminals for a single or multiple control signals, and a set of operating contact terminals. 
  
   ### LCD Display:
   
   * Displays each and every value we enter in our keypad along with Temperature.
   
   ### LED's:
   
   * LED displays the on and off status of the device.
   
  ## MICRO CONTROLLER AND MEMORY
  
   ### EEPROM
   
   * Here this is actually inside the microcontroller
   
   ### Clock
   
   * Here we are using internal clock of our micro controller.
   
   ### MicroController:
   
   * This is the main component which controls all the above mentioned part or thins of our embedded system.This interfaces keypad and LCD and controlls the fan,light and doors depending on the value we pressed on keypad.
   
  ## SUBSYSTEM & OTHERS
  
   ### Relay Module:
   
   * A 5v relay is an automatic switch that is commonly used in an automatic control circuit and to control a high-current using a low-current signal. The input voltage of the relay signal ranges from 0 to 5V.

# 4. ARCHITECTURE

  ## Sturctural diagram:
  
  ![Structural diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/7_ImagesAndVideos/STRUCTURAL.png)
  
  ## Behavioural diagram:
   ### Flow chart:
  
  ![flowchart](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/7_ImagesAndVideos/flowchart.png)
  
   ### UML diagram:
   
   ![UML diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/7_ImagesAndVideos/UML.png)
  
# 5. APPLICATIONS

- It can be used in Home Gardening.
- It can be used in Agriculture Sector.
- 
    ## Advantages:
    - Just the right amount of water will be released.
    - The water will be directed to exactly where it is needed. 
    - An automatic shut off can help to keep water usage to a minimum.
# 6. REFERENCE
* http://www.electronicwings.com
