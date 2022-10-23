# Serverless TODO Application

This is a simple TODO application using AWS Lambda and Serverless framework.

# Functionality of the application

This application will allow creating/removing/updating/fetching TODO items. Each TODO item can optionally have an attachment image. Each user only has access to TODO items that he/she has created.
# How to run the application

## Backend

To deploy an application run the following commands:

`cd backend`

`sls deploy -v`

## Frontend

To run a client application first edit the client/src/config.ts file to set correct parameters. And then run the following commands:

`cd client`

`npm install`

`npm run start`

This should start a development server with the React application that will interact with the serverless TODO application.
