# api-gateway service
The tenant-service for getting a config file to APIs.

## Project Status
[![Build Status](https://travis-ci.com/speech4j/api-gateway.svg?branch=master)](https://travis-ci.com/speech4j/api-gateway)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=speech4j_api-gateway&metric=alert_status)](https://sonarcloud.io/dashboard?id=speech4j_api-gateway)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=speech4j_api-gateway&metric=coverage)](https://sonarcloud.io/dashboard?id=speech4j_api-gateway)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=speech4j_api-gateway&metric=sqale_index)](https://sonarcloud.io/dashboard?id=speech4j_api-gateway)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=speech4j_api-gateway&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=speech4j_api-gateway)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=speech4j_api-gateway&metric=ncloc)](https://sonarcloud.io/dashboard?id=speech4j_api-gateway)


## Requirements

* Java 11
* Docker

## Building Instructions
 * `./gradlew package` -- create executable jar
 * `./gradlew clean build` -- build the project

## Testing Instructions
(If running from windows - replace / to \ )
 * `./gradlew clean test` -- build and run the tests.
