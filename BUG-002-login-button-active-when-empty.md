# 🐞 Bug Report: "Login" button is enabled even when fields are empty

**ID:** BUG-002  
**Title:** Login button is clickable when username and password fields are empty  
**Environment:**  
- OS: Windows 10  
- Browser: Google Chrome 123.0  
- App version: 1.0.0  
- URL: https://example.com/login

---

### Steps to Reproduce:
1. Go to the login page  
2. Leave the "Username" and "Password" fields empty  
3. Observe the state of the "Login" button

---

### Expected Result:
- "Login" button should be **disabled** when fields are empty  
- Button should only become active when both fields are filled

---

### Actual Result:
- "Login" button is **clickable** even when fields are empty  
- Clicking it causes an error message or reloads the page

---

### Severity: Medium  
### Priority: Medium/High (depends on product goals)

---

**Attachments:** *(Optional screenshot showing enabled button with empty fields)*
