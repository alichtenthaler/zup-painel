# Participatory Urban Janitorial - Panel

## Introduction

It is known that information handling is crucial for an efficient management and that is why Participatory Urban Janitorial(or ZUP) features a full life historic of each of the assets and of municipal problems, incorporating citizens' requests, geo-referenced data, technical reports, photographs and preventive actions taken over time. This way, the system centralizes all the information, allowing authorities and field technicians to take rapid decisions.

this component of the Panel is responsible for the complete administrative management by the institution using the project. Other components are:

* Android and iOS application for citizens
* Web application for citizens
* Android application for inventory management
* API

## Installation

**NOTE:** This README teaches you how to deploy the project in a development environment. For information on how to deploy the project in production, see the [Installation Guide](http://docs.zup.ntxdev.com.br/site/installation_docker/).


To install ZUP Painel on your machine, you will need to install:

 - nvm >= 0.26.0
 - npm >= 2.7.0
 - Ruby >= 2.0.0

# Project setup

After cloning the repository, run the commands:

    cd zup-painel
    nvm install
    npm run setup

Create an `.env` file in the root of the project with the following content:

    SERVER_IP=127.0.0.1
    SERVER_PORT=9000
    API_URL=http://your-api.zupinstance.com
    MAP_LAT=-23.549671
    MAP_LNG=-46.6321713
    MAP_ZOOM=11
    DEFAULT_CITY="São Bernado do Campo"
    DEFAULT_STATE=SP
    DEFAULT_COUNTRY=Brasil

To run the tests, you will also need to setup the following variables:

    SERVER_PORT=9001
    USER_EMAIL=teste.zup@gmail.com
    USER_PASSWORD=123456

Modify `API_URL` to point to your instance of ZUP API. `MAP`'s `LAT` and `LNG` are used to centralize the maps to their initial positions. The `DEFAULT_CITY`, `DEFAULT_STATE` and `DEFAULT_COUNTRY` variables define the standard geographical information.

If you require access via VM, you must change the `SERVER_IP` to the IP `0.0.0.0`.

# Build for production

    npm run prod-build

The `dist` directory will contain all of the _assets_ for deploying in production.

# Server for development

    npm run dev-server

# Running tests

    npm run test
