
Algorithms to optimize Dial-A-Ride operations with multiple drivers in a 2-Dimensional space.

A quick summary of this project can be found here: https://drive.google.com/file/d/1kU6srgm4wXbBzQC8KtPu1BZ_C9DPZOgh/view?usp=sharing

A more detailed final report of this project can be found here: https://docs.google.com/document/d/1HG4BfCG4YzMCN69pZmlEUV0qOmZbThrSuBIE5IHiCxA/edit?usp=sharing
__________________________________________________________________________________________

Algorithms:

EarliestPickUp- Requests sorted on earliest pickup time

EarliestDropOff - Requests sorted by earliest drop off time (similar to activity selection)

MinFValue - Requests sorted by Min F value

MSBP - The furthest we got on our multi-driver segmented best path algorithm (needs to be tested more)

Classes:

Graph - Has a width, height, and time limit that can be changed. Also contains methods to generate random points and also a hard-coded list of points (points are an array of two doubles).

Request - Each request has a start position, finish position, pickup time, weight, f_val, and location.

Driver - Each driver has a schedule of type List<Request> and a position on the graph

Other Files:

Simulation - this is what we have been using in the Summer of 2023 to test our algorithms.

WeightsCombination - used for finding the weights for MinFValue

WeightedRoutingTest - unused; for single-driver



