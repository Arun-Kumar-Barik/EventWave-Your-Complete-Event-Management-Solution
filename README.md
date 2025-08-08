# EventWave-Your-Complete-Event-Management-Solution

EventWave is a full-stack event management web application that simplifies the process of event creation, registration, and tracking for both organizers and attendees. It combines the power of **Spring Boot** for a robust backend and **React.js** for a dynamic and user-friendly frontend.

## 🚀 Features

### 👥 User Features
- Register and log in as a user
- Browse and view upcoming events
- Register for desired events
- View your registered events (`/my-registration` endpoint)

### 🧑‍💼 Organizer Features
- Register and log in as an event organizer
- Create, update, and delete events
- View attendees for their events

### 🛠️ Admin (Optional Future Enhancement)
- View all users, organizers, and events
- Delete any abusive content or user

## 📦 Tech Stack

| Layer         | Technology        |
|---------------|-------------------|
| Frontend      | React.js          |
| Backend       | Spring Boot       |
| Database      | MySQL             |
| API Tool      | Postman (for testing) |
| Build Tool    | Maven             |

## 📂 Project Structure

```bash
EventWave/
├── backend/
│   ├── src/
│   │   ├── main/java/com/eventwave
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   └── service/
│   │   └── main/resources/
│   │       └── application.properties
│   └── pom.xml
├── frontend/
│   └── (React files)
└── README.md

```

⚙️ Setup Instructions
Backend (Spring Boot)
Navigate to the backend folder.

Update application.properties with your local DB credentials.

Run: mvn spring-boot:run

Frontend (React)
Navigate to the frontend folder.

Install dependencies: npm install

Start the dev server: npm start

🛡 License
This project is licensed under the MIT License.

👨‍💻 Contributors
Sneghaa A : Java
Arun Kumar Barik : Java
Swasthi S Shetty : Java
Pratheeksha K N : React


