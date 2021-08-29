*Web Form Testing Homework* 


## 1 Checklist Web Form

Link to Web Form: http://itcareer.pythonanywhere.com/ 

| ID      | Functional Area (module) | Checks                                                                                        | Test Status   |
| --------|--------------------------|-----------------------------------------------------------------------------------------------|---------------|
| C_1     | Web Form                 | Verify Tab and Shift+Tab order should work properly                                           | Passed        | 
| C_2     |                          | Check the required fields by not filling any data                                             | Passed        |
| C_3     |                          | Ensure that all the fields have titles                                                        | Passed        |
| C_4     |                          | Upon click of any input text field, mouse arrow pointer should get changed to cursor          | Passed        |
| C_5     |                          | Fill all required fields valid data and press the button[Submit]                              | Failed        |
| C_6     |                          | Check the on-screen notification is displayed after successfully filling out the form         | Passed        |
| C_7     |                          | Check in case of incorrect filling of any of the fields, the form is displayed again          | Passed        |
| C_8     |                          | Check that confirmation message about successfully registration was sent via email            | Not tested    |
| C_9     |                          | Verify user is able to edit data in the all fields                                            | Passed        |
| C_10    |                          | Verify tooltips text should be meaningful   				            | Faild         |
| C_11    |                          | Verify the web form without entering any data in required fields and press the button[Submit] | Passed        |
| C_12    |                          | Verify the signup web form by entering the invalid data in all the required fields            | Failed        |
| C_13    |                          | Verify user is able to clear data in the fields                                               | Passed        |
| C_14    |                          | Verify that all the required fields are marked with asterisk symbol                           | Failed        |
| C_15    |                          | Verify the web form by entering the valid data only in some required fields                   | Failed        |
| C_16    |                          | Verify that after reload of the web form the data in the fields was clear                     | Passed        |
| C_17    |                          | Verify warning message is appeared after filling all required fields invalid data             | Passed        | 


## 2 Checklist Web Form fields

