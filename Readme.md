# HospEase

## Overview
**HospEase** is a comprehensive hospital management application designed to streamline operations related to patient queue management, bed availability tracking, and inventory control. The application leverages real-time data processing and a microservices architecture to provide an efficient and scalable platform for both hospital staff and patients.

## Features
- **Patient Queue Management**: Efficiently manage patient queues with priority levels for emergencies.
- **Real-Time Bed Availability**: Track bed availability in real-time, allowing patients and staff to make informed decisions quickly.
- **Inventory Management**: Manage hospital consumables and medicines, with features for manual updates by authorized staff.
- **User Authentication**: Secure access with role-based authentication for hospital staff and patients.
- **Scalable Architecture**: Designed with a microservices architecture, enabling independent scaling of different components.

## Technology Stack
- **Front-End**: 
  - React.js
  - HTML5, CSS3, JavaScript
  - Axios for API calls
- **Back-End**: 
  - Node.js with Express.js
  - JWT (JSON Web Token) for authentication
  - WebSockets (Socket.io) for real-time data communication
- **Database**: 
  - MongoDB for flexible, NoSQL data storage
  - Mongoose for ORM (Object-Relational Mapping)

## Installation
### Prerequisites
- Node.js (v14+)
- MongoDB
- Git

### Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/HospEase.git
   cd HospEase
2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables**

    Create a `.env` file in the root directory and add the following:

    ```makefile
    NODE_ENV=development
    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application:**

    ```bash
    npm run dev
    ```

5. **Access the Application:**

    Open your browser and navigate to [http://localhost:5000](http://localhost:5000)

## Usage

### For Hospital Staff
- Log in with your credentials to manage patient queues, bed availability, and inventory.

### For Patients
- Access the platform to check bed availability and your position in the queue.

## Contact

For any inquiries or support, please contact [ok.anuj30@gmail.com](mailto:ok.anuj30@gmail.com).
