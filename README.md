<!-- stated with npm init to create project  -->
1. npm init
2. creating file index.js


<!-- install express  -->
|| - npm i express


<!-- npm i nodemon --save-dev for dev  -->
|| - npm i nodemon --save-dev 

|| - là công cụ phát triển nodejs
|| - tự động reset khi file có thay đổi


<!--  add key + value to scrpit in package.json -->
|| - "start": "nodemon --inspect index.js"
|| - run project with command npm start
|| - --inspect to debug


<!-- Morgan -->
|| - HTTP request logger middleware for node.js
|| - Quan sát log request từ client
|| - for dev

|| - npm install morgan --save-dev


 <!-- Template engines -->
|| - handlebars
|| - npm install express-handlebars



<!-- Get value  -->

method : get -> req.query.'key'
method : post -> req.body.'key'