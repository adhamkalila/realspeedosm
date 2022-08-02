# realspeedosm
This project contains code to edit OSM files to assign real speed to ways or partial ways from observed speeds.

### Repo Contents
- realspeedosm.py:		python code with functions
- Code description.pdf:	description of the steps involved with pseudocode diagram
### Inputs
1. OSM file for road network converted to .osm format
2. speeds csv from Uber or Mapbox

### Output
1. OSM file in .osm format

Note: you will need to convert the .osm file back to .pbf to use with r5 or OpenTrip Planner