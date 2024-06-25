# Luis's Social Network Web Application API (Module 18 NoSQL)

## This Challenge contains Luis's Social Network Web Application API to include the following functions:

- Allows my social network web application to use the MongoDB database so that my Social network website can handle large amounts of unstructured data.

## Installation

- npm init -y
- npm install express mongoose
- npm install --save-dev nodemon

## Usage

1. Start server:

- Open a new Git Bash terminal
- Go to Social-Network-API directly
- Once in Social-Network-API directly type 'code .'
- Once VS Code pulls up open the Git Bash terminal within VS Code and type 'npm start'(At this point, the server is running and you should get the message that states "API server running on port 3001!")

2. Testing in the Insomnia environment:

- To demonstrate GET routes for all users run the following in the Insomnia testing environment - http://localhost:3001/api/users
- To demonstrate GET routes for all thoughts run the following in the Insomnia testing environment - http://localhost:3001/api/thoughts
- To demonstrate GET routes for a single user run the following in the Insomnia testing environment - http://localhost:3001/api/users/:userId
- To demonstrate GET routes for a single thought run the following in the Insomnia testing environment- http://localhost:3001/api/thoughts/:thoughtId
- To demonstrate POST, PUT, and DELETE routes for users run the following in the Insomnia testing environment-
  - POST - http://localhost:3001/api/users - JSON Body: { "username": "newuser", "email": "newuser@example.com"}
  - PUT - http://localhost:3001/api/users/:userId - JSON Body: { "username": "newuser", "email": "newuser@example.com"}
  - DELETE - http://localhost:3001/api/users/:userId
- To demonstrate POST, PUT, and DELETE routes for thoughts run the following in the Insomnia testing environment -
  - POST - http://localhost:3001/api/thoughts - JSON Body: {"thoughtText": "This is a new thought", "username": "new user", "userId": "60d5f9b5c8a2b450c47d95a7"}
  - PUT - http://localhost:3001/api/thoughts/:thoughtId - JSON Body: { "thoughtText": "This is an updated thought"}
  - DELETE - http://localhost:3001/api/thoughts/:thoughtId
- To demonstrate POST and DELETE routes for a user’s friend run the following in the Insomnia testing environment -
  - POST - http://localhost:3001/api/users/:userId/friends/:friendId
  - DELETE - http://localhost:3001/api/users/:userId/friends/:friendId
- To demonstrate POST and DELETE routes for reactions to thoughts run the following in the Insomnia testing environment -
  - POST - http://localhost:3001/api/thoughts/:thoughtId/reactions - JSON Body: { "reactionBody": "This is a reaction", "username": "new user"}
  - DELETE - http://localhost:3001/api/thoughts/:thoughtId/reactions/:reactionId

## Demonstration Video and GitHub Repository Links

- To access video demonstration of Social Network Web Application API: [Social Network Web Application API video demonstration](https://drive.google.com/file/d/1R_6VTB58ENLyPAKMb2iXLctQrCAp1gcK/view?usp=sharing)
- To access the Social Network Web Application API repository: [Social Network Web Application API repository](https://github.com/ricanlonghorn23/Social-Network-API.git)

## Credits

Luis Aldaz
