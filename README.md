# RaceDay Event Management System - API (Part 2)

A robust RESTful Web API built with **ASP.NET Core** and **Entity Framework Core** for managing sports and racing events across South Africa. This project serves as the backend implementation for the RaceDay platform.

---

## 🚀 Features & Capabilities

- **User Authentication & Authorization**: Secure user registration and login with encrypted passwords using BCrypt.
- **Role-Based Access**: Role management distinguishing between Event Organisers and Event Participants.
- **Event & Category Management**: Dynamic event creation, category filtering, and status tracking.
- **Participant Enrolments**: Registration handling for participants entering specific races or events.
- **Race Results**: Recording and retrieving participant timing and position results.
- **Automated CI/CD**: GitHub Actions workflow for automated building and testing on every commit.

---

## 🛠️ Tech Stack

- **Framework**: .NET 8.0 / ASP.NET Core Web API
- **ORM**: Entity Framework Core
- **Database**: Microsoft SQL Server / LocalDB
- **Authentication**: BCrypt.Net-Next
- **Documentation**: Swagger / OpenAPI
- **CI/CD**: GitHub Actions
- **Testing**: xUnit

---

## 📁 Solution Structure

```text
RaceDay.API/
│
├── Controllers/         # API Endpoint Controllers (AuthController, EventsController, etc.)
├── Data/                # DbContext and Data Seeder configurations
├── Models/              # Database entities and Data Transfer Objects (DTOs)
├── Migrations/          # EF Core Database Migrations
├── appsettings.json     # Configuration settings & Connection Strings
└── Program.cs           # Application bootstrap and dependency injection
