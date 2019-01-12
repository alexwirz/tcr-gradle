This is a template for practicing `test && commit || revert` as described in https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864

`gradle tcr` will build the project run the tests and commit when the test task succeeds.
It will revert all changes when tests fail. 