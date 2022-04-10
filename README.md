# WAD-Project
Project for EG3701 – Web API Development (Rohit, Jasmine)
Set-up
1) In the Integrated Terminal (ensure you cd into the project root directory), do the following;
 - npm install express mongoose materialize-css@next nodemon multer bcrypt 
 - Create a wadProjectDB database in MongoDB Compass and import in the JSON Files from the assets > database Folder
2) To start the project, type npm start in the integrated terminal

- Account:
    1) User Account:
    user1@gmail.com
    userpass
    user2@gmail.com
    userpass
    2) Admin Account: 
    admin@nanyanghealth.com
    adminpass
    3) Staff Account:
    staff@nanyanghealth.com
    staffpass
Features:
    1) Jasmine: 
    
    - View vaccination status. ✔ (http://localhost:3000/vaccinationStatus)

    - View Covid-19 data. ✔ (http://localhost:3000/viewData)

    - Check Out and View Payment History ✔ (http://localhost:3000/store)

    - Book, edit and cancel appointments. ✔ (http://localhost:3000/appointment)
    
    2) Rohit:
        
    - View, edit, delete, add staff record. ✔ (http://localhost:3000/staffRecord)

    - View, Edit, Delete, Add treatment record. ✔ (http://localhost:3000/treatmentRecord)

    - View Covid-19 news from Api. ✔ (http://localhost:3000/covidNews)

    - Update ART test result. ✔ (http://localhost:3000/ART)

    - View, edit, delete, add patient record ✔ (http://localhost:3000/treatmentRecord)

    - Register Account, Login to Account, Log out  ✔ (http://localhost:3000/loginSignup)