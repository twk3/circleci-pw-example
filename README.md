# Currents.dev - CircleCI Playwright Example

This is an example repository that showcases using [CircleCI](https://circleci.com) with [Currents.dev](https://currents.dev).

The example [config file](https://github.com/currents-dev/circleci-example/blob/master/.circleci/config.yml):

- uses [Test CLI commands](https://playwright.dev/docs/test-cli) to run `@currents/playwright` for recording test results and parallelization with [Currents.dev](https://currents.dev)

- Note: set the `CURRENTS_PROJECT_ID` [Environment variable](https://circleci.com/docs/2.0/env-vars/) - obtain the project id from [Currents.dev](https://app.currents.dev)

- Note: use CLI arguments to customize your Playwright runs, e.g.: `pwc --key <your Currents.dev key>`

- Note: create an organization, get your record key at [Currents.dev](https://app.currents.dev) and set [Environment variable](https://circleci.com/docs/2.0/env-vars/) `CURRENTS_RECORD_KEY`

---