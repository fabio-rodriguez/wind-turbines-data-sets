# wind-turbines-data-sets
Data sets from sensors outlets of two wind turbines. Each data set have the following columns:

Date	
Elec Gen (kWh)	
Wind speed (Ø) [m/s]	
Rotor speed (Ø) [rpm]	
Reactive power (Ø) in kW	
Power (Ø) [kW]	
Nacelle position [°]

For each sensor and each instant of time, there are three columns. Ex: ("Elec Gen (kWh)", "Elec Gen (kWh) - Expected", and "Elec Gen (kWh) - Failure") 

The first column <sensor> is the outlet value of the sensor subject to fails. The second column <sensor - Expected> contains the expected fault-free value of the sensor. The third is a binary value column containing {0,1} whether or not the sensor outlet is a failure (0: fault free, 1: failure).   
