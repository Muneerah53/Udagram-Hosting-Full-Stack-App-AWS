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

## Screenshots

- ### Homepage
![1](https://user-images.githubusercontent.com/90178514/209948987-b943c0bc-9df8-45c4-8380-f7aae1eb4bd7.jpg)

- ### Register
![2](https://user-images.githubusercontent.com/90178514/209948988-0817f38e-48db-4ade-a87c-9912cc6f0f8f.jpg)
- ### Logged in
![3](https://user-images.githubusercontent.com/90178514/209948992-95ab5867-9219-444c-84f1-a4b1656259de.jpg)
- ### Create Post
![4](https://user-images.githubusercontent.com/90178514/209948995-7a6a265f-14d6-48f9-ab1e-e897509266b0.jpg)
- ### Added Post
![5](https://user-images.githubusercontent.com/90178514/209948980-b4e55dab-9a79-41d8-bf4c-215b36d40742.jpg)

## Documentation

- **[Detailed Documation](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/Documentation.md)** of the project's dependencies, infrastructure, and pipelines.
- **[Screenshots](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/screenshots/)** showing of the last CircleCi build and an overview of each AWS console services (RDS, ElasticBeanstalk, S3)
- **[Diagrams](https://github.com/Muneerah53/Udagram-Hosting-Full-Stack-App-AWS/blob/master/docs/diagrams/)** of the AWS architecture and pipeline.

## License

[License](LICENSE.txt)
