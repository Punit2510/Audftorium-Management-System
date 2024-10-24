# Auditorium Management System

This project is a web-based application designed for managing an auditorium with different user roles: Admin, Salesperson, and Accountant. The project is built using React.js for the frontend and Firebase for the backend, with deployments on Firebase and Netlify.

## Project Setup

### To run the project locally:
1. Clone the repository.
2. Open the project directory.
3. Run the following commands:


npm install
npm start

Web Deployed Links .

1. https://643287dd7e2e5278df0bbf6c--astounding-churros-59db32.netlify.app/

2. https://auth-roles-react.web.app/.

Note: There is a known issue with the deployed links where reloading the page causes the app to break. You may need to click the link again for access. To avoid this, use the local server when possible.


User Roles and Functions
The system supports three types of users:

1. Admin
Role: Only one Admin is allowed.
Functions:
1. Add a user.
2.Delete a user.
3. Set a show on a particular date in the auditorium.
4. Delete a show.
5.Access the yearly expenditure sheet.

2. Salesperson
Role: Multiple Salespersons are allowed.
Functions:
1. Book tickets for a show as requested by customers.
2. Cancel booked tickets.

3. Accountant
Role: Multiple Accountants are allowed.
Functions:
1. Provide expenditure cost for every show.


Technology Stack
Frontend: React.js
Backend: Firebase
Deployment: Firebase, Netlify

