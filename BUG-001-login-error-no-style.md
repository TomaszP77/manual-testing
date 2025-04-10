# 🐞 Bug Report: Error message on failed login is not styled

**ID:** BUG-001  
**Title:** Error message on invalid login appears without red styling  
**Environment:**  
- OS: Windows 10  
- Browser: Google Chrome 123.0  
- App version: 1.0.0  
- URL: https://example.com/login

---

### Steps to Reproduce:
1. Go to the login page  
2. Enter invalid credentials:  
   - Username: `invalidUser`  
   - Password: `wrongPassword`  
3. Click the "Login" button

---

### Expected Result:
- An error message is displayed in **red color**
- Message is clearly visible, near the login form

---

### Actual Result:
- Error message appears as **plain black text**  
- It's not styled, looks like regular text  
- User might not notice the error

---

### Severity: Low/Medium (UI issue, but affects user experience)  
### Priority: Medium

---

**Attachments:** *(Add screenshot)*
