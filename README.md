## Currency Exchange API – NodeJS

Objective:

* to expose API for consumption

CI/CD with Google Cloud Build and Cloud Run:

* builds docker image with Cloud Build
* pushes docker image into Container Registry
* deploys docker image to Cloud Run

Live endpoint available at: 

[https://gcp2-s4zqrwobhq-as.a.run.app](https://gcp2-s4zqrwobhq-as.a.run.app)

[https://gcp2-s4zqrwobhq-as.a.run.app/fx](https://gcp2-s4zqrwobhq-as.a.run.app/fx)

Pre-requisites:

* Google Cloud account
* GitHub account

You also need to enable the following APIs in Google Cloud:

* Cloud Run
* Cloud Build 

To run on localhost:
```
docker run -d -p 8080:8080 gcr.io/lateral-booking-317103/github.com/dawnhe-edx2021/nodejs-api

curl -i http://localhost:8080/fx
```
