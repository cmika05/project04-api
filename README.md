## Tasks

---

> Add the route to support deleting the item/row in the portfolio table. (Refer to the api router)
 
> ~~Add the route to support creating the item/row in the portfolio table. (Refer to the api router)~~


> ~~Add an apiRouter to your app~~

> ~~Add Sequelize to your application (https://sequelize.org/master/manual/getting-started.html) . This task also involves connecting to the mysql server.~~


## Database Tables Needed

---

- Tables needed: Portfolio - stockSymbol, quantity, price
- Tables needed: Wallet - value


## API Endpoints needed

---

- GET http://localhost:3000/api/v1/stocks/search/:symbol
- POST http://localhost:3000/api/v1/stocks  {stockSymbol: "AAPL", quantity: 100, price: 50}
- DELETE http://localhost:3000/api/v1/stocks/45
