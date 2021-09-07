# test-appsvc

[![Build and deploy container app to Azure Web App - fw-test-appsvc-1](https://github.com/friarswood/test-appsvc/actions/workflows/master_fw-test-appsvc-1.yml/badge.svg)](https://github.com/friarswood/test-appsvc/actions/workflows/master_fw-test-appsvc-1.yml)


docker/azure app service example, using flask and [open API](https://swagger.io/specification/) (f.k.a. swagger).

integration with AppInsights:
- if instrumentation key is defined, logging will redirect to app insights
- log traces can be viewed using the search link in overview

The github workflow:

- builds and tests container
- pushes to container repo
- deploys to azure
