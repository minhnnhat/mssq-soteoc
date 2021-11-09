# This project provisioning mssql, sonarqube, teamcity, octopus.

## Requirements
- Docker installed
- Docker-compose

## How to start
- docker-compose up

#### Note:
- For Teamcity service, it need to process manually
  - Get token from teamcity container
  - Access to localhost:8112 with the above token
  - Then click the process button to complete the installation