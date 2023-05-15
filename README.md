# Installation

to install:
`npm install`

In order to swap between running the app on docker vs locally, you may need to run the following command:

`sudo chown -R $USER node_modules`

This is because once you run the dockerized version it may deny access, therfore you need to take ownership.

# Run

to run locally:
`npm run dev`

to run via docker:
`docker compose up`
