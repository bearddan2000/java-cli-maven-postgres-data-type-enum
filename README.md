# java-cli-maven-postgres-data-type-enum

## Description
Creates a small database table
called `dog`. Uses an enum user defined type.

## Tech stack
- java
- maven
  - log4j
  - postgres driver

## Docker stack
- maven:3-openjdk-17
- postgres

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`
