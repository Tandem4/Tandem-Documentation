# Tandem-News

## News in perspective

Tandem News is a mobile news feed aggregator which presents current trending topics from popular news organizations. Articles are analyzed for sentiment/tone biases in order to provide a quick comparison of the ways in which various publications may cover the same topic under a different light.


# Table of Contents

- Getting started

- Architecture

- Technologies

- Team

- Contributing

<Screenshot>


# Getting started

The Tandem News Project is composed of five repos:

  1) Tandem-Crawler-Service
     Automated web crawlers for fetching news feed articles

  2) Tandem-Analysis
     Sentiment, Trend and Ranking Analysis for fetched articles

  3) Tandem-DB
     Persistent storage for Tandem-API-Server

  4) Tandem-Public-API
     API server for mobile client

  5) Tandem-Views
     React Native mobile client for iOS

Please see the individual repos for further information.


## Screenshots

  ![Screenshots](https://raw.githubusercontent.com/NCSkoglund/Tandem-Analysis/upstream/images/tandem_screenshots.png)

## Site Architecture

  ![Site Architecture](https://raw.githubusercontent.com/NCSkoglund/Tandem-Analysis/a80f9271e9ed9ac5420a1f65d5b2864537a2e497/images/Tandem_Architecture.png)
  
## Sequence Diagram 
 
   ![Sequence Diagram](https://raw.githubusercontent.com/NCSkoglund/Tandem-Analysis/merge-harmony/images/sequence_diagram.png) 

## Schema Diagram

  ![Schema Diagram](https://raw.githubusercontent.com/Tandem4/Tandem-Analysis/master/images/DB_schema.png)


# Technologies

## Front end:

- React Native

- Redux

## Back end:

- Node

- Express

- Bookshelf/Knex

- MySQL

- MongoDB

- Redis

- Pug

## Testing:

- Mocha

- Chai

- Mock-Knex

## Continuous Integration:

- Travis CI

## Deployment:

- EC2

- PM2

- Digital Ocean


# Tandem Team

Product Owner : Asifuzzaman Ahmed

Scrum Master : Nicole Skoglund

Development Team : Asifuzzaman Ahmed, Nicole Skoglund, Brett Lensvelt, Kani Munidasa


# Contributing

See CONTRIBUTING.md for contribution guidelines.
