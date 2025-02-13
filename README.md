# Family Travel Tracker

## Overview

The Family Travel Tracker is a web application designed to help families monitor and record their travel histories. Users can add family members, log visited countries, and visualize travel data on an interactive map.

## Features

- User Profiles: Create individual profiles for each family member.
- Travel Logging: Add and manage a list of countries each member has visited.
- Interactive Map: Visual representation of visited countries.
- Data Management: Store and retrieve data efficiently using PostgreSQL.

## Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript
  - EJS (Embedded JavaScript Templates)
- Backend:
  - Node.js
  - Express.js
  - PostgreSQL

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the Repository:
   ```bash
   git clone https://github.com/Chandrakanth2328/Family_Travel_Tracker.git
   cd Family_Travel_Tracker
   ```

2. Install Dependencies:
   ```bash
   npm install
   ```

3. Configure the Database:
   - Ensure PostgreSQL is installed and running.
   - Create a database named `family_travel_tracker`.
   - Execute the SQL script provided in `queries.sql` to set up the necessary tables.

4. Set Up Environment Variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     DATABASE_URL=your_postgresql_connection_string
     PORT=3000
     ```

5. Start the Application:
   ```bash
   npm start
   ```
   Access the application at `http://localhost:3000`.

## Usage

- Add Family Members: Navigate to the "Add Family Member" section to create profiles.
- Log Travels: For each member, add the countries they have visited.
- View Map: Use the interactive map to see a visual representation of the travels.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## Acknowledgements

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [EJS](https://ejs.co/)
