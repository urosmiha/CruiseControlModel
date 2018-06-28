# CruiseControlModel
Cruise control for a car designed in Esterel

## Description:

Cruise control designed in Esterel language.

------------------------------

## Recquired Files:

	1. CruiseControl.strl
	2. CruiseControl.h
	3. CruiseControl_data.c
	4. ctype.c
	5. Makefile
	
------------------------------
	
## Running the program:

	1. Open command window and navigate to the destination of this folder.
	2. Type: make CruiseControl.xes
	3. Type: ./CruiseControl.xes
	4. The UI window should be displayed
	
-------------------------------
	
## Simulation:

###	Inputs:
	1. on_button 	= Turn the cruise control ON.  
	2. off_button	= Turn the cruise control OFF.
	
	3. accel 		= Accelerate pedal position in %
	4. brake 		= Brake pedal position in %
	
	5. resume		= Resume from Stand By State (STBY)
	
	6. quick_accel	= Increase Cruise speed by 2.5km/hr
	7. quick_decel  = Decrease Cruise speed by 2.5km/hr
	8. set			= Set current vehicle speed to cruise speed
	
	9. vehicle_speed = Current vehicel speed in km/hr
	
###	Output:
	1. cruise_speed 	= Cruise speed that vehicle is trying to match

	2. throttle_cmd 	= Throttle position expressed in % 
	
	3. cruise_state 	= Current state of the cruise system, expresed as integer, where:
	
		1 = OFF
		2 = ON
		3 = DISABLE
		4 = STDBY
		
----------------------------------	
		
	** END OF README **
