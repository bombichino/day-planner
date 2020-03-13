# Homework 5 -  Day-Planner

## Task:

According to the user story and acceptance criteria below, craft a calendar web application that allows you to save the events for the hours in a given day. 

## Development for the future:

If I were to develop this further, I would make an app that would allow you to store multiple days and switch between them. With the nature of this app and assignment, it seems we are limited to a given day, and one can overwrite tasks in a given hour, but there is no need for the functionality of clearing the local storage. I would then:
-make a button to clear a given task
-make a button to clear the storage for a day
-create a system whereby you can navigate through different days
-update my local storage so that I could store and recall the data by day rather than by hour.

05 Third-Party APIs: Work Day Scheduler
Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.
You'll need to use the Moment.js library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

User Story
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively

Acceptance Criteria
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist