# C5 CycleHub
### A Web-Based Bicycle Shop and Parts Hub

C5 CycleHub is a web-based bicycle shop and parts hub designed to provide customers with a convenient platform for browsing bicycle products, managing wishlists, and placing orders. It also provides administrative features for managing products, inventory, orders, and customer interactions.

The system combines a responsive React frontend with a Node.js backend and a database-driven architecture. It also incorporates Progressive Web App (PWA) capabilities to improve accessibility and support selected offline operations.

---

## Features

### Customer Features
- Browse bicycles, bicycle parts, and accessories.
- View product information and availability.
- Add products to a wishlist.
- Place and manage orders.
- Communicate through the Live Chat feature.
- Receive notifications.
- Install the application as a Progressive Web App.

### Administrator Features
- Manage products and product categories.
- Manage inventory and stock information.
- Monitor and manage customer orders.
- Manage customer interactions and notifications.
- Access administrative system functions.

### System Features
- REST API integration.
- Real-time communication using Socket.IO.
- Push notifications.
- Progressive Web App support.
- Offline order queuing and background synchronization.
- Responsive user interface.
- Database integration.
- Soft-delete and archiving functionality where implemented.

---

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Development and Build Tool | Vite |
| Styling | CSS |
| Backend | Node.js |
| API | REST API |
| Real-Time Communication | Socket.IO |
| Database | TiDB Cloud / MySQL-compatible database |
| PWA | Service Worker and Web App Manifest |
| Version Control | Git and GitHub |

---

## Project Structure

```text
C5-CycleHub/
│
├── backend-node/
│   ├── src/
│   │   ├── db.js
│   │   └── server.js
│   ├── package.json
│   └── .env.example
│
├── backend/
│   ├── api/
│   ├── config/
│   └── server.js
│
├── database/
│   └── schema.sql
│
├── frontend/
│   ├── public/
│   │   ├── icons/
│   │   ├── manifest.webmanifest
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   ├── App.jsx
│   │   ├── api.js
│   │   ├── main.jsx
│   │   └── style.css
│   ├── package.json
│   └── vite.config.js
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## Installation and Setup

### Prerequisites

Install the following before running the project:

- Node.js and npm
- Git
- A MySQL-compatible database or configured TiDB Cloud database
- Visual Studio Code or another code editor

### 1. Clone the Repository

```bash
git clone https://github.com/Marc07-7/C5_CycleHub.git
cd C5_CycleHub
```

### 2. Install Backend Dependencies

```bash
cd backend-node
npm install
```

### 3. Configure Backend Environment

Create a local `.env` file using `.env.example` as your reference.

Configure the required database connection, server port, session settings, and frontend origin.

Never commit actual environment files, passwords, database credentials, or private certificates.

### 4. Install Frontend Dependencies

Open another terminal:

```bash
cd frontend
npm install
```

Configure the frontend environment using the provided `.env.example` file.

### 5. Configure the Database

Create or configure your database and use:

```text
database/schema.sql
```

as the initial database schema reference.

Additional migrations may be required for features implemented after the initial schema.

### 6. Run the Application

Start the backend using its configured development script:

```bash
cd backend-node
npm run dev
```

Start the frontend in another terminal:

```bash
cd frontend
npm run dev
```

Use the local URLs displayed by the development servers.

---

## Development Team

| Member | Role |
|---|---|
| Marc Stephen L. Fernandez | Full Stack Developer |
| John Pheus P. Miran | Backend Developer |
| Cristian M. Neri | Frontend Developer |

The team collaborates through GitHub for source-code management, version control, and project development.

---

## Repository

**GitHub:** https://github.com/Marc07-7/C5_CycleHub

**Branch:** `main`

---

## Project Status

C5 CycleHub is under active development. Features and documentation may be updated as the development team improves the system.

---
