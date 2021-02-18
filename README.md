# pruteus_logicalcuircet_of_cooler
End-of-semester project of logic circuits and digital systems
Water cooler controller
General explanation: This controller, which replaces the water cooler switch, has the following function:
1) By pressing the on / off switch, the water pump starts to turn on and after 1 minute, the engine starts at the bottom
falls down. On and off is indicated by one LED and engine speed by two LEDs.
2) Each time you press the fast / slow key, a relay changes position and identifies the LED for the engine speed.
3) The environment is measured by a digital temperature sensor and its output is a binary number 6
Bits are possible in the range of zero to 64 degrees Celsius. The read value must be on two .seg-7
is shown.
4) The threshold temperature can be seen by two up / down switches between 15 and 30 settings. This value is on two monitors .seg-7
is shown.
5) By pressing the auto key, the controller enters the automatic mode and if the steps are on
It is done and the air conditioner is usually turned off. Auto mode with on
Becoming a special LED.
6) By pressing the timer key, the circuit is entered when it is and each time it is pressed for 30 minutes (5.0 hours) by
The number is added on two time displays (maximum 5.9) over time, the value displayed every half hour
it is decreasing. Successfully end time if the air conditioner is off and on if it is off. with change
The time value mode is displayed - and the circuit exits the timer mode.
Inputs: OFF / ON - AUTO - UP - DOWN - TIMER - Frequency clock pulses
1Hz - Temperature value in 6 bits.
Outputs: Pump relay steering - motor relay steering - remote relay steering (dual mode) - LED on / off -
Round LEDs - Auto mode LED - Ambient temperature display) 2 digits seg-7 -) Threshold temperature display) 2 digits
.) 7-seg digit 2 (display time (- 7-seg
These three displays can be converted to one) or two (2-digit and three-digit displays) or two (LEDs. The value is displayed
It changes every 3 seconds and the LED indicates how much each number corresponds to.
Execution steps:
1) Circuit design is schematically simplified
2) Write Verilog code in a modular way
3) Simulation
4) Preparation code on CPLD or FPGA
2) Detail circuit design with logic ICs
3) Circuit simulation with Proteus
4) Circuit construction
Project time and delivery details will be announced later
