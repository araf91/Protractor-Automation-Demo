Tutorial
This is a simple tutorial that shows you how to set up Protractor and start running tests.

Prerequisites
Protractor is a Node.js program. To run, you will need to have Node.js installed. You will download Protractor package using npm, which comes with Node.js. Check the version of Node.js you have by running node --version. Then, check the compatibility notes in the Protractor README to make sure your version of Node.js is compatible with Protractor.

By default, Protractor uses the Jasmine test framework for its testing interface. This tutorial assumes some familiarity with Jasmine, and we will use version 2.4.

This tutorial will set up a test using a local standalone Selenium Server to control browsers. You will need to have the Java Development Kit (JDK) installed to run the standalone Selenium Server. Check this by running java -version from the command line.

Setup
Use npm to install Protractor globally with:

npm install -g protractor
This will install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working.

The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:

webdriver-manager update
Now start up a server with:

webdriver-manager start
