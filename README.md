# Aloha from the Cloud! 🌺🌴

This project is a test cloud application that showcases the integration of different technologies such as React, Spring Boot, Postgres and Terraform. We'll be using GCP as our cloud provider 🌩️

## 🌴 Project Structure

- **Frontend**: The frontend is built using React, and it's located in the `client` folder.
- **Backend**: The backend is built using Spring Boot, and it's located in the `server` folder.
- **Database**: We're using Postgres as our database and it's configured on GCP.
- **Infrastructure**: We're using Terraform to provision and manage our resources on GCP and it's located in the `infrastructure` folder.

## 🌺 Configurations

- **Frontend**: The frontend configurations are located in the `client/src/config` folder.
- **Backend**: The backend configurations are located in the `server/src/main/resources` folder.
- **Database**: The database configurations are located in the `server/src/main/resources/application.properties` file.
- **Infrastructure**: The infrastructure configurations are located in the `infrastructure` folder.

## 🌊 Usage

- **Frontend**: To run the frontend, navigate to the `client` folder and run `npm start`.
- **Backend**: To run the backend, navigate to the `server` folder and run `./mvnw spring-boot:run`.
- **Database**: To connect to the database, you'll need to use the credentials provided in the `server/src/main/resources/application.properties` file.
- **Infrastructure**: To provision the infrastructure, navigate to the `infrastructure` folder and run `terraform init`, then `terraform apply`.

## 🌴 Deployment

- **Frontend**: The frontend is deployed on GCP using App Engine.
- **Backend**: The backend is deployed on GCP using App Engine.
- **Database**: The database is deployed on GCP using Cloud SQL.
- **Infrastructure**: The infrastructure is deployed on GCP using Terraform.

## Mahalo for checking out our project! 🌺🌴

Hope you find it as fun and interesting as we did building it!
