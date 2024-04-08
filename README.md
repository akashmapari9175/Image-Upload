# Frontend

This is the frontend part of the project. It's responsible for uploading, fetching, and displaying images from the backend.

## Technologies Used

- React
- Axios

## Getting Started

To run the frontend locally, follow these steps:

1. Clone this repository.
2. Navigate to the frontend directory: `cd frontend`.
3. Install dependencies: `npm install`.
4. Start the development server: `npm start`.
5. Open http://localhost:3000 in your web browser to view the app.

## Features

- Upload images.
- Fetch all images from the backend.
- Display images with their names.
- Delete images from the backend.

## Folder Structure
- frontend/
- ├── src/
- │ ├── components/
- │ │ ├── ImageUpload.jsx
- │ │ └── ...
- │ ├── App.js
- │ ├── index.js
- │ └── ...
- └── public/
- ├── index.html
- └── ...

  
## Additional Notes

- Make sure the backend server is running and accessible from the frontend.

# Backend

This is the backend part of the project. It's responsible for handling image uploads, fetching images from MongoDB, and deleting images.

## Technologies Used

- Spring Boot
- MongoDB

## Getting Started

To run the backend locally, follow these steps:

1. Clone this repository.
2. Navigate to the backend directory: `cd backend`.
3. Configure MongoDB connection in `application.properties`.
4. Run the Spring Boot application.

## Endpoints

- `POST /upload`: Upload an image.
- `GET /images`: Fetch all images.
- `DELETE /images/{id}`: Delete an image by ID.

## Folder Structure

- backend/
- ├── src/
- │ ├── main/
- │ │ ├── java/
- │ │ │ ├── com.example/
- │ │ │ │ ├── controller/
- │ │ │ │ │ └── ImageController.java
- │ │ │ │ ├── model/
- │ │ │ │ │ └── Image.java
- │ │ │ │ └── repository/
- │ │ │ │ └── ImageRepository.java
- │ │ │ └── BackendApplication.java
- │ │ └── resources/
- │ │ └── application.properties
- │ └── test/
- └── pom.xml

  
## Additional Notes

- Make sure MongoDB is installed and running locally.
- The backend server runs on http://localhost:8080 by default.



