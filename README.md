# Todo_hackathon
Reading Tracker is a full-stack web application that helps users manage and track their reading progress. It allows users to securely log in using Google, add books they’re reading, update progress, and remove books when finished.  The app is built with React (frontend), Node.js + Express (backend), and MongoDB (database).
🔧 Tech Stack
Frontend: React + Material UI
Backend: Node.js + Express
Database: MongoDB (Atlas or local)
Authentication: JWT + Google OAuth
Extras: Fully responsive, modular, and well-documented
🚀 Features
✅ Login with Google or username/password
✅ Add books with title, author, current status (Reading/Completed/Want to Read)
✅ Edit/update/delete books
✅ Filter books by status
✅ Material UI for sleek design
✅ JWT-secured backend API
✅ Environment secrets handled via .env
✅ Architecture diagram and README included
codelink:https://ci3.googleusercontent.com/meips/ADKq_NaFh0MxMsIVdKWZyOmi9Hv_5s7XwjA-HNEYS6Aoz130_8vGxZfadhQRY2DhzEBAFjxTIP0aWo2oBj0WRsDDWiD5d8BGMBX1OOT4vt9xQ9OEQedRh7szXc_T9e87ukBArhwaK5Aa-1V0CQ=s0-d-e1-ft#https://drive-thirdparty.googleusercontent.com/32/type/application/x-zip-compressed
🔧 Setup Instructions
1.Backend
bash
cd backend
npm install
2.Create .env:
MONGO_URI=your_mongo_url
JWT_SECRET=your_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_clien_secret
3.Start backend:
bash
npx nodemon server.js
4.Frontend
bash
cd frontend
npm install
npm start
Visit http://localhost:3000. 
Assumptions: Uses manualemail/password registration AND Google OAuth. JWT stored in localStorage. Reads books tied to authenticated user only.
