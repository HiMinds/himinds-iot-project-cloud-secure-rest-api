# himinds-iot-project-cloud-secure-rest-api

If you need a convenient way of creating a secure REST-API for test purposes, Express.js is a great match. 

Express.js is the most popular web framework for Node apps. Together with Node.js body parsing middleware body-parser which simplifies the handling of incoming request bodies it is easy to create a REST-API.

We use curl to test the API:


```
curl -k -i -H  "Accept: application/json" "https://localhost:8080/api"

```


```
curl -k -i -H  "Accept: application/json" "https://localhost:8080/api/timestamp"

```


We are using the self-signed certificates we created [here](https://github.com/HiMinds/himinds-iot-project-general-self-signed-certificate).
