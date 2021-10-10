# AssessmentWebDriverIO
#By Shalini

The project has test scenario to perform user registration and validate product on payments page 
for a test url: http://automationpractice.com/index.php

Below is the feature:
  Feature:
·       Register on the website
·       Create Account by entering email address
.       Enter details on the Your Personal Information and click Register
·       Validate on the landing screen - correct name and surname is displayed
·       Add a product to the cart
·       Proceed to the checkout page and continue till payments
·       Validate on the payments page if the product details are correct.

Project has been implemented with WebdriverIO, having BDD cucumber framework. Allure reporting yet to be done.
Page Object model has been implemented for screens. Status - In Progress

Execution steps are as below:
	1. Execute: from terminal, run npx wdio wdio.conf.js
