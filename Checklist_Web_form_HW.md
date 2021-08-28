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
| C_6     |                          | Check the on-screen notification is displayed after successfully filling out the form         | Failed        |
| C_7     |                          | Check in case of incorrect filling of any of the fields, the form is displayed again          | Passed        |
| C_8     |                          | Check that confirmation message about successfully registration was sent via email            | Failed        |
| C_9     |                          | Verify user is able to edit data in the all fields                                            | Passed        |
| C_10    |                          | Verify tooltips text should be meaningful   				            | Faild         |
| C_11    |                          | Verify the web form without entering any data in required fields and press the button[Submit] | Passed        |
| C_12    |                          | Verify the signup web form by entering the invalid data in all the required fields            | Passed        |
| C_13    |                          | Verify user is able to clear data in the fields                                               | Passed        |
| C_14    |                          | Verify that all the required fields are marked with asterisk symbol                           | Failed        |
| C_15    |                          | Verify the web form by entering the valid data only in some required fields                   | Passed        |
| C_16    |                          | Verify that after reload of the web form the data in the fields was clear                     | Passed        |
| C_17    |                          | Verify warning message is appeared after filling all required fields invalid data             | Passed        | 


## 2 Checklist Web Form fields

| ID     | Functional Area (module) | Checks                                                                                       | Test Status  |
| -------|--------------------------|----------------------------------------------------------------------------------------------|--------------|
| C_1    | Name field               | Verify the input valid data in the field                                                     |              |
| C_2    |                          | Verify the minimum character limit of the field				          |              |
| C_3    |                          | Verify the maximum character limit of the field                                              |              |
| C_4    |                          | Check for latin alphabet is accepted in upper and lower case both                            |              | 
| C_5    |                          | Check the field for numeric characters only                                                  |              |
| C_6    |                          | Check copy/paste in the field                                                                |              |
| C_7    |                          | Verify the field by entering the special symbols                                             |              |
| C_8    |                          | Verify the field place holder visible or not                                                 |              |
| C_9    |                          | Check the field except only spaces as input                                                  |              |
| C_10   |                          | Verify the value visible to the or not when type in the filed                                |              |
| C_11   |                          | Check input empty value in the filed                                                         |              |
| C_12   |                          | Check input cyrillic letters in the field                                                    |              |
| C_13   |                          | Check by entering spaces in the prefix and suffix of the entered character                   |              |
| C_14   |                          | Verify user is able to edit data in the field                                                |              |
| C_15   |                          | Check input unicode in the field                                                             |              |
| C_16   |                          | Verify the fail feedback is displayed to highlight mistakes in the field                     |              |
|--------|--------------------------|----------------------------------------------------------------------------------------------|--------------|
| C_1    | Surname field            | Verify the input valid data in the field                                                     |              |
| C_2    |                          | Verify the minimum character limit of the field				          | 	   |
| C_3    |                          | Verify the maximum character limit of the field                                              |              |
| C_4    |                          | Check for latin alphabet is accepted in upper and lower case both                            |              | 
| C_5    |                          | Check the field for numeric characters only                                                  |              |
| C_6    |                          | Check copy/paste in the field                                                                |              |
| C_7    |                          | Verify the field by entering the special symbols                                             |              |
| C_8    |                          | Verify the field place holder visible or not                                                 |              |
| C_9    |                          | Check the field except only spaces as input                                                  |              |
| C_10   |                          | Verify the value visible to the or not when type in the filed                                |              |
| C_11   |                          | Check input empty value in the filed                                                         |              |
| C_12   |                          | Check input cyrillic letters in the field                                                    |              |
| C_13   |                          | Check by entering spaces in the prefix and suffix of the entered character                   |              |
| C_14   |                          | Verify user is able to edit data in the field                                                |              |
| C_15   |                          | Check input unicode in the field                                                             |              |
| C_16   |                          | Verify the fail feedback is displayed to highlight mistakes in the field                     |              |
| C_17   |                          | Check the field for input hyphenated combination of the two surnames (e.g. Casal-Giménez)    |              |
|--------|--------------------------|----------------------------------------------------------------------------------------------|--------------|
| C_1    | Email                    | Verify the field by entering the valid email address: contact@ahcstaff.com                   |              |                          
| C_2    |                          | Verify the field by entering the valid email address: il@domain.com                          |              |
| C_3    |                          | Verify the field by entering the valid email address: firstname.lastname@domain.com          |              | 
| C_4    |                          | Verify the field by entering the valid email address: firstname-lastname@domain.com          |              |
| C_5    |                          | Verify the field by entering the valid email address: firstname+lastname@domain.com          |              |
| C_6    |                          | Verify the field by entering the valid email address: 1234567890@domain.com                  |              |
| C_7    |                          | Verify the field by entering the valid email address: email@123.123.123.123                  |              |
| C_8    |                          | Verify the field by entering the valid email address: email@domain-one.com                   |              |
| C_9    |                          | Verify the field by entering the valid email address: name@localhost                         |              |  
| C_10   |                          | Verify the field by entering the valid email address: _______@domain.com                     |              |
| C_11   |                          | Verify the field by entering the valid email address: email@domain.co.jp                     |              |
| C_12   |                          | Verify the field by entering the invalid email address: email.domain.com                     |              |
| C_13   |                          | Verify the field by entering the invalid email address: @domain.com                          |              |
| C_14   |                          | Verify the field by entering the invalid email address: @%^%#$@#$@#.com                      |              |
| C_15   |                          | Verify the field by entering the invalid email address: email@domain@domain.com              |              |
| C_16   |                          | Verify the field by entering the invalid email address: email..email@domain.com              |              |
| C_17   |                          | Verify the field by entering the invalid email address: あいうえお@domain.com                 |              |
| C_18   |                          | Verify the field by entering the invalid email address: email@.domain.com                    |              |
| C_19   |                          | Verify the field by entering the invalid email address: Empty field                          |              |
| C_20   |                          | Verify user is able to edit data in the field                                                |              |
|--------|--------------------------|----------------------------------------------------------------------------------------------|--------------|
| C_1    | Password                 | Verify that user is able to enter the password in the field                                  |              |
| C_2    |                          | Check the password is encrypted or not (dots/asterisks)                                      |              |
| C_3    |                          | Check the password filed by entering the space                                               |              |
| C_4    |                          | Check the password filed not blanked                                                         |              |
| C_5    |                          | Check the data type for the password field latin alphabet, numeric                           |              |    
| C_6    |                          | Check the data type for the password field special symbols                                   |              |
| C_7    |                          | Check that user is able to paste data in password filed                                      |              |
| C_8    |                          | Check the max/min char limit for the field                                                   |              |
| C_9    |                          | Check the alert message when user leave the password field blank                             |              |
| C_10   |                          | Verify user is able to edit data in the field                                                |              |
| C_11   |                          | Verify user is able to delete data in the field                                              |              |
| C_12   |                          | Check the password strength                                                                  |              |
| C_13   |                          | Verify the password field is reqired                                                         |              |                      
| C_14   |                          | Check IP/account is blocked for user entering wrong password 5 times                         |              |
| C_15   |                          | Check the alert message when has not entered the password                                    |              |


**Values** 

| Execution       |
| --------------- |
| Passed          |                      
| Failed          |                                  
| Not Tested      |                                               
| Blocked         |             
           



