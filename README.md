## Street Dog Services Portal

Street Dog Services Portal is a MERN stack-based project that I built to solve a real-world social issue related to street dog rescue and welfare.
The main idea was to create a centralized platform where users can report injured or sick street dogs, find nearby rescuers, feeders, NGOs, or adoption-related services, and filter those services based on location. 
 
## Goal of the Project
To demonstrate the ability to:

- Build a complete full-stack web application using the MERN stack
- Create a real-world social impact project with practical use cases
- Design and implement RESTful APIs for service management
- Store and manage structured service data using MongoDB
- Implement CRUD operations for adding, viewing, and managing services
- Build a user-friendly and responsive frontend using React
- Implement location-based filtering for better service discovery
- Connect frontend and backend efficiently in a production-style workflow
- Solve a real-world coordination problem using technology

## Features

- Add and manage street dog-related services
- Browse available services such as rescue, feeding, adoption, and support
- Filter services based on location
- Search for relevant dog welfare services in specific areas
- User-friendly interface for easy navigation
- Centralized platform for organized service discovery
- Structured backend API integration
- Stores service details in MongoDB database
- Scalable architecture for future enhancements
- Designed for real-world community and animal welfare support

## Problem Statement

Street dog rescue and welfare support is often managed through unorganized channels such as social media groups, personal contacts, or scattered local networks. This makes it difficult for users to quickly find the right rescuers, feeders, NGOs, or support services in urgent situations.
The Street Dog Services Portal solves this problem by providing a centralized, searchable, and location-aware platform where users can discover and access relevant street dog-related services more efficiently.


## Technologies Used

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Additional Concepts / Implementation
- REST APIs
- CRUD Operations
- Location-Based Filtering
- JSON-based Static Location Data (for cost-effective filtering)
- Full-Stack Client-Server Architecture



## Why This Project Matters
This project was built to solve a real-world problem where street dog rescue and welfare support is often handled in an unorganized way through social media, local contacts, or informal communication channels.
The **Street Dog Services Portal** provides a structured and centralized solution where users can easily find relevant help, report cases, and discover services available in their area. It combines technology with social impact, making it both technically strong and meaningful as a portfolio project.

## How to Run

### 1 - Clone the repository
git clone https://github.com/your-username/Street-Dog-Services-Portal.git

## 2 - Navigate to the project folder
cd Street-Dog-Services-Portal

## 3 - Install backend dependencies
cd server
npm install

## 4 - Install frontend dependencies
cd ../client
npm install

## 5 - Create environment variables
Create a .env file inside the server folder and add:
MONGO_URI=your_mongodb_connection_string
PORT=5000

## 6 - Run the backend server
cd server
npm start

## 7 - Run the frontend
cd client
npm start

## Folder Structure
Street-Dog-Services-Portal/

├── client/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── README.md
└── package.json


## How It Works
- User Visits the Portal → Accesses the web application through the frontend.
- Browse Services → Views available street dog-related services.
- Filter by Location → Searches for services in a selected city or area.
- Service Data Fetching → Frontend requests data from backend APIs.
- Backend Processing → Express server handles the request logic.
- MongoDB Storage → Service details are stored and retrieved from the database.
- Display Results → Filtered or complete service data is shown on the frontend.

## Core Workflow
- Service Listing → Stores rescue, feeding, adoption, or support services.
- API Integration → React frontend communicates with Node/Express backend.
- Database Handling → MongoDB stores structured records.
- Filtering Logic → Location-based filtering helps users discover relevant services.
- User Experience → Clean and simple UI for accessibility and ease of use.

## Use Cases
- Reporting injured or sick street dogs.
- Finding nearby feeders or rescuers.
- Discovering NGOs working in dog welfare.
- Managing street dog-related service listings.
- Supporting local adoption and rescue coordination.
- Helping users quickly connect with relevant services in urgent situations.
- Building a digital support system for community animal welfare.

## Future Enhancements
- User authentication (Login / Signup)
- Volunteer / NGO dashboards
- Admin panel for service verification
- Real-time rescue request updates
- Image upload for rescue cases
- Google Maps integration
- Status tracking for reported cases
- Notifications for nearby rescue requests
- Role-based access for users, volunteers, and admins
