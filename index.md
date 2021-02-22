# Frontend Software Development / Medical Device R&D
I worked in medical device R&D for three years and successfully launched a cardiovascular implant that saves lives. However, the medtech industry was falling behing in adopting new technologies so I decided to take it upon myself to pivot and take up a tech stack so that I may take part in modernizing healthcare and medical devices from the tech side.

###Specializing JavaScript NERP stack: Node, Express, React, PostgresSQL

# GWG - eCommerce Web App

[https://grizzly-winter-gear.herokuapp.com/login](https://grizzly-winter-gear.herokuapp.com/login)

[https://github.com/grizzly-winter-gear/GWG](https://github.com/grizzly-winter-gear/GWG)

### NERP Stack (Node.js, Express.js, React.js, PostgreSQL)
### Front End
- Front end utilizes React and Material UI for interface, Redux for store management, React Router for page management
- User authorization is persisted with local storage use of JWT Token
- User can log in via GitHub OAuth2 API
- Cart is persistent for a user across browsers, phones
- Stripe API used for epayment and checkout process

### Back End
- Back end utilizes Express for RESTful API, Sequelize for ORM with PostgreSQL database
- User Authorization via JWT in header authorization tokens
- Passwords encrypted with bcrypt

### Deployment
- Deployed on Heroku with postgres db and secret keys for OAuth, Stripe, JWT
