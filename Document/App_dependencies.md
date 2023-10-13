## Application Dependencies

### FrontEnd
    - Application is built using Angular framework
    - Firstly, you need to install the node_modules using `npm run frontend:install` or you navigate to directory 'udagram-frontend' and run the command `npm install`.
    - To start the application use `npm run start` or `ng serve`
    - If you have installed Angular of version > 8 then use `set NODE_OPTIONS=--openssl-legacy-provider && npm run start`

> **Technologies:** *Angular v8, Iconic, rxjs*

### Backend API
    - API is built using Node.js version 14.15 and Express.js
    - Postgres SQL database is used to persist data
    - Firstly install the node_modules using `npm run api:install` or you navigate to directory 'udagram-api' and run the command `npm install`.
    - Create a .env file and configure the environment variables. If you are using any CI/CD platform, you should set up environment variables in the .env file in a similar manner.Furthermore, the script for initializing the environment or setting environment variables using AWS Elastic Beanstalk service is also available in the ./bin/deploy.sh directory, you navigate to directory 'udagram-api' and run the command `npm run deploy`.
    - To start the server use the `npm run start:dev` command locally

> **Technologies:** *Node.js, ExpressJS, Postgres, dotenv, sequelize, bcrypt*

#### .env File Reference
```
POSTGRES_HOST = <Endpoint of RDS>
POSTGRES_DB = postgres
POSTGRES_USERNAME = postgres
POSTGRES_PASSWORD = <db password>
PORT = 8080
AWS_REGION = <region>
AWS_PROFILE = default
AWS_BUCKET = <bucket name>
AWS_ACCESS_KEY_ID = <key>
AWS_SECRET_ACCESS_KEY = <key>
JWT_SECRET = mysecretstring
URL = http://localhost:8100/
```