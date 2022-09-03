# Jenkins
Dockerfile and configuration for a jenkins service running in AWS on fargate

The basis for the configuration used here is taken from [here](https://github.com/aws-samples/serverless-jenkins-on-aws-fargate)

## Local testing

Start a local jenkins instance
```sh
$ docker build -t jenkins .
$ docker run -p 127.0.0.1:8080:8080 jenkins
```
and go to localhost:8080 in your browser
