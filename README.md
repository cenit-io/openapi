# Cenit IO OpenAPI Specification
[![Build Status](https://travis-ci.org/cenit-io/openapi.svg?branch=master)](https://travis-ci.org/cenit-io/openapi)

Cenit IO (https://cenit.io) is an Open Platform for Data and Business Integration (iPaaS) to process, storage and move data in connection with Cloud or On-Premise services. It has been designed to orchestrate data flows that may involve several kind of endpoints (APIs, Datasets, EDI). It makes possible the automation of all operational processes in a company, connecting between organization's on-premises infrastructure and cloud provider services.

It allows the creation of custom data pipelines for process, storage and data movement between APIs –either cloud or on premises-. The flows could be trigger by data events or be scheduled.

## Links

- Documentation(ReDoc): https://cenit-io.github.io/openapi/
- SwaggerUI: https://cenit-io.github.io/openapi/swagger-ui/
- Look full spec:
    + JSON https://cenit-io.github.io/openapi/swagger.json
    + YAML https://cenit-io.github.io/openapi/swagger.yaml
- Preview spec version for branch `[branch]`: https://cenit-io.github.io/openapi/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://cenit-io.github.io/openapi/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:
