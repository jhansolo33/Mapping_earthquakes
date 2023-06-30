#  Mapping_earthquakes

## Overview

In this module, I used the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake was visually represented by a circle and color, where a higher magnitude has a larger diameter and is darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake.

Resources: I used the Leaflet library to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data. We added the USGS URL for earthquake data by navigating to the USGS Hazards Program, clicking the Earthquakes link to open the Real-time Data Feeds link and scrolled down to "GeoJSON Summary" Feed. There, we clicked the All Earthquakes link under the “Past 7 Days” heading.

Data Source: majorAirports.json, torontoRoutes.json, tectonic_plate_starter_logic.js, tectonic_plate_starter_logic.js, tectonic_plate_starter_logic.js and index.html

Software: JS, D3, Leaflet, JavaScript, JSON, GeoJSON and IO (Web Server), ECMAScript and Visual Studio Code 1.50.0

Objectives • Create a branch from the master branch on GitHub. • Add, commit, and push data to a GitHub branch. • Merge a branch with the master branch on GitHub. • Retrieve data from a GeoJSON file. • Make API requests to a server to host geographical maps. • Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library. • Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls. • Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps. • Render maps on a local server.

Summary Step 1. Maps all recorded earthquakes in the past seven days.

Step 2. As a first step in making the earthquake data more visually appealing, we added some styling to the earthquake data in step 2 and varied the radius of each earthquake based on the magnitude.
![image 10](https://github.com/jhansolo33/Mapping_earthquakes/assets/119264589/dda49fb5-4384-43ca-aa29-d89d2a9c090e)


Step 3. 
lthough, the size of the earthquake data based on magnitude looks great, it’s hard to tell the difference between earthquakes within the same area. We come up with the idea to color-code the earthquakes based on magnitude. We, also, added the magnitude and location as a popup for each earthquake in step 3.

![image 12](https://github.com/jhansolo33/Mapping_earthquakes/assets/119264589/5515bad7-be92-46fe-8a5f-819341e45eaf)

Step 4. The map has the earthquake data as an overlay on both the Streets and Satellite tile layers, so users can turn the data on and off.
![image 13](https://github.com/jhansolo33/Mapping_earthquakes/assets/119264589/490d0f36-d12b-4345-aa3a-3d4e6757fcb0)
