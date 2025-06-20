# University-Outpass-System
A MERN stack web application to manage outpass requests for students, with OTP verification and role-based access (Student, Warden).

Tech Stack:
Frontend: React.js, Axios, React Router
Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Others: Nodemailer (for sending OTPs), dotenv (environment variables)

Project Structure:


outpass-management-system/ ├── backend/ │ ├── controllers/ │ ├── models/ │ ├── routes/ │ └── server.js ├── frontend/ │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ ├── services/ │ │ └── App.js └── README.md

Features:

✅ Student Registration with OTP email verification
✅ Apply for outpass with reason, place, dates
✅ View Pending and Previous Outpasses
✅ Warden Login to approve or reject requests
✅ ERP-like dashboard for both students and wardens
