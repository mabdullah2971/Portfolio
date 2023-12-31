# Airline Data Analysis
* **Skills:** Data Analysis <br>
* **Tools:** SQL <br>

Performed exploratory analysis on the [Airline Dataset](https://www.kaggle.com/datasets/mohammadkaiftahir/airline-dataset/code). The goal of this project is to demonstrate proficiency with SQL by performing queries that showcase specific techniques such as joins, aggregate functions, subqueries, etc.

## Code Files:
[`AirlineDataAnalysis.ipynb`](https://github.com/mabdullah2971/Portfolio/blob/main/Airline%20Data%20Analysis/AirlineDataAnalysis.ipynb)

## Tables & Columns of Interest

### aircrafts_data
* Range: We can use this to determine which airplaines are situatable for which routes

### airports_data
* city: with enrichment we can use this to know which cities serve as flight hubs, which cities have the most/fewest number of connecting routes
* coordinates: via enrichment, we can use this to figure out what the longest/shortest flights are

### flights
* flight_id: helpful for counting flights 
* departure_airport & arrival_airport: These two columns can help us establish a route for each flight. We can use this to know which airports serve as hubs, what are the most common routes, the rarest flights, etc. This data can be linked with the airports dataset for enrichment.
* actual_departure & actual_arrival: can use this to determine longest/shortest flights
* aircraft_code: can be used to know which kind of airplanes are travelling which routes
* status: could check how many flights get cancelled by airline, city, etc

### ticket_flights
* flight_id : connects this table to the main flights table
* amount: indicates how much the passenger paid
* fare_conditions: the seat class they travelled in
 
