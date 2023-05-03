# Social-Network-API

 ## Table of Contents:  
[1. Description](#Description)  
[2. Acceptance Criteria](#Acceptance-Criteria)  
[3. Walkthrough Videos](#Walkthrough-Videos)  
[4. Installation](#Installation)  
[5. Tests](#Tests)  
[6. License Details](#License-Details)    
[7. Contact/Questions](#Contact/Questions)   
 

## Description:
This is a set of API for a social network that uses a MongoDB database so that the website can handle large amounts of unstructured data, Express.js for routing, Mongoose ODM, and the moment package to format time stamps.

## Acceptance Criteria:

GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Walkthrough Videos

[User Routes](https://user-images.githubusercontent.com/119627874/236024554-c0f6070b-cb8f-4fb1-a4a9-0f79e5648ac2.webm)
[Friend Routes]()  
[Thought Routes]()  
[Reaction Routes]()  

## Installation:

This repo is not to be deployed, if you wanted to, you could by doing the following:  
1. Download the repo files from the link below
2. You must have mongoDB installed
3. Run the following at the command line
```
    - npm init
    - npm i express
    - npm i mongoose
```
4. Start the server
```
    $ npm start
```
5. Open Insomnia Core to test API routes

## Tests:  

Testing restful API calls with Insomnia 

## License

This project is licensed under the MIT license. Click [here](https://opensource.org/licenses/MIT) for more information.<br>
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Contact/Questions

[GitHub Profile](https://github.com/Christinaecb)

Email -- christina.e.c.barberi@gmail.com



