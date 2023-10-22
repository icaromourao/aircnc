# Simple Node.js, React, and MongoDB Project

This project is a basic web application implemented with Node.js for the backend, React for the frontend, and MongoDB for the database. The Node.js backend serves as an API, utilizing Express for routing. The React frontend is a web platform with three main pages: login, dashboard, and a new item page. The database is configured using MongoDB Cloud, specifically MongoDB Atlas.

## Technologies Used

- **Backend:** Node.js with Express
- **Frontend:** React
- **Database:** MongoDB (MongoDB Atlas for cloud hosting)

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone git@github.com:icaromourao/aircnc.git
   ```

2. Install the necessary dependencies for both the backend and frontend:

   ```bash
   cd aircnc
   cd backend
   yarn install

   cd ../frontend
   yarn install
   ```

3. Configure the MongoDB database connection, specifying the MongoDB Atlas URI.

4. Start the backend server:

   ```bash
   cd ../backend
   yarn dev
   ```

5. Start the React frontend:

   ```bash
   cd ../frontend
   yarn start
   ```

6. Access the web platform by opening it in your browser. You can navigate through the login, dashboard, and new item pages.
  
## License

This project is licensed under the [MIT License](https://github.com/icaromourao/aircnc/blob/master/LICENSE).
