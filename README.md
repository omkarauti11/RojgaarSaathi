# RojgaarSaathi

# Job Portal

This project is a job portal web application that allows job seekers to view and apply for jobs, while recruiters can post, edit, and delete job listings. The application implements JWT-based user authentication and password encryption using bcrypt.

## Features

- **Job Seeker**: View available jobs, apply for jobs.
- **Recruiter**: Post jobs, edit job listings, delete job listings.
- **Authentication**: Secure user authentication using JWT.
- **Password Encryption**: Passwords are encrypted using bcrypt.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Express.js
- **Database**: MongoDB Atlas
- **Image Storage**: Cloudinary API


## Setup Instructions

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/omkarauti11/RojgaarSaathi.git
    cd RojgaarSaathi
    ```

2. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies:**
    ```bash
    cd frontend
    npm install
    ```

4. **Set up environment variables in backend:**
 
    - Create a `config/config.env` file in the `backend` directory and add the following:

    ```env
    PORT=4000

    CLOUDINARY_CLIENT_NAME=
    CLOUDINARY_CLIENT_API=
    CLOUDINARY_CLIENT_SECRET=
    
    FRONTEND_URL=http://localhost:5173
    
    MONGO_URI=mongodb+srv://username:password@cluster0.9t0akcl.mongodb.net
    
    JWT_SECRET_KEY=anykey
    JWT_EXPIRES=7d
    
    COOKIE_EXPIRE=5
    ```

6. **Run the backend server:**
    ```bash
    npm run dev
    ```

7. **Run the frontend:**
    ```bash
    npm run dev
    ```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.



