# ts-template

A template for typescript projects and sites.

Features:

* pnpm workspaces
  * directory hierarchy for react, vue, typescript packages, etc.
* enforce pnpm as the package manager
* enforce node versions

# Uses

## Package Manager

[`pnpm`](https://pnpm.io/) as the package manager.

## Workspaces

[`pnpm workspaces`](https://pnpm.io/workspaces) are used.

## Node

[`Node`](https://nodejs.org/en) versions can be managed via the `.nvmrc` file. Create a different `.nvmrc` file for each package as needed. Run `nvm use` within a given directory to change the node version.

TODO: Setup ability to auto use a version.

## Typescript

This template is for [`typescript`](https://www.typescriptlang.org/) so `typescript` is added as a dev dependency in the root package.json.
