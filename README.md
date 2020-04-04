# Progressive Budget App
​
## Overview
Making and keeping track of a budget can be a very hard task, with this app I plan to make things a little bit easier on a person that 
is trying to keep up on this. One of the reasons that my app is unlike others is that it allows you to keep track of your budget online
and offline. 

### Links

Github repository: https://github.com/dawson-hamilton/budget-tracker

Heroku site: https://cryptic-taiga-45369.herokuapp.com/
​
### Problem
User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
​
### Solution

This application allows a user to reach track their individualized transactions online or offline for seamless financial decisionmaking.
​
## Tech and Features Used
​
* Node.js
* Javascript
* JQuery
* Mongo DB
* NPM Modules: Express, Mongoose, Morgan
* MVC methodology

## How to use
​
On the hosted heroku webpage, enter the title/topic of the transaction and the amount. Then, decide whether to add to your current account or subtract from it based on the transaction time. See a graphical representation of your financial progress below the main chart.

## Technical Overview

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.
Offline Functionality:

Enter deposits offline
Enter expenses offline

When brought back online:
Offline entries should be added to tracker.
