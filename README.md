# About
Simple introduction to using K6 Performance testing

# API
Example API is https://test.k6.io/

# Concepts we will cover
* [Designing a Load test](https://k6.io/docs/testing-guides/api-load-testing/#different-types-of-api-load-testing)
* Setting up K6 to run a test.
* [Checks](https://k6.io/docs/using-k6/checks/)
* [VUs](https://k6.io/docs/getting-started/running-k6/#using-options)

# How to run
This example will run K6 via Docker. Make sure docker is installed on your machine.

The test files are stored the the `src` folder.

Running `npm test` in the command line will run the `src/example1.js` file via K6 docker.
