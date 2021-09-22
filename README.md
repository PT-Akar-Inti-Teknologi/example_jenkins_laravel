# Laravel Jenkins Example

Sample project to demonstrate how to use Jenkins & SonarQube in Laravel.

## Table of Contents

-   [General Information](#general-information)
-   [Technologies Used](#technologies-used)
-   [Setup](#setup)

## General Information

-   This sample project uses Jenkins' built in tools to build and test a typical Laravel project
-   Please see `Jenkinsfile` and `sonar-project.properties` as a reference

## Technologies Used

-   Laravel 8
-   PHPUnit 9
-   PHPCodeSniffer

## Setup

### Development

-   `composer install`
-   `cp .env.example .env`
-   `php artisan key:generate`

### Test

-   `./vendor/bin/phpunit`
