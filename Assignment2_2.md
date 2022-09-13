# Assignment 2.2
List down the testing levels and testing types

Provide detailed scenario as much as possible

Provide explanation on the chosen answer during presentation

## Task 1: Define what testing type that we can apply for this requirement. And explain how the testing will be done in each levels   
  
**Requirements**
- User should be able to register using email
- Email should be in valid format
- Email is mandatory

**Testing level:** Unit Testing

**Testing type:** Functional

**Detailed scenario:** 
- register with nonexistent email
- register without agreeing to tnc
- register with an existing email account that is already registered with binary.com
- register with an existing email that is not yet registered with binary.com
- verify email and log in
- create a password shorter than 8 characters
- create a password with only alphabets
- capitalize first letter of password
- add numbers to password
- add symbols to password


**Explanation:** 
- unit testing because the signup page is an individual component 
- functional testing because it is related to the business process

## Task 2: [Given this link](https://oauth.deriv.com/oauth2/authorize?app_id=16929), define what scenarios that you will be testing

- login with a nonexistent account
- login with an existing account that is not yet registered with binary.com
- login with an existing google account
- login with an existing account but wrong password
- login with an existing account and correct password
- log out
- log out
- delete account

## Task 3: [Given this link,](https://deriv.com/help-centre/) What kind of non functionality testing that you will do? and explain how the testing will be.

> nonfunctional testing includes: performance / load / security / stress testing / usability

1) Performance testing
- Using the chrome devtool to mimick low internet speed (i.e. 2G and below) to load the site

2) usability testing

- attempt to open the page in different browsers (chrome, opera, firefox, etc) 
- open the page in devices with different viewport sizes
 

