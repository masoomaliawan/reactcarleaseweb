## 📋 Instructions
#### Application Structure
```
│
├── bin
├── models (MongoDB Mongoose Models)
├── node_modules 
├── public (application resources - css, js, images)
├── routes (handles admin, electric and gas routes)
├── views  (express-handlebars templates)
    ├── admin (admin templates)
    ├── layouts (default layout templates)
    └── electric and gas template files
├── app.js (root Node app script)
├── package.json
└── README.md
```


#### General
1. Install Dependencies using `npm install`
2. Make sure `MongoDB` server is running
3. Create a database named `autorizz`
4. Create all the required `collections` in the created database and fill in the data from `db_data`


#### Local
1. Inside  `--> app.js` under MongoDB section, replace the url with `mongodb://localhost:27017/autorizz`
2. Open Terminal in the app folder
3. Run `npm start` or `nodemon start` (if nodemon is preinstalled)
4. Launch client app in `localhost:5000`
4. Launch admin app in `localhost:5000/admin`
