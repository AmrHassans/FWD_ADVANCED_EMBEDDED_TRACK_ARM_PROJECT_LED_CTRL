# FWD_ADVANCED_EMBEDDED_TRACK_ARM_PROJECT_LED_CTRL
FWD_ADVANCED_EMBEDDED_TRACK_ARM_PROJECT_LED_CTRL

requirements
	

Control blinking of an LED for a user-defined ON and OFF periods

Create a function in the App layer that takes as an input from the user a specific ON time and OFF time in seconds,
lights a LED for the given ON time, and dim it for the given OFF time. 
It’s prohibited to use predefined delay functions, only timer driver functions can be used.
This function implements implicitly the PWM module using Timer Overflow.
