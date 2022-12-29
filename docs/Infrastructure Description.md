# **Infrastructure Description**

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


