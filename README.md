# chat-application💬
 chat application built using Node.js, Express, Socket.io, and MongoDB. This project is designed to provide a real-time chat experience with user authentication and various chat features.

## Features😎

- Real-time messaging
- User authentication (sign-up, login)
- Email domain restriction for college students
- IP whitelisting and VPN support
- Role-based access control

## Installation🤹

1. **Clone the repository:**

    ```bash
    git clone https://github.com/SarayuGangula/chat-application.git
    cd chat-app
    ```

2. **Install dependencies:**

    ```bash
    npm install
    npm install --prefix frontend
    ```

## Configuration🕷️

1. **Environment Variables:**

    Create a `.env` file in the root directory and add the following environment variables:

    ```bash
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

2. **Email Domain Restriction:**

    Modify the user authentication logic to restrict email domains to your college domain. Update the relevant code in the `src` directory inside the `app` folder.

3. **IP Whitelisting:**

    Implement middleware in your backend server to check incoming request IP addresses. This can be done by modifying the `server.js` file or creating a new middleware file in the `src` directory.

4. **Geofencing:**

    Add geolocation checks in the frontend to ensure users are within the college campus when accessing the app.

5. **Role-Based Access Control:**

    Define user roles and permissions in the backend. Ensure that only authorized users can access certain features.

## Usage🧂

1. **Start the server:**

    ```bash
    npm run server
    ```

2. **Build the frontend:**

    ```bash
    npm run build
    ```

3. **Start the application:**

    ```bash
    npm start
    ```

4. **Access the application:**

    Open your browser and go to `http://localhost:3000`.
