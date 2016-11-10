# TimeZynk OpenAPI Specification
[![Build Status](https://travis-ci.org/TimeZynk/timezynk-api-spec.svg?branch=master)](https://travis-ci.org/TimeZynk/timezynk-api-spec)

## Links

- Documentation(ReDoc): http://developer.timezynk.com/
- SwaggerUI: http://developer.timezynk.com/swagger-ui/
- Look full spec:
    + JSON http://developer.timezynk.com/swagger.json
    + YAML http://developer.timezynk.com/swagger.yaml
- Preview spec version for branch `[branch]`: http://developer.timezynk.com/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/) and [Yarn](https://yarnpkg.com/)
2. Clone repo and `cd`
    + Run `yarn install`

### Usage

1. Run `yarn run start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing http://developer.timezynk.com/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:
