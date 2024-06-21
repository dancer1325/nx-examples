# NxExample

This project was generated using [Nx](https://nx.dev).

<p align="center"><img src="https://raw.githubusercontent.com/nrwl/nx/master/nx-logo.png" width="450"></p>

🔎 **Powerful, Extensible Dev Tools**

## Quick Start & Documentation
* [Nx Documentation](https://nx.dev)
* [30-minute video showing all Nx features](https://nx.dev/getting-started/why-nx)

## Adding capabilities to your workspace
* Nx supports [many plugins / add capabilities](https://nx.dev/concepts/nx-plugins)
  * [React](https://reactjs.org)
    * `npm install --save-dev @nx/react`
  * Web (no framework frontends)
    * `npm install --save-dev @nx/web`
  * [Angular](https://angular.io)
    * `npm install --save-dev @nx/angular`
  * [Nest](https://nestjs.com)
    * `npm install --save-dev @nrwl/nest`
  * [Express](https://expressjs.com)
    * `npm install --save-dev @nrwl/express`
  * [Node](https://nodejs.org)
    * `npm install --save-dev @nrwl/node`

## Generate an application
* Via some plugin
  * _Example:_ `nx g @nx/react:app my-app`
* multiple applications & libraries / same workspace, can be created

## Generate a library
* Via some plugin
  * _Example:_ `nx g @nx/react:lib my-lib`
* are shareable
  * importing them -- _Example:_ `@nx-example/mylib` --
  * across
    * libraries &
    * applications

## Development server
* `nx serve my-app`
  * start dev server
    * Open in your desired browser, http://localhost:4200/
  * hot reload
    * == if you change any of the source files -> The app will automatically reload 

## Code scaffolding
* `nx g @nx/react:component my-component --project=my-app`
  * generate a new component

## Build
* `nx build my-app`
  * build the project
  * build artifacts
    * stored in `dist/`
  * `--prod`
    * allow production build

## Running unit tests
* `nx test my-app`
  * execute unit tests -- via -- [Jest](https://jestjs.io)
* `nx affected:test`
  * execute the unit tests / affected by a change

## Running end-to-end tests
* `nx e2e my-app`
  * execute the end-to-end tests -- via -- [Cypress](https://www.cypress.io)
* `nx affected:e2e`
  * execute the end-to-end tests / affected by a change

## Understand your workspace
* `nx dep-graph`
  * see a diagram of the dependencies of your projects
