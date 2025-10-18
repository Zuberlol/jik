
Blog App — Next.js + MongoDB
Project Overview
The Blog App is a full-stack blogging platform built using Next.js and MongoDB. It allows users to create, read, update, and delete (CRUD) blog posts efficiently. The application uses Next.js 14 for server-side rendering, Mongoose for database management, and Tailwind CSS for a modern and responsive design. Axios handles API communication, while React Toastify provides smooth user notifications, resulting in a functional and polished blogging experience.

Setup Instructions
1. Install Node.js
If Node.js is not installed, download and install it from the official website:
https://nodejs.org/en/download

2. Open the Project
1.	Open the project folder (for example, BlogApp) in Visual Studio Code.
2.	Right-click inside the sidebar and select “Open in Integrated Terminal.”

3. Install Dependencies
Run the following command in the terminal:
npm install
Wait for all dependencies to finish installing.

4. Configure MongoDB Database
1.	Sign up or log in to your MongoDB provider (for example, MongoDB Atlas).
2.	Create a new project and build a database.
3.	Select the M0 (free) tier and choose a preferred region.
4.	Create a database user with a username and password (avoid using “@” in the password).
5.	Whitelist the IP address 0.0.0.0/0 to allow public access.
6.	Click Connect → Drivers → Connection String and copy the URI.
7.	In the project root, create a file named .env.local and add the following line:
8.	MONGODB_URI=your_connection_string_here
9.	In lib/config/db.js, ensure your MongoDB URI uses the correct username and password.

5. Run the App
Start the development server with:
npm run dev
When it starts, open your browser and visit:
http://localhost:3000

6. Key Technologies
•	Next.js 14.0.4
•	React 18
•	Mongoose 8.1.0
•	Axios 1.6.5
•	Tailwind CSS 3.3.0
•	React Toastify 10.0.3
•	ESLint 8 with Next.js plugin

