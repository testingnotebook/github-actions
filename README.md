# github-actions

## Purpose of Repo

Supporting repo for the post at https://testingnotebook.com/running-tests-on-github-workflows/. Please view there for the prerequisites and instructions.

## Install and Run Tests

To install dependencies run `npm i`

Run jest tests run `npm t`
Run test on Cypress locally run `npm run cypress:run`

## GitHub Workflows

See `.github/workflows/` for the YML files.

- Pull Request - jest tests will run
- Push to main branch - cypress tests will run
