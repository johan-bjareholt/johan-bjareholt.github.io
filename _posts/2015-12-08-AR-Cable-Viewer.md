---
layout: post
title:  "AR Cable Viewer"
date:   2015-12-08 12:00:00
status: complete
categories: project android java
---
Status: Complete

During the first semester of my second year at Blekinge Institute of Technology, I had a course named 'Idividual Project' where we got assigned a company which gave us a project to work on for 4 months.
I got to work for Softhouse Baltic AB, a division of Softhouse Consulting in Karlskrona which at the time had 52 employees.
My project was to create an prototype app for ABB in Karlskrona who work with high voltage cables.
The app was supposed to display the cable routes in two views, a regular map view for good overview and an AR View for the field workers.
It also had a administration web interface for managing the cable routes.
The project started in September 2015 and was completed in December 2015.

The backend is written in NodeJS+Express with MongoDB as the database.
The web frontend uses a custom rest interface and the Google Maps API.
The app is written with Android SDK v21 and uses the Volley REST library, the Map View is using the Google Maps API and the AR view uses the Camera2 api and with custom code for the sensors and a canvas layer on top of the camera fragment.

<figure style="width: 100%;">
	<img style="width:32%; display: inline;" src="/img/projects/ARProject/screenshot1.png">
	<img style="width:32%; display: inline;" src="/img/projects/ARProject/screenshot2.png">
	<img style="width:32%; display: inline;" src="/img/projects/ARProject/screenshot3.png">
</figure>
