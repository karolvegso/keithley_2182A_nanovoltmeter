# keithley_2182A_nanovoltmeter
This simple program just reads voltage values from Keithley 2182A nanovoltmeter. 

This simple program opens communication with Keithely 2182A nanovoltmeter using pyVISA. I have a GPIB interface in my example code to communicate with Keithely 2182A nanovoltmeter in my example code. I use a continuous while loop to query for voltage values using the 'FETCH?' command. I continuously save measured voltage values to the text file.  
