Tech Stack
Frontend
React (Hooks + Context API)
React Router
Axios
Backend
ASP.NET Core Web API (C#)
Entity Framework Core
Database
SQLite (with EF Core Migrations)
✨ Features
📊 Dashboard
Total number of projects
Task count by status (Todo, In Progress, Review, Done)
Overdue tasks highlighted
Tasks due within next 7 days
📁 Projects
Create, update, delete projects
Unique project name validation
View project with task summary
📌 Tasks
Create, update, delete tasks
Assign priority (Low, Medium, High, Critical)
Track status (Todo, In Progress, Review, Done)
Due date validation
Filtering (status, priority)
Sorting (due date, priority, created date)
Pagination support
💬 Comments
Add comments to tasks
Delete comments
View all comments per task
🏗️ Project Structure
Backend (/backend)
Controllers/
Services/
Models/
DTOs/
Data/
Middleware/
Migrations/
Frontend (/frontend)
components/
pages/
hooks/
context/
services/
⚙️ Setup Instructions
🔧 Backend Setup
cd backend
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run

Backend runs at:

http://localhost:5000
💻 Frontend Setup
cd frontend
npm install
npm start

Frontend runs at:

http://localhost:3000
🔗 API Base URL

Configured in frontend:

http://localhost:5000/api
🧪 Sample API Endpoints
Projects
GET /api/projects
POST /api/projects
Tasks
GET /api/projects/{projectId}/tasks
POST /api/projects/{projectId}/tasks
Comments
GET /api/tasks/{taskId}/comments
POST /api/tasks/{taskId}/comments
Dashboard
GET /api/dashboard
