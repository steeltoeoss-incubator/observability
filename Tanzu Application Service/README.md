# Steeltoe with Tanzu Applcation Service

This is a something remember under the covers TAS is using Cloud Foundry

## Getting Started

A summary of actions:
  1. Create a sample .NET app
  1. Add in all needed middleware and configs to app
  1. Deploy using docker-compose
  1. Open the platform's dashboard to see everything

### Creating the app

#### Using Initializr UI

  1. Head over to [https://start.steeltoe.io](https://start.steeltoe.io) 
  1. Create a project with the following:
    *Latest Steeltoe version*
    *Latest netcore version*
    *Dependencies:* Actuators, Logging
  1. Extract the zip
  1. Open the project in your IDE of choice
 
#### Using Initializr CURL

  1. Open a terminal a run:
    ```bash
    $ curl https://start.steeltoe.io/start.zip XXXXXX
    ```
  1. Extract the zip
  1. Open the project in your IDE of choice

### Adding needed middleware and configs to app

### Deploy with docker-compose

### Viewing the dashboard in Wavefront

