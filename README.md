# meal_scanner_compiled

 Executable file for Food Waste Management System interface.

## Login Details:
**User:** siauser1
**Password:** password

## Usage instructions:
### To scan for leftovers:
1. Click "Create New Flight" in Flight Manager. Enter Departure & Arrival Airport (e.g. SIN/HKG) and Departure Date/Time (e.g. 20/7/2018 07:30:00 AM). As sample data provided in flight schedule APIs does not include the flights used in passenger and meal uplift plan APIs, please also enter Arrival Date/Time (e.g. 20/8/2018 11:20:00 AM) and Flight Number (e.g. 890).

Press "Auto-Fill" to get passenger data, and click "OK". The flight and any corresponding meals will be added to the database.

2. Select the flight that was added in the flight manager, and click "Scan Leftovers".

3. When the video window appears, staff may begin to scan the food packages. Sample QR codes are provided in the folder "Sample QR Codes". The food packages should be scanned from the left of the image frame to the right.

4. Once done, press "Q" on the keyboard. The system will automatically record the leftover units in the database and compute the wastage statistics.

### To view wastage statistics:
1. Under flight manager, the aggregated wastage statistics are shown in the rightmost column of the table.

2. To drill down into the meals served on a particular flight, select the flight in the flight manager, and click "View Meals Served on Selected Flight".

3. The meals served will be displayed on the Meal Schedule manager, with wastage statistics shown in the rightmost column of the table.

4. To drill down further into individual meal options, select the meal schedule in the Meal Schedule Manager, and click "View Options for Selected Meal".

5. The options provided and their uplift/ leftover/ wastage statistics are shown at the right of the table.