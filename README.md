# FriendFinder
Welcome to the _**FriendFinder**_ app! 
FriendFinder is a friend-matching application that utilizes the user's responses to questionaire. The user responds to questions that have values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, the application checks the existing hard-coded friends API in order to return the match who has the lowest absolute difference when compared to the user's score.  

This app is deployed to Heroku, check it out [here](https://friendfinder5.herokuapp.com/) 

To run FriendFinder locally and access it in your browser, first set the PORT environment variable to the value of your choice. 
After the PORT environment variable has been set, run the Node.js application with the command below.

node server.js

FriendFinder will now be running locally on PORT

**Happy matching!**

