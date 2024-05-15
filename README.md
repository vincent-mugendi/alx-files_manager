# alx-files_manager

# Project Summary: Back-End Trimester

This project is a summary of the back-end trimester, covering topics such as authentication, NodeJS, MongoDB, Redis, pagination, and background processing.

## Objective
The objective is to build a simple platform for uploading and viewing files, with features including:

- User authentication via a token
- Listing all files
- Uploading a new file
- Changing permission of a file
- Viewing a file
- Generating thumbnails for images

## Implementation
You will be guided step-by-step for building the project, with some freedom in implementation details (e.g., splitting into more files). The 'utils' folder is recommended for organizing your code.

## Learning Objectives
By the end of this project, you should be able to explain:

- How to create an API with Express
- How to authenticate a user
- How to store data in MongoDB
- How to store temporary data in Redis
- How to set up and use a background worker

## Requirements
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All files should end with a new line
- A README.md file at the root of the folder is mandatory
- Your code should use the `.js` extension
- Your code will be verified against lint using ESLint

## Provided Files
- package.json
- .eslintrc.js
- babel.config.js

Don't forget to run `$ npm install` when you have the `package.json`.

## Resources
Read or watch the following resources:
- [Node JS getting started](https://nodejs.dev/)
- [Process API doc](https://nodejs.org/api/process.html)
- [Express getting started](https://expressjs.com/en/starter/installing.html)
- [Mocha documentation](https://mochajs.org/)
- [Nodemon documentation](https://nodemon.io/)
- [MongoDB](https://www.mongodb.com/)
- [Bull](https://optimalbits.github.io/bull/)
- [Image thumbnail](https://www.npmjs.com/package/image-thumbnail)
- [Mime-Types](https://www.npmjs.com/package/mime-types)
- [Redis](https://redis.io/)

## Tasks
1. **Redis Utils**: Implement a Redis utility class.
2. **MongoDB Utils**: Implement a MongoDB utility class.
3. **First API**: Create the Express server and define two endpoints.
4. **Create a New User**: Implement endpoint for creating a new user.
5. **Authenticate a User**: Implement endpoints for user authentication.
6. **First File**: Implement endpoint for uploading files.
7. **Get and List File**: Implement endpoints for retrieving and listing files.

For detailed instructions and examples, refer to the provided files and the project's GitHub repository.

Enjoy building your project!
