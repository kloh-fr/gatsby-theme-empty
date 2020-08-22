# Gatsby Theme Empty

_Fill me up with awesome!_

Zero config.
Quick Start.
Ultra-minimalist.
Opinion free.

## Prerequisites

The following software should already be installed on your local dev environment.

- Gatsby CLI
- NPM (with account and logged in)
- Yarn

## Get Started

1. Click `Use This Template` and create a new repo for your project from this template.
1. `git clone` your project and open it in your code editor of choice
1. Find and replace `empty` with your theme's new name. For example if your theme name was going to be `gatsby-theme-kickoff` you would find and replace `empty` -> `kickoff`.
1. Run `yarn install` to setup yarn workspaces
1. Run `lerna init` to initialize Lerna
1. Run `yarn develop:kickoff` to ensure it is building
1. Create something amazing.
1. Commit your changes to Git.
1. Run `lerna publish` and share it with the world on NPM.
1. Log in to Netlify, point it at the Git repo and launch it! It will automatically build and deploy the starter.

## Commands

The syntax for yarn workspaces is long and the following scripts are setup to make it easier to run commands in your starter.

**yarn develop:theme-name**: Runs `gatsby develop` on your starter.
**yarn build:theme-name**: Runs `gatsby build` on your starter.
**yarn serve:theme-name**: Runs `gatsby serve` on your starter.
**yarn clean:theme-name**: Runs `gatsby clean` on your starter.
**yarn test:theme-name**: Uses start-server-and-run to start and Gatsby develop server and then open Cypress.io for running tests.

## What's included

- An ultra-minimalist theme and starter that include the following dependencies:
  - Gatsby, React, React-Dom, Prettier
- Cypress.io with a basic smoke test and an accessibility audit test. Run `yarn test:theme-name`.
- Lerna preconfigured to manage publishing packages to NPM.
- GitHub action for CI to run a smoke test on every pull request and push to the main branch. You can use this as a starting point to expand your end-to-end testing.
- Dependabot to manage any outdated dependencies.
- Netlify config to automatically build and deploy the included starter

## What's next

Depending on how you want to use this monorepo you may also want to add a GitHub action to publish your starters to their own repo. Check out [actions-push-subdirectory](https://github.com/johno/actions-push-subdirectories).
