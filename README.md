# Lak App Backend

The backend server for Lak App is built using **Node.js** and **Express.js**. It provides the API and WebSocket functionalities required for a real-time chat application. The backend manages user authentication, real-time messaging, database interactions, and media uploads.

---

## **Features**
- **Authentication**: Secure user authentication using JWT and bcrypt.
- **Database**: MongoDB with Mongoose for robust and scalable data management.
- **Real-Time Communication**: Implemented using Socket.IO for chat functionality.
- **File Uploads**: Supports image uploads via Multer and Cloudinary.
- **Validation**: API request validation using Express Validator.
- **Environment Variables**: Configured with dotenv for managing sensitive credentials.

---

## **Getting Started**

### **Prerequisites**
- **Node.js**: Ensure Node.js (>= 14.0.0) is installed on your system.
- **MongoDB**: MongoDB server or cloud database (e.g., MongoDB Atlas) must be set up.

### **Installation**
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd server
