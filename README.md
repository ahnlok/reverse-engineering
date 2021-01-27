# **Reverse Engineering Code**
## _Table of Contents:_
1. **[Installation](#installation)**
2. **[Explanation](#explanation)**
3. **[Link](#link)**
4. **[Contact](#contact)**
5. **[License](#license)**
---
## **Installation**
#### **_git clone: git@github.com:ahnlok/reverse-engineering.git_**
---

## **Explanation**

#### **_List inside this section_**
1. [Overview](#overview)
2. [Tools](#tools)
3. [Start](#start)
4. [Files](#files)

<br />

### **Overview**
##### -_This app allows the user to "Create", "Log-In", and "Log-Out" to the account securely._ 
##### -_Upon creating the account, the user data will be stored in MySQL database._
---
<br />

## **Tools**
##### _Node.Js, MySQL2, Sequelize, Passport, Express, JavaScript, HTML5, and CSS._
---
<br />

## **Start**
##### _1) Create a MySQL database named "passport_demo."_

<br />

##### _2) Inside the "config" folder, go to "config.json", then add your "MySQL password" to the "password" sections._
<br />

##### _3) Run "npm install" in your terminal to download required node packages._
<br />

##### _4) Once the node packages have been downloaded, run "node server.js" in your terminal to start the server._
<br />

##### _5) Open the browser, then enter <http://localhost:8080> inside the address tab to redirect to the app._
<br />

##### **_Now You're All Set!_**
---
<br />

## **Files**
### **_List of Files for The App_**
1. [config](#config)
2. [models](#models)
3. [public](#public)
4. [routes](#routes)
5. [server](#server)
<br />

### **_1. config_**
##### **1) isAuthinticated.js (inside "config" -> "middleware"):**
##### _This file restricts routes that the user is not allowed to visit if not logged in. If the user is logged in, it continues with the request._
<br />

##### **2) config.json**
##### _This file allows the connection configuration to connect to the server (Make sure change "password" section to your "MySQL password")._
<br />

##### **3) passport.js**
##### _This file tells passport we want to log in with an email address and password (it contains javascript logic to execute)._
<br />

### **_2. models_**
##### **1) index.js**
##### _This file connects to the database and imports user log-in data._
<br /> 

##### **2) user.js**
##### _This file requires "bcrypt" for password hashing. This makes the database secured even if it is compromised._
<br />

### **_3. public_**
##### _This folder contains HTML, CSS, and Javascript files that required to create "Front-End" part of the app._
<br />

### **_4. routes_**
##### **1) api-routes.js**
##### _This file contains routes for sign-in, log-out, and getting users the specific data to display on the client side._
<br />

##### **2) html-routes.js**
##### _This file creates a route that checks whether the user is logged in, whether user already has an account. It will send the user to the correct html page._
<br />

### **_5. server_**
##### **1) server.js**
##### _This file requires packages, sets up PORT, and creates express, middleware, routes, and sync the database. It also logs the message in the terminal on a successful connection to the server._



---
## **Link**
#### **GitHub Page: <https://github.com/ahnlok/reverse-engineering>**
#### **Google Doc: <>**
---
## **Contact**
#### **E-Mail: <ansungpil1@gmail.com>**
#### **GitHub: <https://github.com/ahnlok>**
#### **LinkedIn: <https://www.linkedin.com/in/an-sungpil-95ab8490/>**
---
## **License**
### **© Sungpil An 2021**
#### _Licensed under the MIT License_
