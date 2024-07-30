# Mcc-Backend-Nodejs

## Description

Backend for mcc project

Tech: Node.js, Express, and MongoDB. This project includes user authentication, data sanitization, and secure HTTP headers, among other features.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Dev Dependencies](#dev-dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd mcc-backend-nodejs
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a config.env file in the root directory and add your environment variables:
   ```sh
      DATABASE=mongodb+srv://<<Please replace your user name>>:<password>@cluster0.im6weeo.mongodb.net/mcc_game?retryWrites=true
      DATABASE_PASSWORD=<your-database-password>
      PORT=3000
      NODE_ENV=development
   ```
5. Usage,
   To start the server in development mode:
   ```sh
   npm run start:dev
   ```
   To start the server in staging mode:
   ```sh
   npm run start:stg
   ```
   To start the server in production mode:
   ```sh
   npm run start:prod
   ```
6. Scripts
   ```sh
   start:dev: Runs the server in development mode using nodemon.
   start:stg: Runs the server in staging mode using nodemon.
   start:prod: Runs the server in production mode using nodemon.
   watch:js: Uses Parcel to watch and bundle JavaScript files.
   build:js: Uses Parcel to bundle JavaScript files for production.
   ```
7. Contributing
   ```sh
   - Fork the repository.
   - Create your feature branch
   - git checkout -b feature/your-feature
   - git commit -m 'Add some feature'
   - Open a pull request.
   ```
