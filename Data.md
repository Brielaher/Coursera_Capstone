Data

Based on definition of our problem, factors that will influence our decission are:

number of car collisions in the neighborhood (any severity level)
number of high level car collision
road condition when collision happenning
We decided to use regularly spaced grid of locations, centered around city center, to define our neighborhoods.

Following data sources will be needed to extract/generate the required information:

centers of candidate areas will be generated algorithmically and approximate addresses of centers of those areas will be obtained using Google Maps API reverse geocoding
number of collision and their type and location in every neighborhood will be obtained using Foursquare API
number of high severity collisions locaiton
