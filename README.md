Test Case 1: Valid Username and Password

Testcase ID: TC_001

Testcase Desc: Verify login with valid username and password.

Test Steps:

Open the SauceDemo website.

Enter a valid username.

Enter a valid password.

Click the Login button.

Test Data:

Username: standard_user

Password: secret_sauce

Expected Result: The user should successfully log in and navigate to the Products page.



Test Case 2: Invalid Username and Password

Testcase ID: TC_002

Testcase Desc: Verify login with invalid username and password.

Test Steps:

Open the website.

Enter an invalid username.

Enter an invalid password.

Click the Login button.

Test Data:





Test Case 3: Blank Username

Testcase ID: TC_003

Testcase Desc: Verify login with a blank username.

Test Steps:

Open the website.

Leave the username field blank.

Enter a valid password.

Click the Login button.

Test Data:

sult: The error message should display: Username is required.

Test Case 4: Blank Password

Testcase ID: TC_004

Testcase Desc: Verify login with a blank password.

Test Steps:

Open the website.

Enter a valid username.

Leave the password field blank.

Click the Login button.

Test Data:

Username: standard_user

Password: Blank

Expected Result: The error message should display: Password is required.

Username: Blank

Password: secret_sauce

Expected Re

Username: invalid_user

Password: invalid_pass

Expected Result: The error message should display: Username and password do not match any user in this service.
