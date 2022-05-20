# Micro Frontend Demo

A sample repo for demoing a micro frontend architecture setup.

## Getting started

1. Run: `yarn start`
2. Navigate to `http://localhost:9001/`

Main Host App: `http://localhost:9001/`
Products Remote: `http://localhost:9002/`
Cart Remote: `http://localhost:9003/`

## Architecture

TBD

- Dynamic remote URLs
- Deployment
- Sharing state from host to application (props)
- Sharing global state from host to remotes (zustand?)
- Sharing local storage (persist cart)
- Central analytics event stream
- Error Boundary/Safe loading. + Suspense in 'FederatedWrapper'
- Versioning between host and remotes
- Versioning node_modules?

## Tech Stack

- [Turborepo](https://turborepo.org/)
- React
- Typescript
- Webpack v5 (w/ Module Federation)

## Scripts

- `yarn turbo run start`
