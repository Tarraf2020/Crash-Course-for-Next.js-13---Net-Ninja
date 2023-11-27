# Crash Course for Next.js 13 - Net Ninja

This project is a crash course for Next.js 13 that demonstrates how to work on a simple project using the new app router and server components. It focuses on building a help desk application with CRUD operations on tickets. The project utilizes JSON Server as a lightweight database.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v16.17 or higher)
- npm

## Installation

**Step 1: Install Node Modules**

Navigate to the project directory and install the required dependencies using npm:

```bash
npm install -force
```

**Step 2: Run the Database**

Start the JSON Server to simulate a database for the application:

```bash
json-server --watch --port 4000 ./_data/db.json
```

**Step 3: Run the Application**

Run the Next.js development server to start the application:

```bash
npm run dev
```

## Project Overview

The project consists of a simple help desk application with the following features:

- Create new tickets
- View existing tickets
- Edit and update existing tickets
- Delete tickets

The application utilizes Next.js's app router and server components to handle routing and data fetching, respectively. JSON Server acts as a lightweight database to store and manage ticket data.

## Contributions

We welcome contributions to this project. Please feel free to fork the repository, make your changes, and submit a pull request.
