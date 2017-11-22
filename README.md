# docker-gae-java

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy a project to [Google App Engine](https://appengine.google.com/). Currently being used with [wercker](https://app.wercker.com), but should meet the requirements for most CI systems.

## Details

### Base Image

* [maven:3-jdk-7](https://hub.docker.com/_/maven/) - Maven 3 and JDK 7

### Additional Node Modules

* [Google App Engine Java SDK](https://cloud.google.com/appengine/downloads) - Google APp Engine SDK. Required to deploy to Firebase.
