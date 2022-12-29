# Detailed Documentation

This document gives a detailed description of the project's dependencies, infrastructure, and pipelines.

## Application dependencies

To run the project locally, the following tools must be installed:

- [Git](https://git-scm.com/downloads)
- [PostgreSQL](https://www.postgresql.org/download/)
- [NodeJS](https://nodejs.org/en/download/releases/)
- [Ionic command-line utility v6](https://ionicframework.com/docs/installation/cli)
- [AWS CLI v2](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- [EB CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html)
- A RDS database
- A S3 bucket

## **Infrastructure Description**

- ### AWS RDS

  The project is built on a PostgreSQL database created in AWS RDS. This is used by the project to store user metadata, such as user credentials.

  Endpoint: mydbinstance.ctgpf3v9rwfw.us-east-1.rds.amazonaws.com
  Port: 5432

- ### S3 bucket

  The project uses an AWS S3 bucket to host the frontend files.

 http://myawsbucket-830992865201.s3-website-us-east-1.amazonaws.com

- #### Elastic Beanstalk Environment

  EB is used for the backend API deployment

  http://udagram-api-env.eba-pm2vqxcz.us-east-1.elasticbeanstalk.com/

![diagram](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/diagrams/architecture%20diagram.jpg?raw=true)
_AWS architecture diagram_


## Pipeline Description

- `npm run frontend:install` : Install frontend app's dependencies.
- `npm run frontend:build` : Build the Angular Frontend app.
- `npm run frontend:deploy` : Deploy the project to S3.
- `npm run frontend:lint` : Linting the frontend app's source code to check for errors.
- `npm run api:install` : Install backend dependencies.
- `npm run api:build` : Build Backend.
- `npm run api:deploy` : Deploy backend to EB.
- ` npm run deploy` : Deploy both frontend and backend project.

![diagram](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/diagrams/pipeline%20diagram.jpg?raw=true)
_Pipeline diagram_
