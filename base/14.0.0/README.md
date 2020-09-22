<!-- WARNING: this file was autogenerated by generate-base-image.js -->
# cypress/base:14.0.0

A Docker image with all dependencies pre-installed.
Just add your NPM packages (including Cypress) and run the tests.
See [Cypress Docker docs](https://on.cypress.io/docker) and
[Cypress CI guide](https://on.cypress.io/ci).

## Example

Sample Dockerfile

```
FROM cypress/base:14.0.0
RUN npm install --save-dev cypress
RUN $(npm bin)/cypress verify
RUN $(npm bin)/cypress run
```

```
node version:    v14.0.0
npm version:     6.14.4
yarn version:    1.22.4
debian version:  10.3
user:            root
```