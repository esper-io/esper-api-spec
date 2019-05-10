# Esper Manage OpenAPI Specification
[![Build Status](https://travis-ci.com/esper-io/esper-api-spec.svg?branch=master)](https://travis-ci.com/esper-io/esper-api-spec)

## Links

- [API documentation (ReDoc)](https://esper-io.github.io/esper-api-spec/)
- OpenAPI Specification file: [JSON](https://esper-io.github.io/esper-api-spec/openapi.json) [YAML](https://esper-io.github.io/esper-api-spec/openapi.yaml)

## Instructions of updating specification

### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
