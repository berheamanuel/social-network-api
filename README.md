# Social Network API App

## Description

This is a RESTful API for a social network application. It allows users to create accounts, post thoughts, follow other users, add reactions on thoughts and perform various social networking actions.

## Features

- User registration and authentication
- Create, update, and delete user 
- Post thoughts and reactions
- Add reactions to thoughts
- Follow and unfollow other users
- Search for users and posts

## User Story

AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria

* GIVEN a social network API
* WHEN I enter the command to invoke the application
* THEN my server is started and the Mongoose models are synced to the MongoDB database
* WHEN I open API GET routes in Insomnia for users and thoughts
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
* THEN I am able to successfully create, update, and delete users and thoughts in my database
* WHEN I test API POST and DELETE routes in Insomnia
* THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Demonstration
* [Walkthrough Video](https://drive.google.com/file/d/1zwqzSBWgx1iJiEsdkX3x9em5xzwrMwoU/view)

## Screenshots
* ![All Users](./images/Screenshot%202024-02-05%20003311.png)
* ![All Thoughts](./images/Screenshot%202024-02-05%20003429.png)

## Technologies Used

- Node.js
- JavaScript
- Git Bash
- VS Code
- Express.js
- MongoDB (NoSQL database)
- Mongoose (ODM)
- Jest for testing
## Reference
* NoSQL class activity
* [MongoDB Docs](https://mongoosejs.com/docs/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/social-network-api.git

## License

* MIT License
