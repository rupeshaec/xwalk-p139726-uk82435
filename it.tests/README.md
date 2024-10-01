# Integration Tests

This module contains integration tests. These tests will be run in an AEM as a Cloud Service environment as part of the CI/CD pipeline when moving from Stage to Production.

## Run Tests locally

To execute the integration tests locally use the following command:

```
mvn clean verify -Plocal
```

The following values are used for the local testing:

* Author: localhost:4502
* Publish: localhost:4503

## To try
https://github.com/adobe/aem-test-samples/tree/aem-cloud/cf-smoke
https://github.com/adobe/aem-test-samples/tree/aem-cloud/wcm-smoke
https://github.com/adobe/aem-test-samples/tree/aem-cloud/xf-smoke
https://github.com/joerghoh/integrationtests/tree/main/it.tests/src/main/java/integrationtests/it/tests
https://github.com/adobe/aem-testing-clients/tree/aem-cloud/src/test/java/com/adobe/cq/testing/client
https://github.com/adobe/aem-testing-clients/tree/aem-cloud/src/test/java/com/adobe/cq/testing/junit/rules/logfile
https://github.com/adobe/aem-testing-clients/tree/aem-cloud/src/test/java/com/adobe/cq/testing/junit/rules/toggles

https://github.com/adobe/aem-test-samples/tree/aem-cloud/ui-cypress
https://github.com/adobe/aem-test-samples/tree/aem-cloud/ui-selenium-webdriver
