# Threads Clone

Welcome to the Threads Clone repository! This project is a social media web application inspired by Threads, allowing users to share posts, interact with others, and explore content in a dynamic and user-friendly interface.

## Live Demo
Check out the live version of the app here: [Flicksy](https://flicksy.onrender.com/)
## images -- if website is down
![Screenshot 2024-12-14 141624](https://github.com/user-attachments/assets/9a58a175-9ec9-4141-8adf-869e5c4fd9eb)


![Screenshot 2024-12-14 141638](https://github.com/user-attachments/assets/c8c4e944-cd3e-486a-90ce-f99fa20e3b99)


![Screenshot 2024-12-14 141710](https://github.com/user-attachments/assets/d4e1a7fb-f88b-4007-8fac-5e56f747049b)


![Screenshot 2024-12-14 141725](https://github.com/user-attachments/assets/2d3ae53f-19e7-4845-b501-edfd36f7440f)


![Screenshot 2024-12-14 141739](https://github.com/user-attachments/assets/30c1fb35-88fe-4ad1-84c5-6f31ef5449ff)


![Screenshot 2024-12-14 141754](https://github.com/user-attachments/assets/85b729ec-681f-46a3-bda1-3c08e310a761)



## Features
- **User Authentication**: Sign up, log in, and log out securely.
- **Post Creation**: Share your thoughts through text-based posts.
- **Feed**: View posts from other users in a scrollable feed.
- **Like and Comment**: Interact with posts through likes and comments.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **real time chat** : implemented real time communicatin with socket.io.
- **follow and unfollow**: you can follow and unfollow a user.
- **dark light mode** : implemented dark and light mode

## Tech Stack
This project is built using the following technologies:

- **Frontend**: React.js, CSS (for styling)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: Render
- **Authentication and Authorization** : jsonwebtoken
- **cloudinary**:for image upload

## Installation and Setup
Follow these steps to run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/threads-clone.git
   cd threads-clone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   cd frontend
   npm install
   cd ../
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     MONGO_URI=<Your MongoDB connection string>
     JWT_SECRET=<Your secret key for authentication>
     PORT = <your port number>
     CLOUDINARY_CLOUD_NAME = <your cloudinary cloud name>
     CLOUDINARY_API_KEY =<your cloudinary api key>
     CLOUDINARY_API_SECRET = <your cloudinary secrets>
     
     ```

4. **Run the app**:
   - Start the backend:
     ```bash
     cd backend
     npm run dev/ npm start
     ```
   - Start the frontend:
     ```bash
     cd frontend
     npm start/ npm run dev
     ```

5. **Access the app**:
   Open your browser and go to `http://localhost:5000`.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Feedback
If you have any feedback, please feel free to reach out or open an issue on GitHub.

---

Enjoy using the Threads Clone! 🎉
