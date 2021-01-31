# HW-5-Workday-Scheduler

# Approach

For this assignment I chose to put my Javascript in the html file, the .css styling is all separate

For this assignment I chose to create an array of possible time throughout the day and append them to the main page container dynamically. Here is a picture of the array:

[Click here] (./Assets/hw-5-workdayscheduler-screenshot-1.png)

For loops:
The creation and appending of all bootstrap rows (containing columns for time, save button and input field) was done in a JQuery $.each loop taking up most of my script.

The next for loop was used to determine styling of input field based on what time it is in relation to the actual time of day pulled from the moment API. Then the styling class from css was assigned to the given input field being iterated through accordingly.

Local storage:
Upon refreshing all input values (if saved after something was entered). A local storage key and value are created upon using the save button. Every time the page loads it checks to see if a value is meant to be in the input field for a given row in local storage.
