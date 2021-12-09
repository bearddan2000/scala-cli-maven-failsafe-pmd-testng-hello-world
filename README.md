# scala-cli-maven-failsafe-pmd-testng-hello-world

## Description
A POC for maven app using testng
framework with failsafe and PMD plugins.

## Tech stack
- scala
- maven
  - testng
  - failsafe
  - PMD

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
- [PMD example](https://github.com/eugenp/tutorials/blob/master/static-analysis/src/main/resources/logback.xml)
