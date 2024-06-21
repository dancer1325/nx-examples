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
  * across  -- _Example:_ Check 'cart' in the 'dep-graph' --
    * libraries &
    * applications

## Development server
* `nx serve SomeAppName` -- _Example:_ `nx serve products` --
  * start dev server
    * Open in your desired browser, http://localhost:4200/
  * hot reload
    * == if you change any of the source files -> The app will automatically reload 

## Code scaffolding
* `nx g @nx/react:component my-component --project=SomeProjectName`
  * generate a new component

## Build
* `nx build SomeProjectName`  -- _Example:_  `nx build products`--
  * build the project
  * build artifacts
    * stored in `dist/`
  * `--prod`
    * allow production build

## Running unit tests
* `nx test SomeProjectName` -- _Example:_ `nx test products` --
  * execute unit tests -- via -- [Jest](https://jestjs.io)
  * ⚠️NOT all projects have an test task configured ⚠️
    * Example:_ `nx test products-e2e`
* `nx affected:test`
  * execute the unit tests / affected by a change

## Running end-to-end tests
* `nx e2e SomeProjectName`  -- _Example:_ `nx e2e products-e2e` --
  * execute the end-to-end tests -- via -- [Cypress](https://www.cypress.io)
  * `nx show projects`
    * list the projects / exist in the current Nx workspace
  * ⚠️NOT all projects have an e2e task configured ⚠️
    * _Example:_ `nx e2e products`
* `nx affected:e2e`
  * execute the end-to-end tests / affected projects by a change

## Understand your workspace
* `npm install --force`
* `nx dep-graph`
  * see a diagram of the dependencies of your projects


## Get the tasks / project
* Display the available tasks / project
  * Solution: TODO: Command
  * Attempts:
    * Attempt1: `nx list target SomeProjectName`
    * Attempt2: `nx show project products`
