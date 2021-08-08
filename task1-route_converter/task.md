## task 1 - Route Converter

# Intro

Developers often has to work with a weird data inputs and formats. This is the example of this statement. Real life problem that I had as a Navigating Officer on a ship, so I have automated it. 

You will have to make a small research to understand the exercise better. Some info you will find in Resources section. Rest you will have to find on your own.

# Prerequisites

You are given a txt file (attached) with the information about your route waypoints. 

[wp] “name” - Name of waypoint
[pos] xxx xxx - Latitude and Longitude
[corridor] xxx - Safety corridor on the right
[corridor_port] xxx - Safety corridor on the left

# Task 
Only with frontend create an app to get input from user ([route.txt](../route.txt)), read it, process it and return as a csv file. 
 
- File will be only txt and in the format provided
- Each waypoint in csv must be “**No.**, **Name**, **Latitude**, **Longitude**, **Corridor**, **Corridor-Left**, **Course**, **Distance**”
- **No.** stands for number of waypoint and starts from 1
- **Latitude** and **Longitude** to be in degrees and minutes
- **Latitude** format “xx xx.x N/S”
- **Longitude** format “xxx xx.x E/W”
- **Corridors** and **Distance** must be in Nautical Miles
- **Course(Bearing)** must be in degrees (000 - 360 format)
- Last waypoint does **not** have **Course**, **Distance** and **Corridors** even if it is given in a file

# Resources
JavaScript library for calculations and conversion 
[Movable](http://www.movable-type.co.uk/scripts/latlong.html?from=48.9613600,-122.0413400&to=48.965496,-122.072989)

# Bonus points
Once you generated a csv file show the map and plot these waypoints on it using Google maps API or any other API to your taste