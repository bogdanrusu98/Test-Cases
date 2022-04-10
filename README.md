# Test Case Samples

Below are some Test Case samples I wrote while working on previous projects.

---------------

**Description:**
Test the login without using credentials.

**Steps to Reproduce:**
1. Go to wordpress.com/login
2. Observe if user can login

**Expected result:**
User should not be able to login


---------------

**Description:**
Test the login by using correct credentials.

**Steps to Reproduce:**
1. Go to wordpress.com/login
2. Add correct user/pass
3. Observe if user can login

**Expected result:**
User should be able to login

**Test Data:**
User: test  &  Pass: 123


---------------

**Description:**
Test the login by using incorrect credentials.

**Steps to Reproduce:**
1. Go to wordpress.com/login
2. Add incorrect user/pass
3. Observe if user can login

**Expected result:**
Use should not be able to login

**Test Data:**
User: test  &  Pass: 123


---------------

**Description:**
Test the login by using correct credentials and remember me check-box checked.

**Steps to Reproduce:**
1. Go to wordpress.com/login
2. Add correct user/pass
3. Check Remember Me check-box
4. Press login and observe if user can login

**Expected result:**
User should be able to login without a session timeout

**Test Data:**
User: test  &  Pass: 123


---------------

**Description:**
Search existing products.

**Steps to Reproduce:**
1. Go to emag.ro
2. Add the product name to search bar
3. Press search
4. Observe if user can see the product

**Expected result:**
User should be able to find products using search function.



---------------

**Description:**
Test the auto-fill function from search bar.

**Steps to Reproduce:**
1. Go to emag.ro
2. Add the product name to search bar
3. See if the product appears on suggestion

**Expected result:**
User should be able to find products using auto-fill function.


---------------

**Description:**
Search unemployed products without getting any errors.

**Steps to Reproduce:**
1. Go to emag.ro
2. Add the product name to search bar
3. Press search
4. Observe if user gets any error

**Expected result:**
User should be able to search unemployed products without getting any errors.



---------------
