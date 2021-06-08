## Live Deploy
https://vygoth.github.io/Work-Day-Scheduler/

# Work Day Scheduler

# Contact
Vygoth
JeremyJoanet@Protonmail.com

## Description
Day planner made to help learn bootstrap. Made in conjunction Matt Reisdorf and Zach Duty.

Since this is an odd week, we had our starter html and css already written. We used bootstrap to import some list elements to create a table with an editable input message field and an operational save button, which works to store whatever is in the input field to local storage.

For first time use, the current day is stored to local storage.
For subsequent use, the currentDay variable in local storage is cross referenced to the actual current day, if they don't match, the local storage is wiped.
If LS isn't wiped, the input fields are auto populated to associated data stored in local storage.

There is a series of IF statements in the JS to check current 24 hour time to an associated block, and change the color of the block based on if its time is upcoming, present or past.

Bootstrap certainly made this project must easier.

## Table of Contents
- [Usage](#Usage)
- [Credits](#Credits)
- [Screenshot](#Screenshot)

## Usage
This application is deployed on pages, link at the top.

## Credits
Zach Duty, Matt Reisdorf

## Screenshot
![screenshot](./assets/imgs/screenshot.PNG)
