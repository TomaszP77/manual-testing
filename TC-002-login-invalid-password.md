# ❌ Test Case: Login fails with incorrect password

**ID:** TC-002  
**Title:** Login fails when valid username and invalid password are entered  
**Preconditions:** User is on the login page  
**Test Data:**  
- Username: `validUser`  
- Password: `wrongPassword123`

### Steps:
1. Open the login page  
2. Enter `validUser` into the "Username" field  
3. Enter `wrongPassword123` into the "Password" field  
4. Click the "Login" button

### Expected Result:
- Login fails  
- Error message is displayed: `"Invalid username or password"`  
- User remains on the login page  
- No redirection to dashboard occurs
