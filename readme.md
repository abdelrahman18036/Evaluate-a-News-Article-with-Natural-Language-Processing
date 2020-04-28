# News Article NLP

This frontend application uses Aylien NLP service to analyze text and article links.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes. See deployment for notes on how to deploy the project on a live system.


## Run project
Below shows how to run in development and production mode.
### run in development mode
To start the webpack dev server at port 8080
`  npm install`
`  npm run build-dev`

### run in production mode
Generate the dist files and then start server at port 3000

`  npm run build-prod`

`  npm run start`

## Configs
Here, we have two webpack config files for both development mode(`webpack.config.dev.js`) and production mode(`webpack.config.prod.js` )

We also have a `package.json` to manage dependencies


## API

The project uses the Text Analysis SDKs from , which provides a powerful and flexible AI-driven content analysis solutions.

## Offline Functionality
The project have service workers set up in webpack to provide the offline functionality of our app. When the service worker is functioning correctly, you will see the below message when you inspect the browser.


## Testing

Testing is done with Jest. To run test, use the command 

`npm run test`. 



## Authors

* [Abdelrahman Abdelnasser Gamal]


