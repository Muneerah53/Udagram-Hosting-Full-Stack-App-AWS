# Hosting a Full-Stack Application - Udagram

> This Project is for Udacity's Full Stack JavaScript Developer Nanodegree Program - Hosting a Full Stack Application.

S3 Endpoint - Frontend: http://myawsbucket-830992865201.s3-website-us-east-1.amazonaws.com

## Overview

The project application, **Udagram** - an Image Filtering application, allows users to register and log into a web client, and post photos to the feed. This application is to be hosted into **AWS** with Pipeline using **CircleCI**.

This application contains three main components:

1.  Frontend - Angular web application built with Ionic framework.
2.  Backend RESTful API - Node-Typescript application built with Express framework.
3.  Postgres Database

## Project Setup

To run this project locally, follow the following steps.

**Backend API**

1. Open a new terminal window and navigate to the project directory.
2. Navigate to the udagram-api folder, `cd udagram-api/`
3. Set environmental variables in a new `.env` file
4. Run `npm install`
5. Run `npm run start `

**Frontend App** 6. Open a new terminal window and navigate to the project directory. 7. Navigate to the udagram-api folder, `cd udagram-frontend/` 8. Run ` npm install -f` 9. Run `ionic build` 10. Run `ionic serve`

## Documentation

- **[Detailed Documation](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/)** of the project's dependencies, infrastructure, and pipelines.
- **[Screenshots](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/screenshots/)** showing of the last CircleCi build and an overview of each AWS console services (RDS, ElasticBeanstalk, S3)
- **[Diagrams](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/diagrams/)** of the AWS architecture and pipeline.

## License

[License](LICENSE.txt)
