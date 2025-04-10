# ⚠️ Test Case: Login fails when fields are left empty

**ID:** TC-003  
**Title:** Login fails when username and password fields are empty  
**Preconditions:** User is on the login page  
**Test Data:**  
- Username: *(empty)*  
- Password: *(empty)*

### Steps:
1. Open the login page  
2. Leave the "Username" field empty  
3. Leave the "Password" field empty  
4. Click the "Login" button

### Expected Result:
- Login attempt is blocked  
- Error message appears: `"Please enter your username and password"`  
- Fields are highlighted (if the app has validation UI)  
- User stays on the login page
