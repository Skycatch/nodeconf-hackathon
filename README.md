# NodeConf EU Skycatch Hackathon

Skycatch creates industrial strength products, services, and solutions that power some of the most complex projects on the planet. We capture the world's data and create visual intelligence to help people operate faster, safer, and smarter than ever before. Skycatch is the industry leader for commercial drone applications and data-imaging, building revolutionary products and providing unparalleled service.


As a company we use NodeJS and we're looking for brand new ideas to bring to our platform.

More about us: 

* [Skycatch High Precision Package: Mining](https://youtu.be/qpn89CkzVw8)
* [Mining Use Case: Improving Safety and Time to Data without Sacrificing Accuracy](https://youtu.be/4ae-138g3O0)

# Table of Content

* [NodeConf EU Skycatch Hackathon](#nodeconf-eu-skycatch-hackathon)
* [Challenges](#challenges)
  * [Challenge 1: Visualizing Drone Flights in 3D](#challenge-1-visualizing-drone-flights-in-3d)
  * [Challenge 2: Open Challenge](#challenge-2-open-challenge)
* [Mentors](#mentors)
* [Rules](#rules)
* [Price](#price)
* [Register](#register)

# Challenges

There will be two challenges for teams to choose from. Skycatch will choose one winner for each challenge based on criteria detailed below.

# Challenge 1 Visualizing Drone Flights in 3D

One of the main products of the company is the Flight1 app, our iOS application for iPad that allows the users to plan and flight missions. Each mission is made up of a flight path that covers a specific area designated by the user as well as custom altitude, overlap and direction; these items will modify the speed at which the drone flies. For every flight performed a file, called Flight Log, is generated that includes information gathered during the flight about the state of the drone.

Do you want to be more involved with the process? Come to our flight demo and see how we do flights.

We want you to experiment turning this flight log into a flight path and rendering the flight path in an interactive playground.

## Technical Details

#### Input

* The Challenge 1 folder will contain a [CSV file](https://github.com/Skycatch/nodeconf-hackathon/tree/master/Challenge%201) with flight logs and it's documentation. This file could contain information as latitude, longitude, flight time, altitude, speed, and much more data you can get from the flight.
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
  * Git repository. (Must have README) 
  * Demo video: take a video of your screen as you develop your app (Nice to have)
  * Document/Slides.
    * What you guys did.

#### Judging Criteria

* 40% Use of JS related technologies. 
  * Cesium
  * Use of the logs. 
* 30% Implementation completeness. 
  * Visualization of Map.
  * Visualization of flight path.
* 30% Creativity using the flight information. 
  * You could add altitud values at certain point in the path of the drone
  * You could show the direction of the drone
  * You could show the warning at certain point in the flight
  * Be free to create! 
  

# Challenge 2 Open Challenge

The output of a flight is a dataset containing a high quality photos of a site. We process this output to generate 3D maps where our clients can see and analyze their sites in our DataHub application.

Do you want to see this in action? Come to our DataHub demo.

We already show you what we can do with a dataset, now what can you do with it?. This is an open challenge where you can experiment, create, and innovate using the data that Skycatchs can provide you. 

## Technical Details

#### Input

* You will be given a [folder with high quality photos](https://github.com/Skycatch/nodeconf-hackathon/tree/master/Challenge%202)

#### Deliverables

* Implementation extracting useful information from dataset
* Pitch Document
  * Git repository. (Must have README) 
  * Demo video: take a video of your screen as you develop your app (Nice to have)
  * Document/Slides.
    * Problem definition. 
    * What you guys did.

#### Example

* GCPs are Ground Control Points used to get accurate data whenever the drone does not have a way to get its current position. They are essential because they are used later on the application to allow the user to manually move an image and select where the checkpoints are in the ground, enabling our platform to take that information and calculate corrections and create point clouds with minimum margin error.

#### Judging Criteria

* 40% Use of JS/Node related technologies. 
  * Use of the dataset and the elements inside. 
* 25% Business value.  
* 30% 20% Implementation completeness.  
* 15% Creativity.
  * Be free to create

# Mentors

#### [Andres Aguilar](https://github.com/anagac3) (IOS Developer in Flight1 Platform)

* He can help with questions regarding the flightlogs 
* Has IOS Knowledge

#### [Isaac Delgado](https://github.com/DZFX) (IOS Developer in Flight1 Platform)

* He can help with questions regarding the flightlogs 
* Has IOS Knowledge

#### [Luis Camargo](https://github.com/lcamargof) (Full Stack Developer JS, Engineer on Edge)

* Any questions about JS

#### [Bryan Montes](https://github.com/bryanmontesv) (Full Stack Developer, Engineer on Edge )

* Can help with questions in JS 

#### [Andre Deutmeyer](https://github.com/dremonkey) (Tech lead of Datahub)

* Processing pipline
* 3d Rendering
* Datahub

If you need any help please create an Issue and we will contact you or send us a slack!


# Rules

The Hackathon will start on **Monday, November 4th**, you may register on that day or later on. On **Sunday,November 10th** you will be able to find people from Skycatch that can give you feedback and answer questions about the challenges at the Welcome Reception and will run inside the Nodeconf.

Before **Wednesday, November 13th 9:00**, you will be required to send an email to both dmedina@skycatch.com and sosorio@skycatch.com with the submission of your project containing the challenge's deliverables.

Our team is going to choose the best submissions based on each challenge criteria, and the winner of each category will win a **DJI Mavic Pro**; that will be announced by **Wednesday, November 13th 17:30**. 

#### Restrictions

* 1 submission per team/person.

# Price

The winners of each challenge will win a **DJI Mavic Pro**

Let's hack! 

# Register

Please send an email to both dmedina@skycatch.com and sosorio@skycatch.com.

The email should contain:

* Subject: **NodeConf Skycatch Hackathon** and your names 
* Content: The teams name and emails of the team members

We will be creating a slack with private channels for each team !


