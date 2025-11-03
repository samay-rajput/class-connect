<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!--<title>School Management System</title>-->
</head>
<body>
  <h1 align="center">ClassConnect</h1>
  <p>This project is a web-based application aimed at catering specifically to small scale education environments. It offers a dynamic and personalized learning environment, enhancing class management for educators and learners alike.</p>

  <h2>Functionalities</h2>
  <ul>
    <li><strong>User Roles:</strong> The system supports three user roles: Admin, Teacher, and Student, each with specific functionalities and access levels.</li>
    <li><strong>Effortless Zoom Meeting Creation:</strong> The platform integrates with Zoom to automate meeting link generation. Zoom meeting links are distributed automatically to designated rooms and to their registered emails as well.</li>
    <li><strong>Personalized students' stats: Analysis of attendance of the student and marks obtained by him/her in each subject.</li>
    <li><strong>Providing study material: Teacher of a particular class will upload study material, which will be accessible to the students of that class only.</li>
    <li><strong>Secure Admin Dashboard:</strong> Admins have controlled access to administrative features, enabling them to manage users, classes, subjects, and system settings securely.</li>
    <li><strong>Attendance Tracking:</strong> Teachers can efficiently track attendance for both offline and online classes through a user-friendly interface. Attendance data is seamlessly recorded and monitored.</li>
    <li><strong>Age-Specific Virtual Classrooms:</strong> Virtual rooms designated for specific age groups facilitate targeted class organization, ensuring a tailored learning experience.</li>
    
  </ul>

  <h2>Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> React.js, Material UI, Redux</li>
    <li><strong>Backend:</strong> Node.js, Express.js</li>
    <li><strong>Database:</strong> MongoDB</li>
  </ul>

  <h2>How to Run the Project</h2>
  <h3>Installation</h3>
  <ol>
    <li>Clone the GitHub repository:</li>
    <pre><code>git clone https://github.com/samay-rajput/class-connect.git</code></pre>
    <li>Navigate to the project directory:</li>
    <pre><code>cd classConnect</code></pre>
    <li>Navigate to backend folder and create .env file. Go to MongoDB Compass/Atlas in your device and create a database and take its connection link and put it in the .env file:</li>
    <li>Install backend dependencies and start the server:</li>
    <pre><code>cd backend</code></pre>
    <pre><code>npm install</code></pre>
    <pre><code>npm start</code></pre>
    <li>Open a new terminal tab/window, navigate to the project directory again, and install frontend dependencies:</li>
    <pre><code>cd frontend</code></pre>
    <pre><code>npm install</code></pre>
    <li>Start the frontend server:</li>
    <pre><code>npm start</code></pre>
    <li>Access the application in your browser at <code>localhost:3000</code>.</li>
  </ol>
 