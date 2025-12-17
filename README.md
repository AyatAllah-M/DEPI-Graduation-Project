# 📌 Project Overview

This project documents testing for OpenCart website https://demo.opencart.com/ and Automation Exercise website https://automationexercise.com/.

The goal is to testing techniques covered in DEPI software testing track. 
We worked on OpenCart for manual testing and database testing. We used Automation exercise for automation testing, API testing and preformance testing.

This repository represents what I worked on during the graduation project for DEPI.

# 📌What I worked on

### 1. Manual Testing
   
 ####  A. Login Functionality – OpenCart
   Tested valid login, invalid login & empty fields.
   Verified error messages.
   Checked input validation (email format, case sensitivity).
   Covered navigation to login page from homepage, logging out & refreshing page.
   
 ####  B.Currency Selection – OpenCart
    Verified available currencies.
    Ensured currency selection persists during navigation.
    Checked functionality works correctly in cart page, product details page & search page.
    

### 2. API Testing
   #### (Automation Exercise)
    API 7: POST To Verify Login with valid details
    API 8: POST To Verify Login without email parameter
    API 9: DELETE To Verify Login
    API 10: POST To Verify Login with invalid details.
   
   
### 3. Automation Testing
  (Automation Exercise)
   A. Page Object Model (POM) with TestNG
    Test Case 2: Login User with correct email and password
    Test Case 3: Login User with incorrect email and password
    Test Case 4: Logout User
    Test Case 10: Verify Subscription in home page
    Test Case 11: Verify Subscription in Cart page
    Test Case 16: Place Order: Login before Checkout
    Test Case 23: Verify address details in checkout page

   B. BDD Automation using Cucumber
    Test Case 2: Login User with correct email and password
    Test Case 3: Login User with incorrect email and password

   
### 4. DataBase Testing
  Key Areas I Tested
    User data validation in DB
    Password case sensitivity
    Blocked/disabled accounts
    Login attempts tracking
    Login attempts reset
    Currencies exist in DB
    Correct currency conversion
    Prices update across system

# 📌 Tools & Technologies

  Excel (Test Cases & Bug report)
  Jira (Issue tracking, assigning tasks, documenting bugs)
  Postman Collections & API Test Scripts
  Automation Test Scripts (Selenium + TestNG + Cucumber)
  JMeter (preformance testing)


# 📌 Jira Board

https://wnbaldwy-team-x10t7voa.atlassian.net/jira/software/c/projects/GP/boards/2?visitedUserSeg=true

Entered all manual and API test cases and bugs into Jira
Attached screenshots for failed test cases
Used Jira boards to organize workflow (To Do → In Progress → Done)


## 🚀 Performance Testing (Additional)

Performance testing was conducted as an **additional, bonus** beyond the original graduation project requirements, with the goal of gaining hands-on experience and deeper understanding of performance testing concepts.


