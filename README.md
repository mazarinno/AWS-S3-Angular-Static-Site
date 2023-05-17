# AWS-S3-Angular-Static-Site

This AWS S3 Angular Static Site was a project for SNHU CS470 built on top of forks from these two repositories:

https://github.com/mazarinno/learn-angular-from-scratch-step-by-step

https://github.com/mazarinno/learn-how-to-build-a-mean-stack-application

The Angular Site created in this project hosts a MongoDB database of questions and answers about Angular. Users can create new questions and/or answers and vote on answers given. Each folder contains photo documentation of the creation of this site using Docker and various AWS tools. A detailed list of the contents is here below: 

1 - Docker Containerization

This folder contains both dockerfiles for the front and backend containers. It also has screenshots of the Docker image output and the Angular and LoopBack explorer frontends running in the container. 

1.5 - Docker Compose and Orchestration

The Docker Compose and Orchestration folder contains the Docker Compose YAML file to merge the two containers made previously. The screenshots show the Docker Compose creation, adding a new question to the LoopBack and Angular frontends, the questions in MongoDB, and the Docker ps -a command output. 

2 - Creating a Static Site on S3 

These screenshots show the S3 configured as a server, the permissions of the bucket's settings allowing public access, and the S3 bucket showing the Angular files. The policy JSON is also within this folder.

3 - Lambda and Gateway API

Here is a documentation of practice with Lambda functions before many more are created in the final folder. These screenshots show the first serverless compute function, execution results, test event EchoWithQuery and its execution results, and the source code for index.js. 

3.5 - Testing Lambda and Gateway API

This portion included the creation of the API method to the Lambdas, using the stage editor for deployment, and using the API method test console to test it. The screenshots include the GET method execution page and test page and the browser running the URL. 

4 - Creaitng and Using the Database

Here, the Mongo models were repointed to use DynamoDB for its single-table design. Then, the Lambda functions to access the database with CRUD operations were created. The CSV files for the questions and answers are included along with screenshots of many test runs for the Lambdas. 
