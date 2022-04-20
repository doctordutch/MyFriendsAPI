<h1 align="center"> Social Networking API Backend </h1>

## Description

🔍 This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.
  

## User Story

```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
    
## Installation
💾   
  
`npm init`

`npm install`
  
## Usage
💻   
  
`npm start`

With Nodemon:

`npm run watch`

## Walkthrough

[here](https://drive.google.com/file/d/1VMm6LdFokBYiB23rfdglNhvm2ym9uy7L)

<p align="center">
    <img src="https://img.shields.io/badge/javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/MongoDB-blue"  />
    <img src="https://img.shields.io/badge/mongoose-red"  />
    <img src="https://img.shields.io/badge/moment-blue"  />
    <img src="https://img.shields.io/badge/nodemon-green" />
</p>
