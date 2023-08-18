## Install

`pnpm install`

## Run all the dev scripts

`pnpm -r dev`

## Run the application one application at a time

`pnpm --filter next-app-1 build`

## Version core-ui-test package

used changeset to version core-ui-test package so that we can use different versions of core.
Note: the core-ui-test package version must be published before use in the applications.

`npx changeset init`
`npx changeset`
`npx changeset status --verbose`
`npx changeset version`
`npx changeset publish`

see (here)[https://pnpm.io/using-changesets] for more information about the changeset
