# Code Café Back-end
<div align="center"> <h1>Code Cafe E-commerce Site </h1>
  <h3>The application features food and drinks for sale</h3>
</div>
<br />
<div align="center">
    <h3>Code Café is an e-commerce site that features foods and drinks for sale. Users are able to add items to their carts, edit their carts, check out, and submit their orders. I also added
authentication to allow users to log in to the site.</h3>

</div>
<br />
<div align="center"><h3>Technologies used in the e-commerce app development:</h3>
<ul align="left">
  <li>ReactJS</li>
  <li>ExpressJS</li>
  <li>NodeJS</li>
  <li>Rest Api</li>
</ul>
</div>

<h2 align="center">This is the back-end server for the Code Café application.</h2>

Run with `npm start`
<br />
## Available Endpoints

- GET `/api/items` returns all the items for Code Café
- `/api/orders` is a RESTful interface for orders
    - GET `/api/orders` returns all the orders
    - POST `/api/orders` creates an order
    - DELETE `/api/orders` deletes all the orders
    - GET `/api/orders/:id` return one order
    - PUT `/api/orders/:id` updates an order
    - DELETE `/api/orders/:id` deletes one order
- `/api/auth` is an interface for authenticating users
    - GET `/api/auth/current-user` returns the currently logged-in user or `{}` if no user is logged in
    - POST `/api/auth/login` with username and password as the JSON body logs in a user and returns 401 if the login is invalid
    - POST `/api/auth/logout` logs out a user
- GET `/api/employees/isEmployeeOfTheMonth` with name as the search query returns a boolean indicating an employee of the month
