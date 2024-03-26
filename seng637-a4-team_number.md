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

The initial phase of our testing process involved adhering to the provided tutorials to gain a comprehensive understanding of Selenium's functionalities. Subsequently, we selected one website from the provided options for thorough examination.

Our testing commenced with fundamental assessments, such as scrutinizing the functionality of links within the navigation bar and evaluating the efficacy of the search feature. Following this, we delved into more intricate examinations, meticulously testing the responsiveness and accuracy of internal navigation links.

As our analysis progressed, we directed our attention towards scrutinizing the checkout process, assessing its robustness and efficiency. This step-by-step approach allowed us to methodically evaluate the website's performance and user experience, providing valuable insights into its functionality and potential areas for improvement.

Similar process was repeated for other two websites.

Some basic features used for all three websites were:  

  1. Get test data
  2. Simulate user action
  3. Check if the app functions as expected
  4. Output test results

Shop Smart Canada

|Test Number | Test Title | Test Description | Test Results | 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| Test 1 | Search_Functionality_Check | The search field was tested to see if correct results are shown for a serach input. | Behaves as expected | 
| Test 2 | Navigation_Functionality_Check | The primary and secondary links on the nagivations bar were checked to see their link is right. | Primary links on the nagivation bar works fine. When a secondary link is clicked, it works on the website but fails while testing |
| Test 3 | SignUp_Verification | Accepts correct info but also accepts incorrect info. I was able to sign up using xyz@abc.com and 000-000-0000 phone number. It should send a verification link to the registered email to overcome this issue rather than just reply on RegEx |

Verify that user successful registration message is displayed. It ran correctly the first time, now the says the user is already registered. Add assertion to make sure registration page is open, add verify to check if the sign up is successful or not. This test will show as failed only because the user profile has already been created and creating same profile is not allowed. So it does not go to the confirmation page at the end. 
Test 4: Shopping Cart: Navigated from home page to baggage section and added a bag to cart. No issues found in that. 

Home Depot
Test 1: Change My Store Location: Search location closer to a actual store and expect a value and then check for a value where no Home Depot store exists and see if it shows 0 stores. 
Test 2: Using popular menu to check nagivate to a category and adding to cart 
Test 3: Go go services page and use the Home Depot logo to nagivate back to Home page. 
Test 4: Order status check: We didn't have a order with Home Depot to check correct order number, but a check ofr incorrect order number being searched was made. Assertion for opening new window was used and verification of error message was used. 

# Explain the use of assertions and checkpoints
We need check points to verify control data, validate contents and compare expected output. 
Checkpoints were used to check if the correct price is diplayed, correct name is displayed upon login, cart shows expected items.

Items that were critical such as displaying the correct name after login were assigned a assertion, but text verification on website was assigned verification. 

# how did you test each functionaity with different test data
The search bar was tested with a category offered by ShopSmartCanada and then with a category not offered by them.


# How the team work/effort was divided and managed

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the assignment itself
