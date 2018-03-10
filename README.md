# WolfPlanner
``Software Engineering Spring 2018``
## Problem Statement

## Bot Description

## Steps for Running and Installing

## Basic Flow of the System
Before showing a typical communication with the bot, let us discuss some points about the application.
WolfPlanner is designed for students to help them in planning their activities by generating a weekly schedule. Thus, the intended user of the system is student.
1. Student starts conversation with the bot: ``Hi``
2. The bot responds to the user asking for the unity id: ``Hi. Please enter your unity ID.``
3. The student enters the unity ID.
4. The bot then checks the database for a corresponding entry to the student ID.
5. If it exists, then the bot asks the student to enter the list of tasks he/she has to perform for the following week: ``Please enter the tasks which you want to be scheduled.``
6. If not, then the bot asks the user to enter details to create a new profile in the system and then asks for the set of tasks to be scheduled.
7. Upon receiving the tasks, the bot will generate a time-table for the student and simultaneously adds the tasks with corresponding timing on Google Calendar of the student's university account.
8. The bot now sends the user an image of the schedule which it generated.
## Use Cases
