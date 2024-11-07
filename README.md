# Docker Compose Commands

```sh
# Validate Docker compose file
docker compose config
docker compose up -d
docker compose stop
```

# Steps 

## Step 1:
- Create 'front-tier' and 'back-tier' networks.

## Step 2::
- Create Volume 'db-data'.

## Step 3:
- Create 'healthchecks' folder and add 'postgres.sh' script. **Make sure the script has execute permissions.**
- Create Service 'db' and bring up Postgresql database.

## Step 4:
- Create 'healthchecks' folder and add 'postgres.sh' script.**Make sure the script has execute permissions.**
- Create Service 'redis' and bring up Redis database.

## Step 5:
- Create 'worker' directory and add the code.
- Update 'compose.yaml' with 'worker' configuration.

## Step 6:
- Create 'result' directory and add the code.
- Update 'compose.yaml' with 'result' configuration.
- Access the 'result' app on the browser with "http://localhost:8081"

## Step 7:
- Create 'vote' directory and add the code.
- Update 'compose.yaml' with 'vote' configuration.
- Access the 'vote' app on the browser with "http://localhost:8080"