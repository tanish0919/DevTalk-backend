# DevTalk Backend

DevTalk Backend is the backend server for the DevTalk application, which allows developers to post new projects, achievements, and problems. It also provides features to view other users' profiles, including their education, work experience, and links to their social websites.

## Technologies Used

- Node.js
- Express.js
- JSON Web Tokens (JWT) for authentication
- Express Validator for request validation

## Features

1. **User Authentication**: Secure user authentication using JWT tokens.
2. **Post Management**: Allows users to create, update, delete posts about their projects, achievements, and problems.
3. **Profile Management**: Provides features to view and update user profiles, including education, work experience, and social website links.
4. **Request Validation**: Implements request validation using Express Validator to ensure data integrity and security.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Install dependencies:

   ```bash
    npm install

3. Create a .env file in the root directory and add the following environment variables:

   ```bash
    PORT=3000
    JWT_SECRET=your_jwt_secret_key

4. Start the server:

   ```bash
    npm start

# License
 This project is licensed under the MIT License.
