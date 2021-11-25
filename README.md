# DWR-Extraction
Code to extract, clean and organize the data from California Department of Water Resources Manual Dataset.
The code will avarge the readings to monthly and drop any empty readings. the readings can be scanned for any period in time, its currently set to extract wells that have at least 10 years worth of readings. it can be increased or decreased based on the use case. it will also drop all the unnessecary columns, keeping only the well name, X,Y, and reading values. the output will be saved into a CSV file.
