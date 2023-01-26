
<h1 align="center" id="title">YouTube</h1>
YouTube is a global online video sharing and social media platform. It is owned by Google, and is the second most visited website, after Google Search. YouTube has more than 2.5 billion monthly users who collectively watch more than one billion hours of videos each day.


## 🛠 Built with 

Technologies used in the project:



![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&amp;logo=html5&logoColor=white)

![CSS](https://img.shields.io/badge/CSS-007ACC?&style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&amp;logo=javascript&amp;logoColor=F7DF1E)

## 💻 Screenshots

**Home Page:**
![Home Page](file:///C:/Users/PUNEET/Desktop/Homepage.png)



**Single Product Page:**
![Single Product Page](https://user-images.githubusercontent.com/49484642/214049494-35508512-06f3-4bfb-bc2a-95ec473b74aa.png)




## ✨ Features 

- Search functionality
- Fullscreen mode
- Single Video Mode


## 🚀 Demo

**Front-end deployed URL:**

https://shopqmart.vercel.app/


##  📁 Folder structure
#### `Frontend` - Holds the client application
- #### `public` - This holds all of our static files
- #### `src`
    - #### `assets` - This folder holds assets such as images, docs, and fonts
    - #### `components` - This folder holds all of the different components that will make up our pages
    - #### `pages` - These represent a unique page on the website i.e. Home or About. 
    - #### `redux` - It consists of store, reducer, action and actiontypes and is responsible for global state management of our app.
    - #### `App.js` - This is what renders all of our browser routes and different pages
    - #### `index.js` - This is what renders the react app by rendering App.js.
- #### `package.json` - Defines npm behaviors and packages for the client
#### `Backend` - Holds the server application
- #### `config` - This holds our configuration files, like mongoDB uri
- #### `middlewares` - This holds all our middlewares used in our application
- #### `models` - This holds all of our data models or business logic
- #### `routes/controllers` - This holds all of our HTTP to URL path associations for each unique url
- #### `index.js` - An entry file for our Node JS application
#### `package.json` - Defines npm behaviors like the scripts defined in the next section of the README
#### `.gitignore` - Tells git which files to ignore
#### `README` - This file!
# Installation

Clone the project
```bash
git clone https://github.com/SCjadhav21/Project_ShopQ_Mart.git
```
## Client-side usage

Go to the project directory

```bash
$ cd frontend          // go to client folder
$ yarn # or npm i    // npm install packages
$ npm run start        // run it locally

// deployment for client app
$ npm run build // this will compile the react code using webpack and generate a folder called docs in the root level
```
## Server-side usage

**Environment Variables:-**

To run this project, you will need to add the following environment variables to your .env file

```
port                    // the port on which the server will run
mongoDbUrl              // your mongoDB URI to connect to the mongoDB atlas
key                     // key which will be JWT secret key 
```

**Start**

```bash
$ cd backend            // go to server folder
$ npm i                 // npm install packages
$ npm run server        // run it locally
```
## ✍ Authors 

- [@Harshank11](https://github.com/Harshank11)
- [@18Kailash](https://github.com/18Kailash)
- [@sbj1198](https://github.com/sbj1198)
- [@SCjadhav21](https://www.github.com/SCjadhav21)
- [@CodexPuneet](https://www.github.com/CodexPuneet)
##
This project was built during our construct week at Masai School. It was built by a team of 5 developers and executed in 6 days.
       
