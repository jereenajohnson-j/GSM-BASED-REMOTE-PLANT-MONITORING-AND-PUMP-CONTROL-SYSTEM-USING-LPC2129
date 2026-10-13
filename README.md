# GSM-BASED-REMOTE-PLANT-MONITORING-AND-PUMP-CONTROL-SYSTEM-USING-LPC2129
The Smart Irrigation System Using GSM is an embedded system designed to monitor soil moisture and control a water pump remotely using SMS messages. The project uses an LPC2129 microcontroller as the main control unit, a soil moisture sensor to detect the moisture level of the soil, a SIM800C GSM module for communication, a 16×2 LCD to display system status, and an L293D motor driver to control the water pump.
The system allows the user to check the soil condition by sending an SMS containing the command “status” to the GSM module. The microcontroller reads the soil moisture sensor and determines whether the soil is wet or dry. The result is displayed on the LCD and sent back to the user's mobile phone through an SMS reply.
When the user receives a message indicating that the soil is dry, they can send the command “pump on” to start the water pump. The LPC2129 processes the command and activates the motor driver, which switches on the pump. The pump runs for 10 minutes and then automatically switches off. The LCD displays the pump status, and the GSM module sends confirmation messages to the user.
Components Used
LPC2129 Microcontroller
SIM800C GSM Module
Soil Moisture Sensor
16×2 LCD Display
L293D Motor Driver
DC Motor
LM393

