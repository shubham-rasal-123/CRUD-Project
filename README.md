# C R U D

![crud](https://user-images.githubusercontent.com/128680209/229861490-4d03630f-ef0e-4463-a618-308266cd0e1b.png)

 CREATE, READ, UPDATE and DELETE. a simple project in crud method on operations.

## Requirements
+ [Npm](https://www.npmjs.com/package/download)
+ [mongoDB Compass](https://www.mongodb.com/try/download/shell)
+ [Express](https://expressjs.com/)
+ [Nodejs](https://nodejs.org/en/download)


## Languages or Frameworks Used
### Steps to create project and install required module:

#### step 1: Start the project using the following command in your project folder:

+ `npm init`

### Package.json file look like

![Screenshot from 2023-04-04 22-24-59](https://user-images.githubusercontent.com/128680209/229863193-8225570b-8c60-4eb8-82c2-3de9462d3552.png)

#### Step 2: Install the required modules using following command:

+ `npm install express`
+ `npm install ejs`
+ `npm install mongoose`
+ `npm install -D nodemon`

#### Step 3: Create two folders inside the project directory using the following command:

+ mkdir models
+ mkdir views
+ mkdir controllers
+ mkdir public
+ mkdir routes


#### Step 4: Create public folder and navigate css and js files inside project directory:

+ cd public
  + mkdir css
    + touch [all.css](https://fontawesome.com/download)
    + touch [bootstrap.css](https://getbootstrap.com/docs/5.3/getting-started/download)
    
  + mkdir js
    + touch [all.js](https://fontawesome.com/download)
    + touch [bootstrap.bundle.js](https://getbootstrap.com/docs/5.3/getting-started/download)
    

#### Step 5: Creates routes file inside project directory:

+ cd routes
  + touch web.js

#### Step 6: Create another file named app.js inside project directory:

+ touch app.js

#### Step 7: Navigate inside model folder and create a file student.js which will contain our Schema

+ cd model
    + student.js

#### Step 8: Navigate inside views folder and create the following ejs files:

+ cd  views
  + edit.ejs 
  + index.ejs
  
+ cd partials
  + footer.ejs
  + header.ejs
  
#### step 9: Navigate inside constrollers folder and create a files which will contain our constrollers files:

+ cd controllers
  + studentController.js
  
#### Step 10: Run the following command to ensure all modules are loaded:

+ `npm install`
  
##  Steps to run the application -
#### Step 1: Type the following command in terminal of your project directory:

+ `npm run dev`

#### Step 2: Open your web browser and type the following address in the URL bar:

+ `(http://localhost:3000/ or http://localhost:8000/)`


##  Output:
