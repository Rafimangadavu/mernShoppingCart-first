# MERN AMAZONA

![amazona](/frontend/images/amazona.jpg)

# React Tutorial - Build ECommerce in 6 Hours [2022]

Welcome to my React and Node tutorial to build a fully-functional e-commerce website exactly like amazon. Open your code editor and follow me for the next hours to build an e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).

## Demo Website

- 👉 Heroku : [https://mern-amazona-app.herokuapp.com](https://react-amazona.herokuapp.com)

## You Will Learn

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Context API: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku
- Watch React & Node Tutorial

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:basir/mern-amazona.git
$ cd mern-amazona
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URI=mongodb://localhost/amazona
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URI=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 6. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

## Support

- Contact Instructor: [Basir](mailto:basir.jafarzadeh@gmail.com)


# Lessons
1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository

5. List Products
   1. create products array
   2. add product images
   3. render products
   4. style products

6. Add routing
   1. npm i react-router-dom
   2. create router for home screen
   3. create router for product screen
   
7. Create Node.Js Server
   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add js to imports
   4. npm install express
   5. create route for / return backend/server.js
   6. add start command as mode backend is ready.
   7. require express
   8. create router for / return backend is ready.
   9. move products.js from frontend to backend
   10.create route for /api/products
   11.run npm start

8. Fetch Products from Backend
   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook 

9. Manage State by Reducer Hook
   1. set proxy in package.json
   2. npm install axios
   3. use state hook

10. Add bootstrap UI Framework
   1. npm install react-bootstrap bootstrap
   2. update App.js 
   
11. Create product and Rating Component
   1. create Rating component
   2. create Product component
   3.Use Rating component in product component

12. Create product Details Screen
   1. fetch product from backend
   2. create 3 columns for image, info and action  

13. Create Loading and Message Component
   1. create loading component
   2. use spinner component
   3. create message component
   4. create utils.js to define getError function

14. Implement Add To Cart
   1. Create React Context
   2. define reducer
   3. create store provider
   4.implement add to cart button click handler

15. Complete Add To Cart
   1. Check exist item in the cart
   2. check count in stock in backend
  
16. Create Cart Screen
   1. create 2 columns
   2. display items list
   3. create action column

17. Complete Cart Screen
   1. click handler for inc/dec item
   2. click handler for remove item
   3. click handler for checkout

18. Create Signin Screen
   1. create sign in form
   2. add email and password
   3. add signin button

19. Connect To MongoDB Database
   1.create atlas mongodb database
   2.install local mongodb database
   3.npm install mongoose
   4.connect to mongodb database  

20. Seed Sample Data
   1.create product model
   2.create user model
   3.create seed route
   4.use route in server.js
   5.seed sample product
  
21. Seed Sample Users
   1.create user model
   2.seed sample users
   3.create user route
   
22. Create Signin Backend API
   1.create signin api
   2.npm install jsonwebtoken
   3.npm install express-async-handler
   4.define generateToken

23. Complete Signin Screen
   1.handle submit action
   2.save token in store and local storage
   3. show user name in header 
  
24. Create Shipping Screen
   1.create from inputs
   2.handle save shipping address
   3. add checkout wizard bar

25.Create Sign Up Screen
   1.create input forms
   2.handle submit
   3.create backend api  

26.Implement Select Payment Method Screen
   1.create input forms
   2.handle submit

27.Create Place Order Screen
   1.show cart items, payment and address
   2.handle place order action
   3.create order create api

28.Implement Place Order Action
   1.handle place order action
   2.create order create api

29.Create to Order Screen
   1.create backend api for order/:id
   2.fetch order api in frontend
   3.show order information in 2 columns

30.Pay Order By paypal
   1.generate paypal client id
   2.create api to return client id
   3.install react-paypal-js
   4.use payPalScriptProvider in index.js
   5.use payPalScriptReducer in Order Screen  
   6.implement loadPaypalScript function
   7.render paypal button
   8.implement onApprove payment function
   9.create pay order api in backend

31.Display Order History
   1.create order history screen
   2.create order history api
   3.use api in the frontend

32.Create profile Screen
   1.get user info from context
   2.show user information
   3.create user update api
   4.update user info

33.Publish To Heroku
   1.create and config node project
   2.server build folder in frontend folder
   3.Create heroku account
   4.connect it github
   5.Create mongodb atlas database
   6.Set database connection in heroku env variables
   7.commit and push

34.Add Sidebar and Search Box
   1.add sidebar
   2.add search box

35.Create Search Screen
   1.show filter
   2.create api searching products
   3.display results

36.Create Admin Menu
   1.define protected route component
   2.define admin route component
   3.add menu for admin in header

37.Create Dashboard Screen
   1.create dashboard ui
   2.implement backend api
   3.connect ui to backend


38.Manage Products
   1.create products list ui
   2.implement backend api
   3.fetch data
   
39.Create Product
   1.create product button
   2.implement backend api
   3.handle on click
   
   
40.Create Edit Product
   1.create edit button
   2.create edit product ui
   3.display product into in the input boxes
   
41.Implement Update Product
   1.create edit product backend api
   2.handle update click

42.Upload product Image
   1.create cloudinary account
   2.use the api key in env file
   3.handle upload file
   4.implement backend api to upload

43.Delete Product
   1.show delete button
   2.implement backend api
   3.handle on click

44.List Orders
   1.create order list screen
   2.implement backend api
   3.fetch and display orders

45.Deliver order
   1.add deliver button
   2.handle click action
   3.implement backend api for deliver

46.Deliver order
   1.add delete button
   2.handle click action
   3.implement backend api for delete

47.List Users
   1.Create user list screen
   2.implement backend api
   3.fetch and display users
  
48.Edit user
   1.Create Edit Button
   2.Create Edit product UI
   3.display product info in the input boxes
   4.implement backend api
   5.handle edit click
  
49.Delete User
   1.Delete User
   2.handle click action
   3.implement backend api for delete

50. Choose Address On Google Map
    1. create google map credentials
    2. update .env file with Google Api Key
    3. create api to send google api to frontend
    4. create map screen
    5. fetch google api
    6. getUserLocation
    7. install @react-google-maps/api
    8. use it in shipping screen
    9. apply map to the checkout screen   

51. Email order receipt by mailgun
    1.create mailgun account
    2.add and verify your domain to mailgun
    3.install mailgun.js
    4.set api key in env file
    5.change pay order in orderRouter
    6.send email order 
    
52. Review Orders
    1.create submit review form
    2.handle submit
    3.implement backend api for review   

53. Upload multiple Images
    1. add images to product model
    2. get images in edit screen
    3. show images in product screen