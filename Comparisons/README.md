# Comparison Metrics

## Dockerized Blob vs Functions Blob binding on container

1. This repository compares the dockerized version generated by this code and PUFunctionsOnACI folder which runs functions on ACI with a Docker file that includes the functions worker

### Observations

Containerized Docker with Functions Image Size: `2.14 GB` (includes azure functions worker)

Containerized Docker without Functions: `1.32 GB`