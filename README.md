# My Docker Compose Project

This project uses Docker Compose to orchestrate the containers for an Angular application and a .NET API.

## Prerequisites

- Docker: Make sure you have Docker installed on your machine.

## Setup

- wip

## Usage

1. Open a terminal and navigate to the root directory of your project.

2. Run the following command to build and run the containers:

docker-compose up

This will build the images and run the containers for the Angular application and the .NET API.

3. Access the Angular application in your web browser using the following URL:

http://localhost:3000

This will open the Angular application in your browser.

4. Use the .NET API by accessing the following URL:

http://localhost:7042


Here, you can make requests to the API.

## Running EF Migrations

Before running the containers, you need to apply the Entity Framework (EF) migrations to set up the database. Follow these steps:

1. Open a terminal and navigate to the `AgendaApi/AgendaApi` directory.

2. Run the following command to apply the EF migrations:

dotnet ef database update

