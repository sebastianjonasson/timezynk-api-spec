# Timezynk OpenAPI Specification
[![Build Status](https://travis-ci.org/TimeZynk/timezynk-api-spec.svg?branch=master)](https://travis-ci.org/TimeZynk/timezynk-api-spec)

## Links

- Documentation(ReDoc): https://developer.timezynk.com/
- SwaggerUI: https://developer.timezynk.com/swagger-ui/
- Look full spec:
    + JSON https://developer.timezynk.com/swagger.json
    + YAML https://developer.timezynk.com/swagger.yaml
- Preview spec version for branch `[branch]`: http://developer.timezynk.com/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
