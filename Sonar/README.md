# Lowrance sonar: data analysis in python

|Description	|  A notebook to decode the sl2 binary file and display the trail and the bouncing data  |
| :-------------| :----------------------------------------------------------- |
|Author		| Corrado Motta |
|Mail		| corradomotta92@gmail.com |
|Date		| 09/2020 |

## description ##
---

This notebook is a first attempt to decode the sl2 file by proceeding step by step and by providing some textual explanation where needed. It does the following:

- Decode the sl2 file and store the data into variables.
- Produce a point shapefile containing the track and the depth for each point detected by the sonar.
- Produce two maps showing the track, the depth and the location with coordinates.
- Process the bouncing data and produce a plot to show them (similarly to ReefMaster).

Please note that the script is n completed but can be very useful for whoever wants to work further on this topic in the future. Future possible steps are:

- Reduce the amount of code (many smarter way to write the script and avoid so many data transformation and for loops) and polish it.
- Look into the bouncing data and check its variation when Posidonia is detected (first step into automatizing the analysis).
- This script is very much based on existing resources Tim found on GitHub:

- https://github.com/nwhoffman/sl2PyDecode
- https://github.com/bjcosta/sonar

*Notes*

1. Code in its current form supports Python 3.6.
