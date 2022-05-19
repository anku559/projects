# About Project

## Programming Language

* JavaScript
  * Runtime Environment - NodeJS
    * NodeJS Framework - ExpressJS



## NPM Packages Used

* `bcrypt` - Hashing and Salting Password.
* `canvas` - Creation of blank canvas for the QR Code. 
* `multer` - For handling Multi Part data.
* `sharp` - For Image size manipulation.
* `nodemailer` - For sending mails.
* `pug` - Templating Engine used for server side rendering.
* `qrcode` -  For generation of QR Code to the user for the crowd filteration.
* Others - `cors | helmet | dotenv | faker | morgan | `



## Database

From the development phase have hosted the database on MongoDB Live Cluster.

* MongoDB
  * MongoDB ORM - Mongoose


* Database GUI Management - MongoDB Atlas, MongoDB Compass, Robo3T



## Payment Gateway

* Razorpay - QR Code Scanner, Payment based on UPI ID



## Project Structure, Design Pattern and Code Style

* Project was designed with the MVC (Model, Views, Controller) Architecture approach following the standard RestAPI best practices.
* Initially when I was creating the project used the `callback` design pattern but ultimately shifted to new ECMA standard `async/await`
* Project uses the ESLint linter with the very famous AirBnB style guide. 



## Tools Used

* Code Editor - VS Code

* Project Managed on - Trello Board

* Postman
* Jest
* Linter - `eslint`
  * `prettier ` Extension
* Mind Mapping and Database Mapping - XMind and Diagrams.io
* Documentations - Google [Sheets, Docs], Microsoft Office 



---

---



# Admin Panel

* Admin
  * Creation of Admin
  * Login of Admin
  * Password Change (Forgot Password) and Password Update



## Dashboard

* Displaying various counts of the data such as Users, Vendors, Market Vendors, Subscriptions, Users on different platform such as [Android, iOS].
* Pie Chart - Displaying of of Vendor data based on the Business types.
* Bar Graph - Registration of Users, Vendors and Market Vendors on Monthly basis.

 

## Client

* Users
  * Listing of All the Users using Pagination concept.
  * Filtering of Users based on Username, Email Address and Phone Number.
  * Sorting of the Users by the Creation Date (newest on top)
  * Viewing the details of specific User.



* Vendors
  * Listing of All the Vendors using Pagination concept.
  * Filtering of Vendors based on Unique ID (generated), Email Address, Phone Number, City, Business Type, Service Type
  * Sorting of the Vendors by the Creation Date (newest on top)
  * Viewing the details of specific Vendor.



* Market Vendors
  * Listing of All the Vendors using Pagination concept.
  * Filtering of Market Vendors based on Unique ID (generated), Email Address, Phone Number, Business Type.
  * Sorting of the Market Vendors by the Creation Date (newest on top)
  * Viewing the details of specific Market Vendor.



## Business | Services and Sub-Services

Business (CRUD)

* Services (CRUD)
  * Sub-Services (CRUD)



## Market Business

Market Business (CRUD)



## Subscriptions

Subscriptions (CRUD)



## Advertisements

Advertisements (CRUD)



## Blogs

Blogs (CRUD)



## Events

Events (CRUD)



## Reports

## Contact



---

---



# Vendor Panel



---

---



# Market Vendor Panel



---

---



# Website for User



---

---



# Mobile App for Users



---

---



# Mobile App for Vendors



---

---



# Mobile App for Market Vendors