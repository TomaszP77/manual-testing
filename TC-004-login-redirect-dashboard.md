# ✅ Test Case: Successful login redirects to dashboard and displays user info

**ID:** TC-004  
**Title:** User is redirected to dashboard after login, and profile info is visible  
**Preconditions:** User is on the login page  
**Test Data:**  
- Username: `validUser`  
- Password: `correctPassword123`

### Steps:
1. Open the login page  
2. Enter `validUser` into the "Username" field  
3. Enter `correctPassword123` into the "Password" field  
4. Click the "Login" button

### Expected Result:
- User is redirected to `/dashboard` (or home page)  
- User's name is visible in the header (e.g. `Welcome, Tomasz!`)  
- Logout button is visible  
- No error messages are shown
