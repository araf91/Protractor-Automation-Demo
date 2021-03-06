This automation demo repo shows you how to set up Protractor and start running tests. It also includes a simple test for an AngularJS application. Check the ``` conf.js ``` and ``` spec.js ``` file in the e2e folder for more information.

**Prerequisites**

Protractor is a Node.js program. To run, you will need to have Node.js installed. You will download Protractor package using npm, which comes with Node.js. Check the version of Node.js you have by running ``` node --version ``` . Then, check the [compatibility notes](https://github.com/angular/protractor#compatibility) in the Protractor README to make sure your version of Node.js is compatible with Protractor.

You will need to have the [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html) installed to run the standalone Selenium Server. Check this by running java -version from the command line.

**Setup**

Use npm to install Protractor globally with:
``` npm install -g protractor ```

This will install two command line tools, protractor and webdriver-manager. Try running ``` protractor --version ``` to make sure it's working.

The webdriver-manager is aw helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:

``` webdriver-manager update ```

Now start up a server with:

``` webdriver-manager start ```
