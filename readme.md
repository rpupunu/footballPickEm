# Project Title: NFL Pick 'Em

## Google Slides Presentation
https://docs.google.com/presentation/d/1SvWemIAWIRDnifAGaSY_YCe023D0SMpBczxvTwKJmCk/edit?usp=sharing

## Try The App Out Here:
https://nflpickem123.herokuapp.com/


## Team Members:
RJ Pupunu, Colin Reesor, Xander Canedo, Brennen Bates

## Technology Used:
HTML, CSS, Bootstrap, Javascript, Jquery, Handlebars, MySQL, Sequelized, Heroku, JawsDB, MVC, Axios

## New Javascript Libraries: 
1. JSON Web Token (jwt) - used for user authentication
2. BCRYPT - used to encrypt passwords when saving user data

## APIs used:
NFL Game Data:
1. https://feeds.nfl.com/feeds-rs/scores.json
2. http://www.nfl.com/liveupdate/game-center/2018102107/2018102107_gtd.json

## Project description:
This app allows you to create pick em forms for NFL games so that you can bet on the games with your friends.  Typically these forms are printed out and passed around at parties or gatherings, people buy a certain number of squares and put their name on the sheet.  

This app has user authentication allowing a new user to sign up.   They then can click on View This Weeks Games to see all of the NFL matchups for the week.  This data is pulled from the NFL apis listed above.   They can then click on a game which saves it in their user games.  Then they can click View Your Games and then select into that game.  After that the form shows up.  They can then input names into each of the cells and click a button to save this data for future use.

## Project presentation slides:

Google Slides: https://docs.google.com/presentation/d/1SvWemIAWIRDnifAGaSY_YCe023D0SMpBczxvTwKJmCk/edit?usp=sharing

.PNG imagess of slides: files for each slide can also be found in /public/images/NFL Pick 'Em_presentation_1-10

## Project Improvements/Icebox Items/Features to be added in the future
1. Matchmaking - currently setup as one admin makes all the squares.  Have it so you invite friends on the app and they choose their squares.

2.  Game Winner Tracking - add UI for the admin to track money on each square, determine the winners of each quarter/half/game, and an auto-txt functionality that text each user/winner with the amount they won.

3.  Multi-User Environment - Add the ability for users to login and not only be able to be part of other peoples games but also be the admin of games and create/invite others to games.

4.  $$$ method - have a way to purchase squares into someones game and make it legit betting.  Evaluate what laws we are breaking if we do that.

5.  UI - Implement the clean UI options we had in mind with login screen and viewing games
