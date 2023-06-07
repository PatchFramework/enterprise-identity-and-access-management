# enterprise-identity-and-access-management
This is a proof of concept to demonstrate how an enterprise identity and access management could be setup. Project by Marvin Welzbacher &amp; Dominic Viola (DHBW CAS)

## 0 Prerequisits
1. Docker
1. Docker Compose

## 1 Setup
For Production use cases change the environment variables for the usernames and passwords.
Best practice is to use the --env-file keyword when building the containers with docker compose and putting the .env file that contains the values into the .gitignore.

## 2 Build & Run
Run the following commands to build and run all the containers in the architecture

```bash
docker-compose build
docker-compose up
```

