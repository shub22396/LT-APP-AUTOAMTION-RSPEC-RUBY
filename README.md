

*Learn how to use RSpec framework to configure and run your Java automation testing scripts on the LambdaTest platform*

[<img height="58" width="200" src="https://user-images.githubusercontent.com/70570645/171866795-52c11b49-0728-4229-b073-4b704209ddde.png">](https://accounts.lambdatest.com/register)

## Table of Contents

* [Pre-requisites](#pre-requisites)
* [Run Your First Test](#run-your-first-test)
* [Executing The Test](#executing-the-test)
* [Running the Parallel Tests Using RSpec Framework](#running-the-parallel-tests-using-rspec-framework)
* [Testing Locally Hosted or Privately Hosted Projects](#testing-locally-hosted-or-privately-hosted-projects)

## Pre-requisites

Before you can start performing Ruby automation testing with Selenium, you would need to:

* Install Ruby and gem on your local system. Follow these instructions to install on different operating systems.
  * For **Windows**, you can download from the [official website](https://rubyinstaller.org/downloads/).
  * For **Linux** or **Ubuntu**, you can run a simple apt command like below:
  ```bash
  sudo apt-get install ruby-full
  ```
  * For **macOS**, you can run a [Homebrew](https://brew.sh/) command like this:
  ```bash
  brew install ruby
  ```

* LambdaTest binary file for running tests on your locally hosted web pages.

### Installing Selenium Dependencies and Tutorial Repo


```bash
git clone https://github.com/LambdaTest/RSpec-Selenium-Sample.git
cd RSpec-Selenium-Sample
```
After navigating to the cloned directory, install project dependencies using the below commands:
```bash
bundle install
```
### Setting up Your Authentication
Make sure you have your LambdaTest credentials with you to run test automation scripts with Jest on LambdaTest Selenium Grid. You can obtain these credentials from the [LambdaTest Automation Dashboard](https://automation.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample) or through LambdaTest Profile.

Set LambdaTest Username and Access Key in environment variables.
 * For Linux/macOS:
 `export LT_USERNAME="YOUR_USERNAME" export LT_ACCESS_KEY="YOUR ACCESS KEY"`
 * For Windows:
 `set LT_USERNAME="YOUR_USERNAME" set LT_ACCESS_KEY="YOUR ACCESS KEY"`

## Run Your First Test

### Sample Test with RSpec Ruby

**Test Scenario:** The example mentioned in the [lambdatest.rb](https://github.com/shub22396/LT-APP-AUTOAMTION-RSPEC-RUBY.git) sample file would help you to execute your automation test using RSpec.

> You can generate capabilities for your test requirements with the help of our inbuilt **[Capabilities Generator tool](https://www.lambdatest.com/capabilities-generator/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)**.

## Executing The Test

Navigate to the directory where you cloned the sample of RSpec Ruby and run the following command.
```bash
bundle exec rake single
```
Your test results would be displayed on the test console (or command-line interface if you are using terminal/cmd) and on LambdaTest automation dashboard. [LambdaTest Automation Dashboard](https://automation.lambdatest.com/build/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample) will help you view all your text logs, screenshots and video recording for your entire automation tests.

## Running the Parallel Tests Using RSpec Framework

### Executing the Parallel Tests 
Navigate to the directory where you cloned the sample of RSpec Ruby and run the following command.
```bash
bundle exec rake parallel
```
Your test results would be displayed on the test console (or command-line interface if you are using terminal/cmd) and on [LambdaTest automation dashboard](https://automation.lambdatest.com/build/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample).

## Testing Locally Hosted or Privately Hosted Projects

You can test your locally hosted or privately hosted projects with [LambdaTest Selenium grid cloud](https://www.lambdatest.com/selenium-automation/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample) using LambdaTest Tunnel app. All you would have to do is set up an SSH tunnel using LambdaTest Tunnel app and pass toggle `tunnel = True` via desired capabilities. LambdaTest Tunnel establishes a secure SSH protocol based tunnel that allows you in testing your locally hosted or privately hosted pages, even before they are made live.

>Refer our [LambdaTest Tunnel documentation](https://www.lambdatest.com/support/docs/testing-locally-hosted-pages/) for more information.

Here’s how you can establish LambdaTest Tunnel.




```
Use the below command for running a local test.
```bash
bundle exec rake local
```
## Additional Links

* [Advanced Configuration for Capabilities](https://www.lambdatest.com/support/docs/selenium-automation-capabilities/)
* [How to test locally hosted apps](https://www.lambdatest.com/support/docs/testing-locally-hosted-pages/)
* [How to integrate LambdaTest with CI/CD](https://www.lambdatest.com/support/docs/integrations-with-ci-cd-tools/)

## Documentation & Resources :books:

      
Visit the following links to learn more about LambdaTest's features, setup and tutorials around test automation, mobile app testing, responsive testing, and manual testing.

* [LambdaTest Documentation](https://www.lambdatest.com/support/docs/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)
* [LambdaTest Blog](https://www.lambdatest.com/blog/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)
* [LambdaTest Learning Hub](https://www.lambdatest.com/learning-hub/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)    

## LambdaTest Community :busts_in_silhouette:

The [LambdaTest Community](https://community.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample) allows people to interact with tech enthusiasts. Connect, ask questions, and learn from tech-savvy people. Discuss best practises in web development, testing, and DevOps with professionals from across the globe 🌎

## What's New At LambdaTest ❓

To stay updated with the latest features and product add-ons, visit [Changelog](https://changelog.lambdatest.com/) 
      
## About LambdaTest

[LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample) is a leading test execution and orchestration platform that is fast, reliable, scalable, and secure. It allows users to run both manual and automated testing of web and mobile apps across 3000+ different browsers, operating systems, and real device combinations. Using LambdaTest, businesses can ensure quicker developer feedback and hence achieve faster go to market. Over 500 enterprises and 1 Million + users across 130+ countries rely on LambdaTest for their testing needs.    

### Features

* Run Selenium, Cypress, Puppeteer, Playwright, and Appium automation tests across 3000+ real desktop and mobile environments.
* Real-time cross browser testing on 3000+ environments.
* Test on Real device cloud
* Blazing fast test automation with HyperExecute
* Accelerate testing, shorten job times and get faster feedback on code changes with Test At Scale.
* Smart Visual Regression Testing on cloud
* 120+ third-party integrations with your favorite tool for CI/CD, Project Management, Codeless Automation, and more.
* Automated Screenshot testing across multiple browsers in a single click.
* Local testing of web and mobile apps.
* Online Accessibility Testing across 3000+ desktop and mobile browsers, browser versions, and operating systems.
* Geolocation testing of web and mobile apps across 53+ countries.
* LT Browser - for responsive testing across 50+ pre-installed mobile, tablets, desktop, and laptop viewports




## We are here to help you :headphones:

* Got a query? we are available 24x7 to help. [Contact Us](support@lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)
* For more info, visit - [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=RSpec-Selenium-Sample)
