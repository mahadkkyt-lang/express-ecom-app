Dont forget to connect to connect to your database in mongoDB compass before you run the project or you will get this error:

ERROR: operation timed out buffering after waiting 1000ms

###_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
Run these commands AT THE project's ROOT directry before running the project:  


npm i express:          (important for every express porject)

npm i mongoose:         (for db connection and crud)

npm i bcrypt:           (for password hashing and matching)

npm i ejs:              (view  engine)

npm i nodemailer:       (for sending emails to clients)

npm i jsonwebtoken:     (for making tokens and cookies)

npm i cookie-parser:    (for validating cookies and using the data stored inside cookies)

#Obove packages are very important

npm i nodemon:          (autoupdates your app on the brower when you edit something in the code while the app is running)
#(this one only is optional but helpfull and recomended)

if you dont run the command obove in the correct folder then you will get error when you run the project

and to run this command at the root of the project's directry to run the webapp:
nodemon

IF you didnt run npm i nodemon then run this commmand instead at the root to run the project:
node index.js
