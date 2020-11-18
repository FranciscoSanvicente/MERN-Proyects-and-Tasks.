# MERN-Proyects-and-Tasks.

Web application made with the MERN stack (MongoDB, Express, React, Node) which consists of being able to create projects and of them tasks allows the user:

1. Register in the app

     - Validation of the form: it does not allow to register if they are not
       all fields filled in, if the password is less than 6
       digits or if the password confirmation does not match

     - Start section: Authentication with JWT
     - All data is saved in MongoDB
     - Each password reaches the database encrypted so the
       administrator cannot know it giving more security to the user
    
![](https://github.com/FranciscoSanvicente/MERN-Proyects-and-Tasks./blob/main/Docs/Captura.PNG)

![](https://github.com/FranciscoSanvicente/MERN-Proyects-and-Tasks./blob/main/Docs/Captura1.PNG)

Once the user has logged in or registered, it allows him to enter the main site of the app

![](https://github.com/FranciscoSanvicente/MERN-Proyects-and-Tasks./blob/main/Docs/Captura2.PNG)

In this section the user can create new projects, in turn new tasks which can:

- Delete them
- Edit them
- Give them as completed or incomplete
- Easily switch between projects and tasks

![](https://github.com/FranciscoSanvicente/MERN-Proyects-and-Tasks./blob/main/Docs/Captura3.PNG)

![](https://github.com/FranciscoSanvicente/MERN-Proyects-and-Tasks./blob/main/Docs/Captura4.PNG)

# Installation
1. navigate to the project folder
2. install dependencies: `npm install`
3. define your environment variables: 
    En Frot-End
    - DB_MONGO=mongodb://localhost/merntasks
    - SECRETA=
    En Back-End
    - REACT_APP_BACKEND_URL=http://localhost:4000
4. start with 
    ```cd Back-End 
    npm run dev
    cd Frot-End
    npm start```


