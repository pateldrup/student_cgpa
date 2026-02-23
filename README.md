# Student CGPA API

=> Build a REST API using Express.js that manages student CGPA records stored in an in-memory JSON array.

## Implemented Routes
    1. GET /students :- Return All Students
    2. GET /students/topper :- Return the student with highest CGPA
    3. GET /students/average :- Return average CGPA of All Students
    4. GET /students/count :- Return total Number of Students
    5. GET /students/:id :- Return student by ID    (Dynamic Route)
    6. GET /students/branch/:branchName :- Return all students from a specific branch   (Dynamic Route)

## Sample API URLs 
    http://localhost:5000/students
    http://localhost:5000/students/topper
    http://localhost:5000/students/average
    http://localhost:5000/students/count
    http://localhost:5000/students/:id
    http://localhost:5000/students/branch/:branchName

## Steps for Run Locally
    => 1. Clone the Repository
   https://github.com/pateldrup/student_cgpa.git

    => 2. Navigate into the Project Folder
    cd backend_server

    => 3. Install Dependencies to Run
    npm install

    => 4. Start the Server
    node index.js (file_name)

## Deployed Links

=> https://student-cgpa-1.onrender.com/