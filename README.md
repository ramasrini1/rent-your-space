# Rent My Space (driveway/swimming pool/backyard)

## Introduction
Have you gone to a beach on weekends and struggled to get a parking spot or 
had trouble in finding a place to park near big events like the 4th of July firework ? 
Or do you wish to host a swimming pool party but are restriced because you 
don't have swimming pool in your house? 

‘Rent My Space’ app can provide solutions to these problems. This app provides a 
listing of all the properties for renters to book. The renters can book the 
property for using the driveway, backyard swimming pool or other spaces.

## Users 
There are 2 types of users for this app 1) property owners and 2) renters
The property owners will provide information about their property that they 
plan to rent through a form input. The property will then be listed on the app. 
The renter can book the property based on the availability. The renter can  make 
payments to the owner for using the property. If the property is rented for using 
the driveway. The renter uploads an image of vehicle id so the owner can verify the correct renter is using the driveway.

## Data
The data for this app will be generated by the users of the app( the owners and
renters). The CRUD operations can be performed through the end points of the REST API. 


## Approach
* The front end will be a React app (client)
* The backend will be a Express (Node.js) server.
* Database: PostgreSQL

## Features
* User sign in, authentication
* File uploads from client to server
* Booking calendar
* Restricted page access
* Search features based on filters
* Payment through Venmo/Paypal Api
* Admin dashbord.

## Hosting
The app will be hosted on Heroku

## Stretch Goals
* Use of Google API for maps and prepopulating the form.
* Paypal Api for seamless payments.
* Message board for communicating betweeen renters or owners
* Use of Typescript instead of JavaScript

## Schema for the DB
https://docs.google.com/document/d/1TpySxFjMZNoi6P3eLA5IZusexQ5Ruj0LUNHSJKAKKUc/edit?usp=sharing
