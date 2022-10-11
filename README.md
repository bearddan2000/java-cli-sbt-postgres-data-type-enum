# java-cli-sbt-postgres-data-type-enum

## Description
Creates a small database table
called `dog`. Uses an enum user defined type.

## Tech stack
- java
- sbt
  - log4j
  - postgres driver

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10
- postgres:alpine

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`
