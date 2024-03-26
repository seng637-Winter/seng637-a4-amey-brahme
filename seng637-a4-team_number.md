**SENG 637 - Dependability and Reliability of Software Systems**

**Lab. Report \#4 – Mutation Testing and Web app testing**

| Group \#:      |     |
| -------------- | --- |
| Student Names: |     |
|                |     |
|                |     |
|                |     |

# Introduction

# Analysis of 10 Mutants of the Range class 

# Report all the statistics and the mutation score for each test class

# Analysis drawn on the effectiveness of each of the test classes

# A discussion on the effect of equivalent mutants on mutation score accuracy

# A discussion of what could have been done to improve the mutation score of the test suites

# Why do we need mutation testing? Advantages and disadvantages of mutation testing

# Explain your SELENUIM test case design process
To start off, the provided tutorials were followed to understand the steps and functioning of Selenium. 
One website out of the three was choosen for testing. 
We started with a basic testing like the links on navigation bar and search functionality. 
Then more nuanced tests were run to check if the links within the navigation works or not. 
Moving further downstream, the checkout process was was tested. 

Then some basic features of other two wensites were also checked. 

1. Get test data
2. Simulate user action
3. Check if the app functions as expected
4. Output test results

Test 1: Search: Everything works, 
Test 2: Navigation: When a sub link is clicked taht works on the website but fails while testing 
Test 3: SignUp_Verification: Accepts correct info but also accepts incorrect info. I was able to sign up using xyz@abc.com and 000-000-0000 phone number. It should send a verification link to the registered email to overcome this issue. 
Verify that user successful registration message is displayed. It ran correctly the first time, now the says the user is already registered. Add assertion to make sure registration page is open, add verify to check if the sign up is successful or not. This test will show as failed only because the user profile has already been created and creating same profile is not allowed. So it does not go to the confirmation page at the end. 
Test 4: Login: 


# Explain the use of assertions and checkpoints
We need check points to verify control data, validate contents and compare expected output. 
Checkpoints were used to check if the correct price is diplayed, correct name is displayed upon login, cart shows expected items.

Items that were critical such as displaying the correct name after login were assigned a assertion, but text verification on website was assigned verification. 

# how did you test each functionaity with different test data
The search bar was tested with a category offered by ShopSmartCanada and then with a category not offered by them.


# How the team work/effort was divided and managed

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the assignment itself
