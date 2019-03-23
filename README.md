# multi-VL53L1X


A simple class that allows multiple VL53L1X sensors to be used

Upon intialization, specify the ports of up to 5 sensors.

Use inialize_sensors() subroutine to start the sensors (default is long range, 4m).

Use get_sensor_readings() subroutine to get the sensor readings until the attribute self.terminate is set to True.

This code works when multithreaded as well.



This code was part of the SUTD SAFMC 2019 Category D2 Autonomous drone where 5 TOF sensors were used for localization.
