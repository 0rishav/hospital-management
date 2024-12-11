# Hospital Management System 🏥

## About the Project  
The Hospital Management System is a comprehensive application designed to streamline hospital operations.  
- Enables efficient management of Doctor and Nurse records.  
- Tracks and displays detailed records of Indoor Patients and Outdoor Patients.
- Provides an easy-to-navigate interface for accessing critical information.

## Time Duration  
**Development Period:**  
```plaintext
1st December 2024 – 10th December 2024
```

# How to Run the Project
This project has two main parts:

**Frontend** - Handles the user interface.
**api** - Manages the server-side logic and APIs.

### 1. Clone the Repository  
Run the following command to clone the repository:  
```bash
https://github.com/0rishav/hospital-management.git
cd hospital-management
```

### 2. Set Up the Environment Variables  
 **backend** require environment variables.

#### Backend Environment Variables  
Create a `.env` file in the `backend/` folder and add the following variables:

```env
PORT=8000
MONGO_URL=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret-key
```

### 3. Install Dependencies  
To install the necessary dependencies for both the **frontend** and **api**, follow these steps:

#### For api  
Navigate to the `backend/` directory and install the dependencies:

```bash
cd api
npm install
```

#### For Frontend
Navigate to the `frontend/` directory and install the dependencies:

```bash
cd frontend
npm install
```

### Start the Frontend Development Server  
Navigate to the `frontend/` folder and run the following command to start the frontend development server:

```bash
npm run dev
```

### Start the Backend Development Server  
Navigate to the `frontend/` folder and run the following command to start the frontend development server:

```bash
Nodemon index.js
```

### Technologies Used  

#### Frontend:  
- **React**  
- **Axios** for HTTP requests  
- **React Router** for navigation  

#### Backend:  
- **Node.js** with **Express**  
- **MongoDB** for data storage  

#### Other Tools:   
- **CORS** for handling cross-origin requests  
- **Dotenv** for managing environment variables
- **Bcrypt.js** for password hashing
- **cookie-parser** for parsing cookies
- **jsonwebtoken** for authentication with JSON Web Tokens  
