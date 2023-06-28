# Capstoneprj-Part3

Question 1: Haversine Distance Calculation - Port Distance to Jurong Island

Overview:
This code calculates the Haversine distance between different ports and Jurong Island using latitude and longitude coordinates. The Haversine formula is used to estimate the distance between two points on the Earth's surface.

Usage:
1. Install the required libraries: pandas, math, IPython.display.

2. Prepare the data:
   - Place the port data CSV file in the same directory as the Python script.
   - Ensure the CSV file has the required columns:
     - Latitude_degrees, Latitude_minutes, Latitude_hemisphere
     - Longitude_degrees, Longitude_minutes, Longitude_hemisphere
     - Wpi_country_code, Main_port_name

3. Update the script:
   - Replace 'new_data.csv' with your CSV file name.
   - Replace '1.285925, 103.727188' with Jurong Island's latitude and longitude.

4. Run the script:
   - Execute the script using a Python IDE or run 'python script_name.py' in the terminal.

5. View the output:
   - The script calculates distances from each port to Jurong Island using the Haversine formula.
   - The resulting table, showing port names and distances to Jurong Island in meters, is displayed.


Question 2: Port Data Analysis - Country Occurrence and Highest Count

Overview:
This code analyzes port data to determine the occurrence of each country in the dataset and identifies the country with the highest count.

Usage:
1. Install the required library: pandas.

2. Prepare the data:
   - Place the port data CSV file in the same directory as the Python script.
   - Ensure the CSV file contains the 'Wpi_country_code' column.

3. Run the script:
   - Execute the script using a Python IDE or run 'python script_name.py' in the terminal.

4. View the output:
   - The script calculates the occurrence of each country in the dataset.
   - The resulting table displays the countries and their counts in descending order.
   - The country with the highest count is identified separately.

Question 3: Port Distance Calculation and Filtering
This code calculates the distance between a target location and various ports using the Haversine formula. It then filters the ports based on supplies availability and displays a table with specific columns.
Prerequisites
•	Python 3.x
•	pandas library
Usage
1.	Place the data file named new_data.csv in the same directory as the code file.
2.	Run the code in a Python environment that has the pandas library installed.
Steps
1.	Load the port data from the new_data.csv file into a pandas DataFrame.
2.	Define a function using the Haversine formula to calculate the distance between two points on Earth's surface.
3.	Specify the latitude and longitude of the target location.
4.	Calculate the distance between the target location and each port in the DataFrame using the Haversine formula.
5.	Find the closest port based on the calculated distances.
6.	Filter the ports for supplies availability (provisions, water, fuel oil, diesel oil).
7.	Create a table with the desired columns (Main_port_name, Wpi_country_code, Longitude_degrees, Latitude_degrees).
8.	Display the resulting table.
Output
The code outputs a table containing the Main_port_name, Wpi_country_code, Longitude_degrees, and Latitude_degrees of the closest port that meets the supplies availability criteria.

