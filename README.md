1. Code Editor
   1. Web Browser
   2. VS Code Extension
   3. Create amazon folder
   4. create template folder
   5. create index.html
   6. add default HTML code
   7. link to style.css
   8. create header, main and footer
   9. style elements
2. Display Products
    1. create products div
    2. add product attributes
    3. and link, image, name and price
3. Create React App
   1. yarn create @vitejs/app frontend
   2. Remove unused files
   3. copy index.html content to App.js
   4. copy style.css content to index.css
   5. replace class with className
4. Create Rating and Product Component
   1. create components/Rating.js
   2. create div.rating
   3. style div.rating, span and last span
   4. Use Rating component
5. Build Product  Screen
   1. Install react-router-dom
   2. Use BrowserRouter and Route for Home Screen
   3. Create HomeScreen.js
   4. Add product list code there
   5. Create ProductScreen.js
   6. Add new Route from product details to App.js
   7. Create 3 columns for product image, info and action
6. Create Node.js Server
   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. rum yarn start
7. Load Products From  Backend
   1. edit HomeScreen.js
   2. define products, loading and error
   3. create useEffect
   4. define async fetchData and call it
   5. install axios
   6. get data from /api/products
   7. show theme in the list
   8. create Loading Component
   9. create Message Box Component
   10. use theme in HomeScreen