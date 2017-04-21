# ADS1115-auto-gain

This code automatically sets the gain of the ADS1115 16-bit ADC depending on the input voltage (between 0-5V). 
A range of 7,000-30,000 is defined as acceptable ADC readings for a particular gain setting. Anything higher or lower than this will make the code increase or decrease the gain automatically. This code will allow analog devices of varying voltage ranges to be plugged in without the need to reconfigure the code.

You can play around with the minimum and maximum ADC range to adjust sensitivity as required.
