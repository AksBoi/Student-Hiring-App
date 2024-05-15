# Recruitment Portal

## Overview

This project is a web-based recruitment portal built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It aims to streamline the recruitment process by providing a platform where recruiters can post job openings and manage applicants, and applicants can apply for jobs and track their application status.

## Features

- **User Authentication**: Secure user authentication system with JWT (JSON Web Tokens) for login/signup functionality.
- **Job Postings**: Recruiters can create, edit, and delete job postings with details such as job title, description, requirements, and application deadline.
- **Application Management**: Applicants can view job postings, apply for jobs, and track the status of their applications.
- **Admin Panel**: Admins have access to a dashboard where they can manage users, job postings, and applications.

## Project Structure


- **client**: Frontend codebase
  - **public**: Static assets
  - **src**: Source files
    - **components**: React components
      - **Auth**: Authentication components
      - **Job**: Job related components
      - *Other reusable components*
    - **pages**: Application pages
      - **Admin**: Admin dashboard pages
      - **Applicant**: Applicant dashboard pages
      - **Recruiter**: Recruiter dashboard pages
      - *Other pages*
    - **App.js**: Main React component
    - **index.js**: Entry point for React app
    - *Other configuration files*
- **server**: Backend codebase
  - **config**: Configuration files
    - **db.js**: Database configuration
    - *Other configuration files*
  - **controllers**: Request handlers
    - **authController.js**: Authentication controllers
    - **jobController.js**: Job related controllers
    - *Other controller files*
  - **models**: Database models
    - **User.js**: User model
    - **Job.js**: Job model
    - *Other model files*
  - **routes**: API routes
    - **authRoutes.js**: Authentication routes
    - **jobRoutes.js**: Job related routes
    - *Other route files*
  - **middleware**: Custom middleware functions
    - **authMiddleware.js**: Authentication middleware
    - *Other middleware files*
  - *Other backend-related files*
- **.gitignore**: Files and folders to be ignored by Git
- **package.json**: List of dependencies and scripts
- **README.md**: Guide for setting up and running the project


## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/recruitment-portal.git
    ```

2. **Install dependencies**:

    - For the client:

    ```bash
    cd client
    npm install
    ```

    - For the server:

    ```bash
    cd server
    npm install
    ```

## Usage

1. **Start the server**:

    ```bash
    cd server
    npm start
    ```

2. **Start the client**:

    ```bash
    cd client
    npm start
    ```

3. **Access the application**:

    Open your web browser and navigate to `http://localhost:3000`.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