| ID     | Functional Area (module) | Checks                                                                                       | Test Status  |
| -------|--------------------------|----------------------------------------------------------------------------------------------|--------------|
| C_1    | Name field               | Verify the input valid data in the field  (enter Mary)                                       | Passed       |
| C_2    |                          | Verify the minimum character limit of the field (enter 1, 2 latin letter)	          | Failed       |
| C_3    |                          | Verify the maximum character limit of the field  (enter 255, 256 characters)                 | Failed       |
| C_4    |                          | Check for latin alphabet is accepted in upper and lower case both                            | Passed       | 
| C_5    |                          | Check the field for numeric characters only. Alert                                           | Failed       |
| C_6    |                          | Check copy/paste in the field                                                                | Passed       |
| C_7    |                          | Verify the field by entering the special symbols. Alert                                      | Failed       |
| C_8    |                          | Verify the field place holder visible or not                                                 | Passed       |
| C_9    |                          | Check the field except only spaces as input. Alert                                           | Failed       |
| C_10   |                          | Verify the value visible to the or not when type in the filed                                | Passed       |
| C_11   |                          | Check input empty value in the filed. Alert                                                  | Failed       |
| C_12   |                          | Check input cyrillic letters in the field                                                    | Passed       |
| C_13   |                          | Check by entering spaces in the prefix and suffix of the entered character                   | Failed       |
| C_14   |                          | Verify user is able to edit data in the field                                                | Passed       |
| C_15   |                          | Check input unicode in the field. Alert                                                      | Failed       |
| C_16   |                          | Verify the fail feedback is displayed to highlight mistakes in the field                     | Failed       |
|        |                                                                                                                         |              |
| C_1    | Surname field            | Verify the input valid data in the field (enter Black)                                       | Passed       |
| C_2    |                          | Verify the minimum character limit of the field (enter 1, 2 latin letter)	          | Failed       |
| C_3    |                          | Verify the maximum character limit of the field (enter 255, 256 characters)                  | Failed       |
| C_4    |                          | Check for latin alphabet is accepted in upper and lower case both                            | Passed       | 
| C_5    |                          | Check the field for numeric characters only. Alert                                           | Failed       |
| C_6    |                          | Check copy/paste in the field                                                                | Passed       |
| C_7    |                          | Verify the field by entering the special symbols. Alert                                      | Failed       |
| C_8    |                          | Verify the field place holder visible or not                                                 | Passed       |
| C_9    |                          | Check the field except only spaces as input                                                  | Failed       |
| C_10   |                          | Verify the value visible to the or not when type in the filed                                | Passed       |
| C_11   |                          | Check input empty value in the filed. Alert                                                  | Failed       |
| C_12   |                          | Check input cyrillic letters in the field                                                    | Passed       |
| C_13   |                          | Check by entering spaces in the prefix and suffix of the entered character                   | Failed       |
| C_14   |                          | Verify user is able to edit data in the field                                                | Passed       |
| C_15   |                          | Check input unicode in the field. Alert                                                      | Failed       |
| C_16   |                          | Verify the fail message is displayed to highlight mistakes in the field                      | Failed       |
| C_17   |                          | Check the field for input hyphenated combination of the two surnames (e.g. Casal-Giménez)    | Passed       |
|        |                                                                                                                         |              |
| C_1    | Email                    | Verify the field by entering the valid email address: contact@ahcstaff.com                   | Passed       |                          
| C_2    |                          | Verify the field by entering the valid email address: il@domain.com                          | Passed       |
| C_3    |                          | Verify the field by entering the valid email address: firstname.lastname@domain.com          | Passed       | 
| C_4    |                          | Verify the field by entering the valid email address: firstname-lastname@domain.com          | Passed       |
| C_5    |                          | Verify the field by entering the valid email address: firstname+lastname@domain.com          | Passed       |
| C_6    |                          | Verify the field by entering the valid email address: 1234567890@domain.com                  | Passed       |
| C_7    |                          | Verify the field by entering the valid email address: email@123.123.123.123                  | Passed       |
| C_8    |                          | Verify the field by entering the valid email address: email@domain-one.com                   | Passed       |
| C_9    |                          | Verify the field by entering the valid email address: name@localhost                         | Passed       |  
| C_10   |                          | Verify the field by entering the valid email address: _______@domain.com                     | Passed       |
| C_11   |                          | Verify the field by entering the valid email address: email@domain.co.jp                     | Passed       |
| C_12   |                          | Verify the field by entering the invalid email address: email.domain.com                     | Failed       |
| C_13   |                          | Verify the field by entering the invalid email address: @domain.com                          | Failed       |
| C_14   |                          | Verify the field by entering the invalid email address: @%^%#$@#$@#.com                      | Failed       |
| C_15   |                          | Verify the field by entering the invalid email address: email@domain@domain.com              | Failed       |
| C_16   |                          | Verify the field by entering the invalid email address: email..email@domain.com              | Failed       |
| C_17   |                          | Verify the field by entering the invalid email address: あいうえお@domain.com                 | Failed       |
| C_18   |                          | Verify the field by entering the invalid email address: email@.domain.com                    | Failed       |
| C_19   |                          | Verify the field by entering the invalid email address: Empty field                          | Failed       |
| C_20   |                          | Verify user is able to edit data in the field                                                | Passed       |
| C_21   |                          | Verify the email field is reqired                                                            | Failed       |
| C_22   |                          | Check the alert message when has not entered the email                                       | Failed       |
|        |                                                                                                                         |              |
| C_1    | Password                 | Verify that user is able to enter the password in the field                                  | Passed       |
| C_2    |                          | Check the password is encrypted or not (dots/asterisks)                                      | Passed       |
| C_3    |                          | Check the password filed by entering the space                                               | Failed       |
| C_4    |                          | Check the password filed not blanked. Alert                                                  | Failed       |
| C_5    |                          | Check the data type for the password field latin alphabet, numeric                           | Passed       |    
| C_6    |                          | Check the data type for the password field special symbols. Alert                            | Failed       |
| C_7    |                          | Check that user is able to paste data in password filed                                      | Passed       |
| C_8    |                          | Check the max/min char limit for the field                                                   | Failed       |
| C_9    |                          | Check the alert message when user leave the password field blank                             | Failed       |
| C_10   |                          | Verify user is able to edit data in the field                                                | Passed       |
| C_11   |                          | Verify user is able to delete data in the field                                              | Passed       |
| C_12   |                          | Check the password strength                                                                  | Failed       |
| C_13   |                          | Verify the password field is reqired                                                         | Failed       |                      
| C_14   |                          | Check IP/account is blocked for user entering wrong password 5 times                         | Failed       |
| C_15   |                          | Check the alert message when has not entered the password                                    | Failed       |

**Values** 

| Execution       |
| --------------- |
| Passed          |                      
| Failed          |                                  
| Not Tested      |                                               
| Blocked         |             
           



