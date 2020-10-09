# DREAMI-Budget-Tracker

## Link to Deployed App
https://mysterious-eyrie-11908.herokuapp.com/

<img width="960" alt="Screen Shot 2020-10-09 at 10 00 31 AM" src="https://user-images.githubusercontent.com/65183415/95611453-b197b580-0a16-11eb-9105-0c4ddefd30b3.png">


I added functionality to an existing Budget Tracker application to allow for offline access and functionality.
The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

When brought back online:
  * Offline entries should be added to tracker.

## User Story

AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

## License 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Technology
Mongo DB
Node JS
DEPENDENCIES:
Express
Compression
Lite-server
Mongoose
Morgan