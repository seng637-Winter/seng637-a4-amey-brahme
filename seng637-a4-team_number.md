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

| Test Number | Test Title | Test Description                                                                      | Test Results                                      | WebSite | 
|-------------|-------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------|----------|
| Test 1      | Search_Functionality_Check    | The search field was tested to see if correct results are shown for a search input.   | Behaves as expected                              | Shop Smart Canada Page |
| Test 2      | Navigation_Functionality_Check| The primary and secondary links on the navigation bar were checked to see their link is right. | Primary links on the navigation bar work fine. When a secondary link is clicked, it works on the website but fails while testing. | Shop Smart Canada Page |
| Test 3      | SignUp_Verification_Check    | Sign up using multiple personal details to verify the form works properly.| Accepts correct info but also accepts incorrect info. I was able to sign up using xyz@abc.com and 000-000-0000 phone number. It should send a verification link to the registered email to overcome this issue rather than just reply on RegEx. Verify that user successful registration message is displayed. It ran correctly the first time, now the says the user is already registered. Add assertion to make sure registration page is open, add verify to check if the sign up is successful or not. This test will show as failed only because the user profile has already been created and creating same profile is not allowed. So it does not go to the confirmation page at the end.| Shop Smart Canada Page |
| Test 4 | Shopping_Cart_Functionality_Check | Navigated from home page to baggage section and added a bag to cart. | No issues found | Shop Smart Canada Page |
| Test 5 | Change_MyStore_Location_Functinoality_Check | Search location closer to a actual store and expect a value and then check for a value where no Home Depot store exists and see if it shows 0 stores | No issues found | Home Depot Page |
| Test 6 | Cart_using_Popular_Categories_Functionality_Check | Using popular menu to check nagivation to a category and adding to cart | No issues found | Home Depot Page |
| Test 7 | HomePage_Navigation_Functinoality_Check | Go go services page and use the Home Depot logo to nagivate back to Home page. | No issues found | Home Depot Page |
| Test 8 | Order_Status_Funcationality_Check | We didn't have a order with Home Depot to check correct order number, but a check for incorrect order number being searched was made. Assertion for opening new window was used and verification of error message was used. | No issues found | Home Depot Page |
| Test 9 | Layout_Check | Check for images on key positions to ensure layout is as expected | No issues to report | Home Depot Page |
|Test 10 | | | | Leon's Page |
|Test 11 | | | | Leon's Page |

# Explain the use of assertions and checkpoints

In our quality assurance testing approach, we implement a systematic methodology centered around checkpoints to verify control data, validate content, and compare expected outputs within our system. We categorize these checkpoints into critical and standard classifications. Critical checkpoints, such as ensuring the accurate display of user information post-login, are rigorously validated using assertion statements. Conversely, standard checkpoints, including the validation of shopping cart contents, employ verification techniques to confirm expected outcomes. Test cases exemplify this approach: for instance, in Test 3, we assert the proper loading of the signup page before validating signup fields and verifying successful account creation. Similarly, Test 5 employs verification to confirm store changes and validate error handling for invalid inputs. Test 8 involves asserting the transition to the correct webpage post-"Check Status" button click, followed by verification of order number handling. Lastly, Test 9 utilizes image-based validation to ensure the consistency of the general layout. By delineating between assert and verify statements, we prioritize critical functionalities while conducting thorough checks across all system functionalities, thereby upholding software quality and reliability.

# how did you test each functionaity with different test data
In Test 1, we conducted tests on the search bar functionality, first using a category provided by ShopSmartCanada and then with a category not within their offerings. In Test 3, we deliberately entered both invalid and valid email addresses to pinpoint any bugs previously reported. Test 8 involved the input of invalid order numbers to scrutinize the order tracking page's handling of such instances. Additionally, in Test 5, we input a location proximate to a Home Depot to verify accurate retrieval of the nearest store and, conversely, a location devoid of Home Depot presence to confirm the absence of store listings for that search.

# How the team work/effort was divided and managed

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the assignment itself
