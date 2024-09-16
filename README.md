# Permalist

Permalist is a simple, yet powerful to-do list application built with Node.js, Express, and PostgreSQL. It allows users to create, read, update, and delete tasks in a persistent manner.

## Features

- Add new tasks to your list
- Edit existing tasks
- Delete tasks
- Persistent storage using PostgreSQL database

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- PostgreSQL installed and running
- Git (for cloning the repository)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/GavriloaiaMircea/PermaList.git
   ```

2. Navigate to the project directory:
   ```
   cd PermaList
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Set up the database:
   - Create a new PostgreSQL database named `permalist`
   - Run the SQL commands in the `queries.sql` file to create the necessary table

5. Update the database connection details in `index.js` if needed:
   ```javascript
   const db = new pg.Client({
     user: "postgres",
     host: "localhost",
     database: "permalist",
     password: "pgadmin2212",
     port: 5432,
   });
   ```

## Usage

1. Start the server:
   ```
   node index.js
   ```

2. Open your web browser and navigate to `http://localhost:3000`

3. Start managing your tasks!

