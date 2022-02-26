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
   * Behavioural Diagram
     * High Level Flow chart Behavioural Diagram
     * Low Level Flow chart Behavioural Diagram
   * Structural Diagram
     * High Level UML Use Case Structural Diagram
     * Low Level UML Use Case Structural Diagram
5. Test plan and Output
   * High level test plan
   * Low level test plan
6. Application

# 1. ABOUT THE PROJECT
   ## Description:
   This is an automation project which is used to control the speed of fan automatically with the help of an temperature sensor which is used to sense the temperature here and sends the data forward by which means the fan speed is controlled to maintain a specific temperature at a pre-defined value of it.

   ## Features:
   * LCD Display shall be provided to know the temperature value we set.
   * Room Temperature shall be displayed on LCD.
   * Fan is on or off shall be displayed on LCD.
   * Fan speed shall be displayed on LCD.
   * LED's shall be provided for the funtioning display of embedded system.
   ## Working state of art:
   The main focus of this project is to control the tempereature and humidity of a perticular room in which it is being implimented with the help of sensors and the microcontroller. Here an LCD display is being used to display some information for user interfacing purpose. As if we see the growth of the technology around us, these types of technologies are the becoming the future of these industries.
   ## SWOT:
   ![SWOT analysis](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/1_Requirements/Screenshot%20(107).png)
   ## 5W & 1H
   ![5W & 1H](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/1_Requirements/Screenshot%20(108).png)
   
# 2. REQUIREMENTS
  ## High level requirements:

  | ID | Description | 
  | ----- | ----- | 
  | HR01 | system shall control fan speed by sensing the temperature. |
  | HR02 | there shall be an LCD display for the user interfacing. |
  | HR03 | LED's shall be used for showing the status of the system. |
  | HR04 | system shall sense the temerature and humidity. |

  ## Low level requirements:


  | ID | Description | HLR ID |
  | ------ | --------- | ------ |
  | LR01 | According to the values of the temperature the fan shall be controlled. | HR01 |
  | LR02 | According to the values of temperature on/off status of fan shall be controlled. | HR01 |
  | LR03 | LDC shall display the temperature of the room. | HR02 |
  | LR04 | Fan speed shall be displayed on LCD screen. | HR02 |
  | LR05 | Device shall pe placed in an appropriate place. | HR03 |
  | LR06 | Device shall glow LED red when placed wrongly. | HR03 |
  | LR07 | Temperature sensor shall detect the room temperature. | HR04 |
  | LR06 | Temperature detected shall be displayed on the LCD screen. | HR04 |

# 3. BLOCK DIAGRAM
  ## Block diagram:
  ![Block diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(110).png)
  ## Sensor: 
   ### Temperature Sensor (Thermistor):
      This Thermistor is a resistor whose resistance is dependent on temperature here this change in resistence produces change in voltage, this voltage is taken as input to micro controller.
  ## Actuators:
   ### LCD Display:
        Displays each and every value we enter in our keypad along with Temperature.
   ### Light:
        Lightning inside the room is controlled by light.
   ### Fan:
        Temperature inside room is controlled by fan.
   ### Motor:
        Helps in opening and closing our doors.
  ## MICRO CONTROLLER AND MEMORY
   ### EEPROM
        Here this is actually inside the microcontroller
   ### Clock
        Here we are using internal clock of our micro controller.
   ### MicroController:
        This is the main component which controls all the above mentioned part or thins of our embedded system.This interfaces keypad and LCD and controlls the fan,light and doors depending on the value we pressed on keypad.
  ## SUBSYSTEM & OTHERS
   ### Motor Driver Unit:
        Helps in driving the motor for our door and fan by providing required power for them(we use motor driver L293).
  ## Flow chart:
  ![flowchart](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(109).png)
