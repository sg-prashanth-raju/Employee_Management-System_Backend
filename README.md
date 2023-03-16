## Employee Management System | React, Express, MongoDB, Node.js, Material UI

- Developed a full-stack web application for managing Employee information with Express.js serving a REST API and with React as the front end
- Used MongoDB to store user and employee information
- Implemented ”Trust this Device” feature during login to handle Auth token expiry by fetching new Auth token using Refresh token stored in browser cookie
- Used Material UI library to style the front end

To run the project on your machine run the follwing commands in your terminal

# Frontend
```sh
git clone https://github.com/sg-prashanth-raju/Employee_Management-System_Frontend
cd Employee_Management-System_Frontend
npm install
npm start
```

# Backend
```sh
git clone git clone https://github.com/sg-prashanth-raju/Employee_Management-System_Backend
cd Employee_Management-System_Backend
npm install
npm run dev
```

# The MERN application is deployed on [Render].
- On registering a new user, you will be assigned a user role which is allowed to fetch and view employee details
- For creating and editing employee details you need to have editor role. Credentials for editor role - Username:Naveen Password:N@veen123
- For deleting employee you need to have admin role. Credentials for editor role - Username:Prashanth Password:Raju123

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
   [Render]: <https://employeemanagementsystem-4qjp.onrender.com>
