## Sample test cases for AWS Pipeline WSO2IS

Sample product artifacts and and sample test cases for WSO2 Identity Server. This repository is used as the sample for artifacts repository in WSO2 AWS pipeline for WSO2IS..

* A sample scenario test suite implemented using Testng is in `tests/wso2is/` directory. This run a simple test to validate response code of a rest endpoint.

#### Add new test 
* Place the tests in `test/wso2is/` directory. Update the testng.xml file to include your test class.

#### Run test suites
* Use following command to run the tests,
```
mvn test -Dendpoint=<ENDPOINT>
```