# 🔐 Windows Password Reset Issue

**Category:** Windows  
**Difficulty:** L1  
**Keywords:** Password Reset, Login Issue, Windows Account, Account Locked, User Authentication

---

# 📌 Problem Description

User is unable to log in to the Windows system due to forgotten password or incorrect credentials.

---

# ⚠️ Symptoms

- “Incorrect Password” message displayed
- User unable to access desktop
- Account locked after multiple failed attempts
- Login screen repeatedly rejecting password

---

# ❓ Possible Causes

- Forgotten password
- Caps Lock enabled
- Incorrect keyboard layout selected
- Expired password
- Account lockout policy triggered

---

# 🔍 Troubleshooting Steps

### Step 1: Verify Keyboard Input
Check whether:
- Caps Lock is enabled
- Num Lock is enabled
- Keyboard is functioning properly

---

### Step 2: Confirm Keyboard Layout
Ensure correct keyboard language/layout is selected from the login screen.

Example:
- English (US)
- English (UK)

---

### Step 3: Retry Known Passwords
Ask the user to try:
- Previously used passwords
- Password hints
- Saved credentials

---

### Step 4: Use Password Recovery Option
If available, click:
- “Forgot Password”
- Follow recovery steps using registered email or phone

---

### Step 5: Reset Password Using Administrator Account

1. Log in using administrator account
2. Open:

```text
Control Panel → User Accounts
```

3. Select affected user account
4. Reset password
5. Save changes

---

### Step 6: Restart the System
Restart computer and verify whether user can log in successfully.

---

# ✅ Resolution

Password was successfully reset using administrator account and user regained access to the system.

---

# ⬆️ Escalate to L2 if

- Administrator account inaccessible
- Domain account synchronization issue detected
- Active Directory issue suspected
- Account remains locked after password reset
- User profile corruption identified

---

# 🛡️ Prevention Tips

- Use strong but memorable passwords
- Enable password recovery options
- Avoid multiple failed login attempts
- Maintain updated recovery email/phone
