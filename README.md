# Alfresco Postman tests

> Ce projet contient des exemples de tests postman pour ALfresco ACS 5.2+

## Prérequis

Avoir installé [Newman](https://www.npmjs.com/package/newman)

`npm install -g newman`

## Utilisation

`newman run ./tests\ alfresco.postman_collection.json -e tests\ alfresco\ centos1.home.postman_environment.json`

