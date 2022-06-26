# Body Path - Microservices

![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)![expressjs](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

![reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) ![redis](https://img.shields.io/badge/Redis-D9281A?style=for-the-badge&logo=redis&logoColor=white)

> Body Path project core repository

## 💻 Requirements

First, verify if you have:

* Install `Node@16.15.0`
* MySQL  `MySQL@8.0` or latest.

## 🚀 Install Microservices

To install, follow these steps on all microservices:

```
npm install
```

The commands below refer to database creation, migration and population, respectively:

- MS-Customer:

  ```
  npx sequelize db:create
  npx sequelize db:migrate
  npx sequelize db:seed:all
  ```


- MS-Physical Evaluation:

  ```
  npx sequelize db:migrate
  npx sequelize db:seed:all
  ```

- MS-Food Plan:

  ```
  npx sequelize db:migrate
  npx sequelize db:seed:all
  ```

## ☕ How to start Microservices

After reviewing the configuration file `./src/config/database.js` is correct, just run:

```javascript
npm start
//or
npm run dev
//or
npm run test
```