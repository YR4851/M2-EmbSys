
# ARCHITECTURE

  ## Block diagram:
  
  ![Block diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(110).png)
  
  ## Sensor: 
  
   ### Temperature Sensor (Thermistor):
   
   * This Thermistor is a resistor whose resistance is dependent on temperature here this change in resistence produces change in voltage, this voltage is taken as input to micro controller.
   
  ## Actuators:
  
   ### LCD Display:
   
   * Displays each and every value we enter in our keypad along with Temperature.
   
   ### LED's:
   
   * LED displays the on and off status of the device.
   
   ### Fan:
   
   * Temperature inside room is controlled by fan.
   
   ### Motor driver:
   
   * Helps in controlling motor of the fan.
   
  ## MICRO CONTROLLER AND MEMORY
  
   ### EEPROM
   
   * Here this is actually inside the microcontroller
   
   ### Clock
   
   * Here we are using internal clock of our micro controller.
   
   ### MicroController:
   
   * This is the main component which controls all the above mentioned part or thins of our embedded system.This interfaces keypad and LCD and controlls the fan,light and doors depending on the value we pressed on keypad.
   
  ## SUBSYSTEM & OTHERS
  
   ### Motor Driver Unit:
   
   * Helps in driving the motor for our fan by providing required power for them(we use motor driver L293).
  ## Sturctural diagram:
  
  ![Structural diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(113).png)
  
  ## Behavioural diagram:
   ### Flow chart:
  
  ![flowchart](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(109).png)
  
   ### UML diagram:
   
   ![UML diagram](https://raw.githubusercontent.com/YR4851/M2-EmbSys/main/Project/2_Architecture/Screenshot%20(111).png)
   
   
