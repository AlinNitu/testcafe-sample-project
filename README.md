# Testcafe project

In order to run this project you will need to install *node.js*, *npm*, *testcafe* and an *IDE* of your preference.

Before running the test, go to the *properties* file and replace the values of the fields *validEmail* and *validPassword* with your valid account credentials. 

The tests can be run from the terminal as follows:

a. run an individual test with the command: **testcafe browser testFile**.
  In this case it will be **testcafe chrome test-collection/login.spec.ts** or **testcafe chrome, safari test-collection/upload.spec.ts**;

b. run the entire suite with the command **npm test**;
The suite is configured to run on chrome but you can edit or add more browsers in *testcafe.config.js*;

### !!! the website it was created for is not available anymore. This can be easily adapted for other websites by updating the base url, credentials and the page elements selectors
