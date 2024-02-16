
# Description
The Public Transport Management System is designed to manage various aspects of a public transport system, focusing on passenger information, ticketing, bus management, controller management, station details, and destination cities. The system includes a database structure consisting of several tables: "PASSENGERS" (with information about passenger code, name, and age), "TICKETS" (details about ticket number, type, travel duration, price, preference, passenger code, and associated bus code), "BUSES" (with bus code, type, and number of compartments), "CONTROLLERS" (information about controller code, name, and allocated bus code), "STATIONS" (description of station code, station name, and lines), and "DESTINATION_CITIES" (with city code, name, and associated station code). Additionally, a table named "STATION_ROW" will be added to facilitate correlation between the "BUSES" and "STATIONS" tables, considering that multiple buses transit through multiple stations.

# Database Structure
- **PASSENGERS**: Contains information about passengers, including their code, name, and age.
- **TICKETS**: Stores details about tickets, such as ticket number, type, travel duration, price, preference, passenger code, and associated bus code.
- **BUSES**: Holds information about buses, including bus code, type, and number of compartments.
- **CONTROLLERS**: Manages data about controllers, including controller code, name, and allocated bus code.
- **STATIONS**: Stores details about stations, including station code, station name, and lines.
- **DESTINATION_CITIES**: Contains information about destination cities, including city code, name, and associated station code.
- **STATION_ROW**: Facilitates correlation between buses and stations, as multiple buses transit through multiple stations.

This project aims to streamline the management of public transport operations, providing efficient handling of passenger data, ticketing, bus management, controller assignments and station information.
