# HW8


Please use D2L to turn in both the HTML output (NOTE leaflet requires HTML) and your R Markdown file in.

### Q1. (5 points)
Use the Baltimore Towing Dataset for this question.
```
library(readr)
baltimore<- 
  read_csv('http://www.math.montana.edu/ahoegh/teaching/stat408/datasets/BaltimoreTowing.csv')
```

#### a (5 points)
Print a table that displays how many vehicles were towed for each of the 24 hours of the day.


#### b (5 points)
Compute the total fees collected for each of the following groups of vehicle types

1. Cars - (Car, convertible, SUV, Station Wagon, Sport Utility Vehicle, Van, Taxi)
2. Trucks - (Pick-up Truck, Pickup Truck, Truck)
3. Semi Trucks - (Tractor Trailer, Tow Truck, Tractor, Construction Equipment, Commercial Truck)
4. Bikes - (Motor Cycle (Street Bike), Dirt Bike, All terrain - 4 wheel bike, Mini-Bike)

### Q2. (5 points)
Use the [leaflet package](https://rstudio.github.io/leaflet/) and create an interactive map. Include markers to show all of the places that you have lived.

