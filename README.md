# MahdisEcommerceBackend

## My Task

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.
This application is the back end for an e-commerce site. It configures a working Express.js API to use Sequelize to interact with a MySQL database.

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Screenshot

The following animation shows the web application's appearance and functionality:

!["Demo".](./Assets/13-orm-homework-demo-01.gif)
!["Demo".](./Assets/13-orm-homework-demo-02.gif)
!["Demo".](./Assets/13-orm-homework-demo-03.gif)

## Setup

Make sure Node.js and MySQL are installed. Enter your password in the connection function in server.js. Next, Open the integrated terminal and run mysql -u root -p into the root folder and enter your password. Then run source ./db/query.sql, enter, then run source ./db/seeds.sql and enter. Then run quit. Finally, run npm seed then npm start. The output can be seen in the video by running Insomnia.

## Installation

Github repository:

https://github.com/mahdi83777/MahdisEcommerceBackend

Deployed video:

https://www.youtube.com/watch?v=i81bUv8lfJo

## References

[Node JS] (https://www.w3schools.com/nodejs/)
