# JWT Authentication

## Overview
This project demonstrates how to implement JWT (JSON Web Token) authentication in a web application. JWT is a compact, URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is used as the payload of a JSON Web Signature (JWS) structure or as the plaintext of a JSON Web Encryption (JWE) structure.

## Features
- User registration and login
- JWT generation and validation
- Protected routes that require authentication
- Token refresh mechanism

## Technologies Used
- Node.js
- Express.js
- JSON Web Token (JWT)
- Sequelize and postgres

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/JWTAuthentication.git
    ```
2. Navigate to the project directory:
    ```sh
    cd JWTAuthentication
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```
    cd server and npm run build
    ```
4. Run the app:
    ```sh
    npm run start

## Configuration
1. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    PORT=3000
    DB_NAME=your_database_name
    DB_USER=your_postgres_username
    DB_Password=your_postgres_password
    JWT_SECRET=your_jwt_secret_key
    ```

## Usage
1. Start the server:
    ```sh
    npm start
    ```
2. The server will be running on `http://localhost:3000`.

## API Endpoints
- `POST /register` - Register a new user
- `POST /login` - Authenticate a user and return a JWT
- `GET /protected` - Access a protected route (requires JWT)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Contact
For any questions or inquiries, please contact [your email].
