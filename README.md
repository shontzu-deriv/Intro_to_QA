# INTRO TO  QA
## my notes
- [Assignment 1: improve the feature](https://github.com/shontzu/Intro_to_QA/blob/main/Assignment1.md) 
- [Assignment 2.1: spot the difference](https://docs.google.com/document/d/1Rm1QN7JzU1O7Ed5TiAEghGwDNRv5ZRSQMu_KQn9zqH4/edit?usp=sharing)
- [Assignment 2.2: test cases](https://github.com/shontzu/Intro_to_QA/blob/main/Assignment2.2.md)
- [Assignment 3.1 black box testing](https://docs.google.com/document/d/1CwxYyhaIYi5KdwYWNYCb9yS66o4W6yHHEjjdZ0LzO04/edit)

# Day 1
## QA 4 sub teams
- smart trade, relesase, visual automation testing
- mobile, dtrader, crypto
- functional, mobile automation, testing
- production qa

## Group 4 Facis
- meeyun
- darmen
- safra

## Exercise
> write 10 test cases for firstname input box
- numbers
- non-ascii characters
- nulls
- shorter than 30 char
- leading and trailing spaces
- escape characters (\ &Tab, nbsp)
- emojis
- non-latin characters
- mixture of latin and non-latin characters
- one-letter name
- copy-pasted values
- html tag
- Xss
- duplicate name
- uppercase/lowercase

## 5 phases pof Software Testing
> debugging
>> Grace Murray (1956)

> demonstration
>> Charles Baker (1978)

> destruction
>> Glenford J. Myers "intention of finding errors" (1982)

> evaluation
>> Methodology proposed in 1987

> prevention
>> William Hetzel "The Growth of Software Testing"

## SDM (Software Development Models)
### Types
- Waterfall (test after development)
- V (test while development, not suitable for requirement change)
- Agile (Deriv: iterate + increment)
- Iterative

## Testing
### Levels
> unit
>> individual component

> integration
>> cross-component

> system
>> entire system

> acceptance
>> - Alpha testing: internal (QA team)
>> - Beta testing: affiliates and users

### Types
> Functional
>> - requirement-based /  business-process-based
>> - smoke / sanity


> Nonfunctional
>> - performance
>> - load
>> - security
>> - stress
>> - usability

> Structural
>> whitebox

> Change-related
>> - confirmation
>> - regression

> Maintenance
>> - modification
>> - migration
>> - retirement

# Day 2
## Test Techniques
> Black Box
>> - Testing wihtout knowing the inner structure of the system
>> - Behavioral based
>> - input output

**5 types of blackbox testing**
1) Equivalence Partitioning (valid vs invalid data/type)
2) Boundary Value Analysis (upper/lower boundaries)
3) Decision Table (Conditions/Actions, Input/Output, "expected result")
4) State Transitioning (state change in one page affect other page)
5) Use Case Test Cases (end-to-end tseting)

> White Box
>> - Testing with full knowledge of how the system operates
>> - Structural-based

> Experience-based
>> experience of developers and testers



