This is a Web App made with React.js and then converted into Hybrid Android app using Capcitor/Ionic
[You can find the app here](https://play.google.com/store/apps/details?id=com.rahulkudum.vaisnava_songs).

## Note

### Motivation
I made this App while learning ReactJs in order to make the learning process intresting and useful and now this app is used by thousands of people with 5 star ratings and now i am very happy as this App is helping many people to enchance their Spirtuality

### What I have used 
I used all the important hooks like useState, useEffect, useReducer, useRef, custom hooks and for managing the state of the App instead of using Redux i used React's built Context Api which is pretty cool and ofcourse i used React-Router in this App

For getting the songs and books used in this app i made a simple NodeJS/ExpressJS backend which i hosted in heroku and whenever anyone install the app it fetch all the data from text files in this backend and store in the local storage     

Coming to the Android stuff although this is an hybrid app as I used Capacitor to transform my React web app into android app but it has many native features like downloading the songs and playing the songs from the android device which are made possible by using native capacitor plugins

### Disclamir
As i made this app while learing React so i had used many bad practices of writing code in this project but now as i have many other projects and things to do and lear i was unable to correct them so if you are facing any problem while understanding my code please feel free to mail me

## Other Projects
All the projects are made using MERN Stack
As I made the following projects for other orginasations so I was not supposed to host them publicly so if you want know more about them please feel free to mail me

### Online platform for setting and writting exams
I made a website for Jee/Neet coaching center called Sarthi Academy, In this website teachers can set questions papers in various formats like of JEE Mains, Neet and customisable pattern for JEE Adavnced and students will be able to acess and write those exams and also this website has so many useful features like personal dashboard, detailed exam anlaysis, Authenticaton, cheating finder etc and presently this website is used by somany students who are part of sarathi academy.

### Website/Database for NGO called Arjuna Group
I made a website for NGO called Arjuna Group, In this website people who are attending their webinars/courses will be registering for them and also the Arjuna members can see the details of those people and courses and also they can store the data of their volunters, courses, speakers etc. Also they can perform search operations, modify/delete the data in bulk without having any database knowledge as I made intraface for those things directly from the website and also they can do many other this like getting the details in excel file etc.                

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.


### 'npx cap sync android'

Syncs the changes made in the React App to the Android
For using this you should have Capacitor installed and also you must do npm rum build before runing this script  
