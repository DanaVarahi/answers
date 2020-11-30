#Questions
## 1. What is responsible for defining the routes of the games resource?

-GamesService.js

## 2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

-Client is resonsible for the api, user input, sending requests to the server.

-Server is responsible for managing the database and sending responses (data) from the api to the client

## 3. What are the the responsibilities of server.js?

-Server.js is responsible for connecting to the database, listening for requests and updating database in response using the api

## 4. What are the responsibilities of the gamesRouter?

-gamesRouter provides CRUD routes for updating the database. 

## 5. What process does the the client (front-end) use to communicate with the server?

-It uses fetch requests to process requests and responses.

## 6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

-init object that controls different settings

## 7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
  
-Create(post route), delete, index(get route)

## 8. What are we using the MongoDB Driver for?

-For interacting with MongoDB. 

