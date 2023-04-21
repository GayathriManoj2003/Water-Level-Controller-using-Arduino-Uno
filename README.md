# Water-Level-Controller-using-Arduino-Uno

Objective:
	To automate home water pump systems that pump water from the sump to overhead tank by using water-level sensor and ultrasonic sensor.

Abstract:
	The water pump automation system has been built using an arduino uno microcontroller board. A water level sensor and ultrasonic sensor are installed on the overhead tank to enable detection of water level. A water level threshold is set; when the readings of the sensors fall below the threshold a signal is sent to the motor and the motor is switched on. An LCD module is also installed which allows us to continuously monitor water level readings.

# Demo:
LCD displays Value (ultrasonic sensor readings converted to distance in cm) and Water Level - Empty, Low or High.
A paper cup has been used to represent water tank.
The height of the cup is about 7 cms.

# Case 1:
When the cup contains no water (distance from sensor greater than or equal to 7 cms). W Level - EMPTY

![Image showing LCD Module output when tank is empty.](/Images/water_level_empty.jfif?raw=true "Water Tank Empty")


# Case 2:
When water-level in cup is low (distance from sensor greater than 3 cms). W Level - LOW

![Image showing LCD Module output when water level in tank is low.](/Images/water_level_low.jfif?raw=true "Water Tank Empty")


# Case 3:
When water-level in cup is high (distance from sensor within 3 cms). W Level - HIGH

![Image showing LCD Module output when water level in tank is high.](/Images/water_level_high.jfif?raw=true "Water Tank Empty")

Using water-level sensor to capture readings:

![Image showing LCD Module output on taking water-level sensor reading.](/Images/water_level_sensor.jfif?raw=true "Water Tank Empty")