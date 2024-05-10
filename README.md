# keithley_2182A_nanovoltmeter
This simple program just reads voltage values from Keithley 2182A nanovoltmeter. 

This simple program opens communication with Keithely 2182A nanovoltmeter using pyVISA. My example code has a GPIB interface to communicate with the nanovoltmeter. I use a continuous while loop to query for voltage values using the 'FETCH?' command. I continuously save measured voltage values to the text file.  
