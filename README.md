# Node Skeleton

## Resource Wall

Created a Pinterest-style resource wall using RESTful conventions and HTTP routing. The front end was built with jQuery, Javascript, Flexbox, CSS, and Ajax while the back end included Node.js, Express, and Knex. The database used was PostgreSQL and the server side rendering was done through a EJS view engine. 

![](home.gif)
![](home2.gif)

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
6. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
7. Run the server: `npm run local`
8. Visit `http://localhost:8080/`

## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
