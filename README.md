# React Js and React Native Challenge

  Hey, thanks for your interest in working with us. Before we continue your application we need to check if you can handle things here in Pingback.
  We know that's boring and it sucks, but it allow us to create a team that really can collaborate. 
  
  So if you are here, we need to check some skills ok? Let's do It!
  
# What are we looking for?
  
  First, we need you to know that you have a domain of Javascript and ReactJs/React Native. It's important to remember that our entire culture is based on Clean Code, so, be aware that we will expect that your code is well written and well documented, ok?
  
  ### ReactJs
   If you are applying for a Reactjs role, we expect you to use SASS for styling your app.
   
  ### React Native
   If you are applying for a React Native role, we expect you to use Styled Component for styling your app. 

 ### Storage

 It's required to use Redux, using hooks, and using Thunk as an async middleware.

 ### Tests
 
 You must implement some tests in your application. Those tests should run when the command `npm test` is prompted.
 We recommend you to use jest and maybe cypress. (But be free to use whatever you like).

# Your Goal
 
  Your goal here is to create a simple application that will be a Trivia Game. 
  
 Your game must receive from an external API 10 questions of true/false, present those questions from users, hold users' answers and then show the result of the end game.
 
  We want to see how you structure your code and the solutions you use to each challenge you will face.

# Api

You must use https://opentdb.com/ as API for getting the Trivia Questions. Be aware that the documentation for using this API is in the provided link and that you need to receive 10 questions for each request these questions should only be true/false and have a pre-setted difficulty.

# Screens

Your application must have at least 3 basic screens:

1) Start Game Screen

|---------------------------------|
|                                 |
|             Welcome             |
|                                 |
|                                 |
|                                 |
|     This is ____ Trivia Game    |
|                                 |
|                                 |
|                                 |
|                                 |
|                                 |
|  You will receive 10 questions  |
|    can you answer all right?    |
|                                 |
|                                 |
|             START               |
|---------------------------------|

 - This screen must have an intro screen that user will understand the game and will start it.

2) Questions Screen

|---------------------------------|
|       Question X of 10          |
|                                 |
|                                 |
|        Question Category        |
|                                 |
|                                 |
|   Lorem ipsum dolor sit amet,   |
|  consectetur adipiscing elit.   |  
|  Sed libero enim, commodo nec   |
|  iaculis et, aliquet ut lectus. |
|                                 |
|                                 |
|                                 |
|                                 |
|          True. False.           |
|                                 |
|                                 |
|                                 |
|             01:22               |
|---------------------------------|

 - This screen will present each one of the 10 questions.
 - It must have the index of each question
 - It must have the category of each question
 - It must have two buttons that user will input the answer.
 - It must have a timmer that will show how much time user have used since the begging of the first question.
 - When the answer is inputed by the user, the application must show if its right or not and go to the next question.


3) Result Screen

|---------------------------------|
|                                 |
|             Result              |
|   1) True                       |
|   2) False                      |
|   3) True                       |
|   4) True                       |
|   5) False                      |
|   6) False                      |
|   7) False                      |
|   8) True                       |
|   9) False                      |
|   10) True                      |
|                                 |
|         You Scored 3/10         |
|                                 |
|            Play Again           |
|---------------------------------|

- This screen will present the result of the trivia game
- It must have all questions listed and if the user choosed the correct or incorrect answer (use colors red and green for that)
- It must have the score
- It must have a button that will lead the user to the first welcome screen
- It must have the total time played in minutes.
                                       
