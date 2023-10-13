# Infrastructure Description

## Services Needed

    - AWS RDS: Postgres
    - AWS S3: Hosting the frontend
    - AWS Elatic Beanstalk: Node.js application
    - Angular
    - Node.js
    - Circle CI: Build pipelines for the application

## Instructions
    1. Install all the dependencies locally and test the application flow
    2. Built the api and frontend modules
    3. Make the necessary changes in .circleci/config.yml and bin/deploy files
    4. Make sure to create the AWS RDS, S3 bucket and EB App and Environment before deploying
    5. Configure the CircleCI environment and application
    6. Commit all the changes and push them to Git, and monitor the pipeline on CircleCI.