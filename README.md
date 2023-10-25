# API-Authentication

The purpose of this Web Application is demonstrate the use of API Authentication. The third party API is provided by Angela Yu's Udemy course - https://secrets-api.appbrewery.com -.

This API provided by Angela has documentation providing details on how to access her resources. In this section of her course we learn 4 parts of API Authentication - 1) No Authentication 2) Basic Authentication 

3) API Key Authorization 4) Token-Based Authentication. When you have the Web Application running  you will see 4 buttons each representing the level of Authentication to access the API information when you click on the

individual buttons.


Run this project using npm.

1) To run this project you will need to clone this repo using SSH or HTTP
2) Open the folder in VS Code or applicable source-code editor with access to terminal
3) When in the terminal, use npm install to install node dependencies - "npm install."
4) Once the dependencies are installed, you can go back into the terminal and use nodemon index.js to have your API running on port 3000. - "nodemon index.js"
5) You can now go to your browser and enter "http://localhost:3000/" to view the application

***NOTE Before running the application , you will need to update the below values with your unique information - found on index.js
// TODO: Replace the values below with your own before running this file. Remember to create your .env file to hide your unqiue credentials.

const yourUsername = "";
const yourPassword = "";
const yourAPIKey = "";
const yourBearerToken = "";

In order to udpate your values you will need to follow the documentation on - https://secrets-api.appbrewery.com - and use postman to register your user & get the token.
Follow the details below from the documentation
POST /register
GET /generate-api-key
POST /get-auth-token

