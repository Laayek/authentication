# Authentication

### To run the backend

1. npm install
2. Create a .env file with "URI", "API_KEY" && "SENDER_EMAIL" variable names

- URI = Your MongoDB connection string (select Node.js as your native driver)
- API_KEY = You need to get the API key from https://www.brevo.com/ (formerly Sendinblue)
- SENDER_EMAIL = The email from which you want to send OTP to users when they try to reset their password

3. nodemon index.js

### To run the frontend

1. Navigate to the client folder
2. npm install
3. npm run dev
