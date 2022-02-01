# kotlin-cli-maven-spring-failsafe-findbugs-pmd-jacoco-cucumber-mockito-testng-hello-world

## Description
A POC for spring app using testng, cucumber, mockito,
jacoco, pmd, and findbugs framework with failsafe
and surefire plugins.

Findbugs and pmd analyze source code for
potential bugs.

This is a simple and trivial way to start:
  - kotlin
    - springframework
    - cucumber test runner for testng
  - cucumber
    - parameterized scenario
  - mockito
    - integration of testng
    - injection

## Tech stack
- kotlin
- maven
	- mockito
  - spring
  - testng
  - cucumber
  - failsafe
  - findbugs
  - pmd
  - jacoco

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
