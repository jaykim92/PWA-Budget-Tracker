# PWA-Budget-Tracker

## Description
This progressive web application allows for users to keep track of one's budget and spending through manually entering in purchases and income. Transactions will be cached if the application goes offline and updated when back online using a service worker.

## Successes and Challenges
Challenges for this project pertained mainly to caching the correct files to get the app running offline. The problem was solved by making sure there was a new version of the files to be cached as well as making sure to link the db.js file to start a queue of updates in the IndexedDB when the app goes back online.
