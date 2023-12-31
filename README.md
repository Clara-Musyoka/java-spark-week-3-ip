[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
# forest-animal-tracker

An application that allows Rangers to track wildlife sightings in a forest.

# Demo
See the live http://localhost:5000/


## Table of Contents
- [Author](#author)
- [Background](#background)
- [Technologies used](#technologies-used)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Author

Clara Musenya

## Background
The Forest Service is considering a proposal from a timber company to clearcut a nearby forest of Douglas Fir.  Before this proposal may be approved, they must complete an environmental impact study.  
This application allows Rangers to track wildlife sightings in the area.
## Installation
1. Have [Java](https://sdkman.io/) installed.
2. Gradle is used as the build tool.
3. Postgresql
```
$ psql
```
Production database database
```
=# CREATE DATABASE wildlife_tracker;
```
Development Database
```
=# CREATE DATABASE wildlife_tracker_test;
```
Connect to database
```
=#\c wildlife_tracker
```
Create tables
```
=# CREATE TABLE sightings (id serial PRIMARY KEY, name varchar, type varchar, location varchar, rangerName varchar); 
```
```
=# CREATE TABLE animals (id serial PRIMARY KEY, name varchar, type varchar, age int, health varchar, location varchar, rangerName varchar); 
```
## TECHNOLOGIES USED
- java
- java spark
- handlebars java
- gradle compiler

## Contributing

PRs accepted.

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT License:Copyright (c) 2022 Clara Musyoka
