# Trim-Tracker
Trim Tracker is a comprehensive salon management and booking platform designed to streamline the process for both salon owners and customers. It allows users to browse available salons, book appointments based on real-time availability, and manage their bookings effortlessly. Salon owners can manage customer queues, service offerings, and appointment schedules through an intuitive dashboard.

# Features
## For Customers:
Salon Browsing: Search and filter salons by availability and services offered.
Appointment Booking: Book appointments seamlessly based on real-time slot availability.
Appointment Tracking: Monitor your upcoming and past appointments.
User Authentication: Secure login and registration system using JWT (JSON Web Token) for authentication.
## For Salon Owners:
Dashboard: Manage your salon services, appointment slots, and customer queue.
Appointment Management: View, approve, or decline appointment requests in real-time.
Service Customization: Add, update, or remove services offered at the salon.
Customer Insights: Track customer history and popular services.
Tech Stack
Trim Tracker is built using modern web technologies for both the front-end and back-end:

## Frontend:
**ReactJS** (for building a responsive, interactive UI)
## Backend:
**NodeJS with ExpressJS** (for building a scalable and efficient REST API)
**MongoDB** (as the database for storing user and appointment data)
## Authentication:
**JWT** (for secure, stateless authentication)
Bcrypt.js (for hashing and securing passwords)
## API Testing:
**Postman** (for testing REST APIs and ensuring reliability)
Installation
Prerequisites:
Node.js (>=14.x)
MongoDB (local or cloud)

# User Dashboard

![Screenshot (370)](https://github.com/user-attachments/assets/21597c34-4cc0-4424-8a70-76b4f33e73c4)

![Screenshot (371)](https://github.com/user-attachments/assets/2f3f359a-7c70-4b32-9015-c99bc1644e2a)

![Screenshot (372)](https://github.com/user-attachments/assets/3d86280a-0419-4196-a703-52b5513979dd)


# Saloon Owner Dashboard

![Screenshot 2024-10-05 194840](https://github.com/user-attachments/assets/8202b609-dce5-4921-bc7c-57f790367da6)

![Screenshot 2024-10-05 194907](https://github.com/user-attachments/assets/888f509b-5bd9-4e4e-97e9-fafd2dc260e3)






# Setup:

Clone the repository:

bash
### Copy code
git clone https://github.com/Iampratik2003/Trim-Tracker.git
Navigate to the project directory:

bash
### Copy code
cd Trim-Tracker
Install dependencies for both the frontend and backend:

bash
### Copy code
npm install
Set up environment variables for JWT secret and MongoDB URI. Create a .env file in the root directory:

makefile
### Copy code
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Start the server:

bash
### Copy code
npm start
The application will be running at http://localhost:3000.

Usage
Customers: Sign up or log in to book appointments at your preferred salon.
Salon Owners: Manage your salon's profile, services, and appointments through the owner dashboard.
API Documentation
For detailed API endpoints and usage, you can refer to the Postman collection included in the repository.

Contributing
If you'd like to contribute to Trim Tracker, please fork the repository and use a feature branch. Pull requests are welcome.
