# Homework Assignment # 4
Homework assignment for week 4 - Timed Quiz Built in Jquery.

# Overview
This project involved building a timed quiz in jquery.  For this project, I chose to go with an automotive theme for the questions presented.  How much automotive trivia do you know?  Take the quiz and find out!

# Function
The user if first presented with an opening message and a start button.  Clicking the start button triggers the first function that initializes the elements of the game, like the first question and the timer.  With each question that is answered correctly, a point will be given.  However, for each question that is answered incorrectly, ten seconds will be taken off the timer.  There are a total of 5 questions in all, each being stored in an array located in a separate javascript file, labeled 'questions.js'.

When the user has answered all questions (or when time runs out), the user will be prompted for their initials.  At the same time, their score will be recorded.  The user will see their initials and high score, as well the number of questions answered correctly and incorrectly, displayed on the final results page.  On this page, the user will also see a "try again" button that will reset the game so it can be played through again.

The high score is recorded to local storage so that if the user scores lower on the second play-through, the previous high score will still display.