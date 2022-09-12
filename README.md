# Notification_MovieBooking_app
# Notification Service 
## _Sending notification emails asynchronoulsy_ 

This code base contains logic/structure  for sending the notfication email asynchronosly
## Features
* Cleint can request the Notification system to send notifications to all the recipeints
* Notfification Service will run a job every 30 seconds to gather all the requests for last 30 seconds and send notifications


## Prerequisite
- Understanding of Node.js
- Understanding of Async Await
- Mongo DB locally installed and running
- Cron Expressions

## Tech
- Node.js
- Mongodb


## Installation

this app requires [Node.js](https://nodejs.org/) v14+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd NotificationService
npm install
npm run devStart
```
