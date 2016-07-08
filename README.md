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


# Architecture

<Architecture>

<Sequence Diagrams>


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

Development Team : Asifuzzaman Ahmed, Nicole Skoglund Brett Lensvelt, Kani Munidasa


# Contributing

See CONTRIBUTING.md for contribution guidelines.
