# Agenda APP

This project uses Docker Compose to orchestrate the containers for an Angular application and a .NET API.

## Prerequisites

- Docker: Make sure you have Docker installed on your machine.

## Setup

### Usage image local

1. Open a terminal and navigate to the root directory

2. Run the following command to build and run the containers:

```docker-compose up```

This will build the images and run the containers for the Angular application and the .NET API.

### Usage image Docker Hub

1. Open a terminal and navigate to the root directory of your project.

2. Run the following command to build and run the containers:

```docker-compose -f docker-compose-remote.yml up```

This will build the images and run the containers for the Angular application and the .NET API.

-----

Access the Angular application in your web browser using the following URL:

http://localhost:3000

This will open the Angular application in your browser.

Use the .NET API by accessing the following URL:

http://localhost:7042

Here, you can make requests to the API.

## Contributors
- Franco Re
- Elio Tombolesi
- Juan Ignacio Queral
- Manuel Gainza Alvarez

