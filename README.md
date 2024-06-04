
# PermaList Web Application

## Overview
PermaList is a web application that allows users to manage a to-do list interactively. This application utilizes Node.js with Express for server-side operations, PostgreSQL for data management, and EJS for rendering dynamic HTML pages.

## Features
- **List Viewing**: View all tasks in a list sorted by item ID.
- **Add Items**: Add new tasks to the list via a web form.
- **Edit Items**: Update existing tasks.
- **Delete Items**: Remove tasks from the list.

## Technology Stack
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Frontend**: EJS, HTML, CSS

## Installation and Setup

### Prerequisites
- Node.js
- PostgreSQL

### Setup Instructions
1. **Clone the repository**:
   ```
   git clone [repository-url]
   cd [repository-name]
   ```
2. **Install dependencies**:
   ```
   npm install
   ```
3. **Set up the PostgreSQL database**:
   - Ensure PostgreSQL is installed and running.
   - Create a database named `permalist`.
   - Use the provided SQL queries to set up the required tables.

4. **Configure the application**:
   - Update the database credentials in `index.js` if necessary.

5. **Start the application**:
   ```
   npm start
   ```

6. **Access the application**:
   - Open a web browser and navigate to `http://localhost:3000`.

## Usage
After launching the application, the homepage will display the current tasks. You can add, edit, or delete tasks using the form provided on the page.

## Contribution
Contributions are welcome. Please fork the repository and submit pull requests to the master branch.

