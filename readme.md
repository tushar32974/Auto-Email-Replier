# Email Auto Replier


This repository houses Auto Email Replier, an application developed using Node.js and Google APIs. The app is designed to automatically respond to emails received in your Gmail mailbox when you are away on Out-Of-Office ("OOO").

## How to Get Started:

First you have to set up the OAuth 2.0 authentication for your application whose documentation and steps can be found out there on internet.

After that clone the repository, install the dependencies and get started :)

## Desired Improvements
Some of the improvements that I think are desirable are :

1. The code could be made better to handle a large number of emails more smoothly and quickly.

2. Make sure that secret information like client secrets and refresh tokens are stored safely and not exposed in the code.

3. The code currently logs errors that happen, but it could do a better job of dealing with them when they occur.

4. Instead of using a random interval for tasks, consider using a scheduling tool like cron jobs to better manage when emails are sent.