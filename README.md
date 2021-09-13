# MERN Stack Tutorial(MongoDB+Express+React+Node)
![Demo image](https://webimages.mongodb.com/_com_assets/cms/kobwy5fsc8wohx9e8-sample-record-landing-page.png?auto=format%2Ccompress)
![Demo image](https://webimages.mongodb.com/_com_assets/cms/kobwz1sx81jn872d7-sample-create-record-landing-page.png.png?auto=format%2Ccompress)
This program copy from official MongoDB MERN stack tutorial[ https://www.mongodb.com/languages/mern-stack-tutorial](https://www.mongodb.com/languages/mern-stack-tutorial).
###
If your follow the above tutorial well, you can easily build(copy + paste) the App within 20 minutes, but still spend some time to try to understand the coding.

There is only one place you need to replace is as below:
##
In directory server/, please replace your own `ATLAS_URI` in config.env file. Replace the `username` and the `password` with your database username and password.
```javascript
ATLAS_URI=mongodb+srv://<username>:<password>@sandbox.jadwj.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
PORT=5000
```
You can get your own `ATLAS_URI` from [here](https://account.mongodb.com/account/register), there is very clear steps in [https://www.mongodb.com/languages/mern-stack-tutorial](https://www.mongodb.com/languages/mern-stack-tutorial), scroll down that tutorial page to `Connecting to MongoDB Atlas`, you will find out  sooner or later.
# How to run the code
>```git clone https://github.com/clairyitinggu/mern_stack.git```
## Go to client folder
>``` npm install```
## Go to server folder
>``` npm install```
## Go into the server folder and run the command 
>```nodemon server.js```
## Go back to the client folder and run the command 
>```npm start```

Have Fun