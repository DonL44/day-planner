# 📆 Work Day Scheduler

A simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery and Moment.js.


## Deployment

Demo: https://donl44.github.io/workday-scheduler/

![Day Planner Demo](https://raw.githubusercontent.com/DonL44/workday-scheduler/main/assets/images/workday%20calendar.png)

## Built With

  * HTML
  * CSS
  * JavaScript
  * jQuery

## Description
a simple calendar application that allows a user to save events for each hour of the day. It runs in the browser and feature dynamically updated HTML and CSS powered by jQuery.

## User Story
```
- AS AN employee with a busy schedule
- I WANT to add important events to a daily planner
- SO THAT I can manage my time effectively
```

## Acceptance Criteria
```
- GIVEN I am using a daily planner to create a schedule
- WHEN I open the planner
- THEN the current day is displayed at the top of the calendar
- WHEN I scroll down
- THEN I am presented with time blocks for standard business hours
- WHEN I view the time blocks for that day
- THEN each time block is color-coded to indicate whether it is in the past, present, or future
- WHEN I click into a time block
- THEN I can enter an event
- WHEN I click the save button for that time block
- THEN the text for that event is saved in local storage
- WHEN I refresh the page
- THEN the saved events persist
```

## Usage
- This workday calendar display work hours of the day 8AM - 5PM.
- On the top of the page, current day and date is diplayed.
- Each time block is color coded to indicate whether it occurs in the past(gray), present(red), or future(green).
- Each time block has an input field and save button where users can store their schedule.
- Once it saved, it will store in their local storage.
- This calendar is desktop and mobile compatible.
