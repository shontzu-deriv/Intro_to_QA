# Day 4: Testing tools
- Trello
- Jira
- Redmine
- Bugzilla
- Selenium (Deriv automation)
- Test Rail

## Types of tools
### 1) Directly in testing
> execution tools, data generation, result comparison

### 2) Managing testing process
> (Redmine): result, requirement, incident, defect

### 3) Monitoring and reporting
> test execution

## Classification of tools
- purpose
- activities
- type/level
- licensing
- technology

## Tool support for testing purpose
- automate repetitive task
- automate resource-heavy task
- automate task that cannot be done manually (i.e. large scale client-server performance)
- reliability (simulate complex behaviour, automate large data comparison)

## Risks
- overestimating capabilities
- time, cost, effort to introduce tool
- maintaining beneficial use of tool
- maintaining automation test assets
- skill mismatch

## Limitations
- process undefined / immature
- frequent changes in UI and functionalitites

## Factors of successful tool support
- Guidelines and documentation
- Training and mentoring for tool users
- Incremental roll-out

## QA Testing tools
### 1) Test Management 
> i.e. Redmine, Jira
- store info
- plan test cases
- report qa status

### 2) Performance Testing
> i.e. Jmeter
- every product has a tipping point where performance start going down
- simulate users in distributed env
- tests provide data points to see min-max response time 
- num of users can simultaneously use the app

### 3) Functional Testing 
> i.e. Jest
#### 3.1) unit testing

#### 3.2) Browser / UI testing

#### 3.3) API testing
> i.e. Postman, Deriv API Playground
- test service level or API

#### 3.4) Automation testing
> i.e. Selenium, Robot Framework
- 


## Activity
### Create virtual acc using API (NOT via app UI)
API: verify email       -> pass in email to verify (+1 before '@' if existing) 
                        -> get verification code from the url sent
API: new virtual acc    -> pass in the verification code`
                        -> reset passwd if need (make sure check regex requirement)
                        -> get oauth token for virtual acc (a1-Wom7OnxATMfrkdVL2RcfL3WDblpMb)
API: new real acc       -> pass in virtual acc oauth token
                        -> send req (if error, check state and uname/bdate etc)
                        -> acquire oauth token to create real acc (ku9FjIPfZ9y6QmQgTHvUvKnQhZXiG)
API: proposal           -> config your order (i.e tp sl contract type, amt, etc)
API: 

### check the UI on how the API are used
- [deriv app](https://app.deriv.com)
- ctrl + shift + I (inspect)
- chrome devtools : Network > WS (Websocket) > Messages

