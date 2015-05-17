# Project Overview

This project was designed to add testing functionality to a given a web-based application that reads RSS feeds. The required testing framework for this task was [Jasmine](http://jasmine.github.io/). To help with selecting some UI elements I also added [Jasmine-jQuery](https://github.com/velesin/jasmine-jquery). Since this is a Udacity Front-End-Developement Nano Degree Submission, I will go into detail how to run the project and what resources I used.

## How to start the project
There are two different ways to start the project:
1.) local setup
clone this repo and open the index.html page, you should see the feedreader application and the jasmine output below.
2.) hosted setup
open http://ceckleder.github.io/frontend-nanodegree-feedreader/ you will see the feedreader application and the jassmine output.

# Which test had been added


1. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. A new test suite named "The menu".
4. A test that ensures the menu element is hidden by default. 
5. A test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
6. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Since, loadFeed() is asynchronous, this test requires the use of Jasmine's beforeEach and asynchronous done() function.
7. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. 

## Ressources used to finish this project
* Jasmine documentation (http://jasmine.github.io/2.0/introduction.html)
* Jasmine jQuery documentation (https://github.com/velesin/jasmine-jquery)
* Udacity Forum (especially for test 7)

