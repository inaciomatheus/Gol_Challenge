# Challenge

This challenge consists of two different parts.

##  First Task

The objective of the first part of this challenge represents a problem close to a real scenario where a broken frontend applcation needs to be fixed.

### Install API KEYS 

In the file backend/app.js, replace API_KEY  on line 7 and API_SECRET on line 8 by the values sent by e-mail:

                6 const amadeus = new Amadeus({
                7     clientId: API_KEY,
                8     clientSecret: API_SECRET,
                9 });

After that you will need to install the dependencies of the project following the intructcions bellow:

### 1 - Install NODE.js

### 2 - Run npm init -y

### 3 - Then install angular dependencies.

    3.1 - Express
    3.2 - Cors
    3.3 - Amadeus
    3.4 - Nodemon
    3.5 - Angular CLI

These dependecies can be installed by running the following commands in your terminal:

    npm install express amadeus cors nodemon
    npm install -g @angular/cli

After installing these dependencies navigate to */backend* folder and run:

    npm start

You will know that the backend api is running when the following message appears:

    [nodemon] 2.0.15
    [nodemon] to restart at any time, enter `rs`
    [nodemon] watching path(s): *.*
    [nodemon] watching extensions: js,mjs,json
    [nodemon] starting `node app.js`
    Server is running on port: http://localhost:5000

Now go back to the project root and navigate to */flight-booking-frontend*

Try running npm start and you will receive an error message.

Fix all errors and when you can run the frontend aplication from start to finish go to step two.

## Second Task

Using your creativity and your knowledge of user interfaces and user experience, modify the application in order to add GOL LINHAS AEREAS visual identity to it while also making it simple to use.

The functionality must remain the same.

Feel free to add any technique or technology to the project in order to achieve these goals.



   
