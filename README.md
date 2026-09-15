# I Get The Point Lab

## Problem Statement
Create a class called Point that is initialized with the x- and y-coordinates of a point in a Cartesian coordinate plane. 
Then, create the following overloaded operators on the class - distance, equality, inequality, midpoint, and output streaming.

## Acceptable Criteria
Create a Point class that takes an x and y coordinate in its constructor.
Override the - operator on Point so that it calculates the distance between the two points.
Override the == operator on Point so that it determines if two points are the same coordinate or different coordinates.
Override the != operator on Point so that it determines if two points are not the same coordinate or different coordinates.
Override the / operator on Point so that it determines midpoint between the two points.
Override the << operator on Point so that a user can stream a point as if it were a C++ string.
Make it so ++point increments the x coordinate, and point++ increments the y coordinate
Implement -- to decrement in the same way
Allow point[0] to access the x coordinate, and point[1] to access the y coordinate
Allow the usage of >> to create a point from an input stream, when the user enters coordinates in the form (x, y)

## Thought Provoking Questions
1. Do you like the names of the overloaded operators? Are there any that might cause confusion?
2. Why didn’t we overload operators for less than and greater than?
3. Would it make sense to add a Point * Point operator? What about int * Point?
4. How much would you have to change to make your Point be in 3 dimensions rather than 2?
