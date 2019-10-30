# Challenge 1: Visualizing Drone Flights in 3D

One of the main products of the company is the Flight1 app, our iOS application for iPad that allows the users to plan and flight missions. Each mission is made up of a flight path that covers a specific area designated by the user as well as custom altitude, overlap and direction; these items will modify the speed at which the drone flies. For every flight performed a file, called Flight Log, is generated that includes information gathered during the flight about the state of the drone.

Do you want to be more involved with the process? Come to our flight demo and see how we do flights.

We want you to experiment turning this flight log into a flight path and rendering the flight path in an interactive playground.

## Technical Details

#### Input

* We're going to publish a flight log (CSV) when the Hackathon starts. This file could contain information as latitude, longitude, flight time, altitude, speed, and much more data you can get from the flight.
* CesiumJS is an open source JavaScript library for creating world-class 3D globes and maps with the best possible performance, precision, visual quality, and ease of use.

#### Useful resources 

* [Cesium sandcastle playground](https://sandcastle.cesium.com)
* [AirData](https://airdata.com/)
* [DroneLogBook](https://www.dronelogbook.com/hp/1/index.html)

#### Deliverables

* Implementation
  * Flight path rendered in Cesium in 3D
  * Nice to have  
    * Display additional information from flight log
    * We're open to all new ideas to improve the interaction of the user and the map.
    * What can a machine learn from FlightPaths?
* Pitch Document
  * Git repository. README is appreciated. 
  * Demo video.  Show us how it works.
  * Document/Slides.
    * What you guys did.
    * What you plan for the future.

#### Judging Criteria

* 40% Use of JS related technologies. 
  * Cesium
  * Use of the logs. 
* 30% Implementation completeness. 
  * Visualization of Map.
  * Visualization of flight path.
* 30% Creativity using the flight information. 
  * Be free to create! 
