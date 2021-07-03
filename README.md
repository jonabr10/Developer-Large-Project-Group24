# Developer-Environment-For-Large-Project-Group24

Steps on settings up environment:

Things you should already have
- nodejs
- npm
- nodemon
- react-app

==================================
Connecting to the mongoDB database
==================================

<go to> From the terminal/commandLine > navigate to project folder 

<terminal cmd> touch .gitignore
    <contents> 
    node_modules
    .env

<terminal cmd> touch .env
    <contents>
    MONGODB_URI="mongodb+srv://Admin:COP4331@cluster0.4b2nn.mongodb.net/Dev_Large_Project_DB?retryWrites=true&w=majority"
    <blank template>
    mongodb+srv://<User>:<password>@cluster0.4b2nn.mongodb.net/<myFirstDatabase>?retryWrites=true&w=majority
    Note: Replace <User> and <password> with the password for the Admin user. Replace <myFirstDatabase> with the name of the database that connections will use by default. Ensure any option params are URL encoded.
    
<terminal cmd> sudo npm start
    <caution> running the command may throw an exception error
        <what if> Error: Cannot find module 'express'
            <terminal cmd> npm install express
        
        <what if> Error: Cannot find module 'dotenv'
            <terminal cmd> npm install dotenv

