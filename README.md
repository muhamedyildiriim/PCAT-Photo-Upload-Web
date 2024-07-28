# PCAT Photo Sharing Application

## Description
The **Photo Sharing Application** is designed to allow users to view and interact with photos uploaded by others, similar to Pexels. Users can also upload their own photos and engage with the community. This project is developed using Node.js for the backend, with popular libraries such as Express for the server and Mongoose for MongoDB connections. Functional features include user login/logout, photo upload, and photo deletion.

## Features
- **User Authentication**: Users can sign up, log in, and log out.
- **Photo Upload**: Users can upload their own photos to the platform.
- **Photo Deletion**: Users can delete photos they have uploaded.
- **Photo Viewing**: Users can browse and view photos uploaded by others.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/photo-sharing-app.git
    cd photo-sharing-app
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Setup Environment Variables**:
    Create a `.env` file in the root directory and add your MongoDB URI:
    ```
    MONGODB_URI=your_mongodb_uri
    ```

4. **Start the Server**:
    ```bash
    npm start
    ```

## Usage
- **User Authentication**: Navigate to the sign-up or login page to create an account or log in.
- **Photo Upload**: Use the upload feature to add new photos to the platform.
- **Photo Deletion**: Delete photos you have uploaded through the user interface.
- **Photo Viewing**: Browse the gallery to view photos uploaded by other users.

## Configuration
1. **MongoDB**: Ensure you have a MongoDB database set up and update the `MONGODB_URI` in the `.env` file.

## How It Works
1. **Backend**: The backend is developed using Node.js, Express for handling server requests, and Mongoose for database operations.
2. **Frontend**: The frontend interacts with the backend APIs for user authentication, photo upload, and deletion.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or support, please contact [your email].
