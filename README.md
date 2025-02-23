🚀 Getting Started with Your MERN Project
1️⃣ Prerequisites
Before running the project, make sure you have installed:

Node.js (Includes npm)
MongoDB (if your app requires a database)

Clone the Repository
Open PowerShell or Terminal, then run:

git clone https://github.com/LikhithaGeetha/Mern.Full.Stack.git
cd Mern.Full.Stack

 Install Dependencies
Run:

npm install
This will install all required dependencies from the package.json file.

Running the Application
✅ Start the Client (React)
Navigate to the client folder:

sh
Copy
Edit
cd client
npm start
This should open the React frontend at:


http://localhost:3000
✅ Start the Server (Express)

cd ../server
nodemon server.js
If nodemon is not installed, install it globally:


npm install -g nodemon

nodemon server.js
5️⃣ Access the Application
Login Page:
👉 http://localhost:3000/login
Dashboard:
👉 http://localhost:3000/dashboard
npm install
npm start


rm -rf node_modules package-lock.json
npm install
npm start
2. If nodemon command is not found
Run:


npm install -g nodemon
3. If MongoDB is not running
Start MongoDB locally or use a cloud database like MongoDB Atlas.

