# YAHTZEE_Project
YAHTZEE web application designed and created by a three person group. Made using JavaScript with React and MongoDB

• Demo:

http://yahtzee-front-end-only.s3-website.eu-west-2.amazonaws.com/

• Technologies Used:

JavaScript with React, MongoDB, HTML, CSS

• Project Brief:

• MVP 

User should be able to play a functional game of Yahtzee:

User should be able to roll dice, then select which dice to roll again, up to three times in total.

The user can then select a scoring category for this turn.

The current game is persisted both in state and in the database.

The program should automatically calculate the users score.

• Extensions

Add a second player. Have the option to add player's names, their team's colour...

Have up to 6 players, with a scorecard matching the rulebook of Yahtzee.

Have a statistics page with details of previous games, hi scores etc.

A whole other card game Pairs/Pelmanism.

• To run:

• Server

cd server
npm install (or npm upgrade)

npm run seeds (seeds database)

npm run server:dev (runs express)

Server available on http://localhost:9000/api/rolls

• Client

cd client

npm install (or npm upgrade)

npm start

Client available on http://localhost:3000/
