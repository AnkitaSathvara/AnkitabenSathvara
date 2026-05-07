# Resolving Active Directory User Login Issues

## 1. Problem Statement

### Issue Occurred

Users reported being unable to log in to their Windows domain accounts in an Active Directory environment.

### Symptoms

* “Invalid username or password” error
* User account locked or disabled message
* Cannot access desktop after login attempt
* Login screen looping back repeatedly
* Delayed authentication response

---

## 2. Environment Setup

* Device: Desktop PC / Laptop
* Operating System: Windows 10/11
* Environment: Active Directory Domain
* Authentication Service: Windows Server AD
* Network: Corporate LAN / Wi‑Fi
* Support Method: On-site / Remote support

---

## 3. Troubleshooting Process

### Step 1: Identify the Problem

* Verified user was unable to log in
* Checked error message on login screen
* Confirmed whether issue affected single or multiple users

### Step 2: Establish Theory

Possible causes identified:

* Incorrect username or password
* Account locked due to failed attempts
* Account disabled in Active Directory
* Expired password
* Network connectivity issue with domain controller
* Profile corruption

### Step 3: Test Theory

Performed diagnostic checks:

* Verified user credentials in Active Directory
* Checked account status (locked/disabled)
* Attempted login with alternate account
* Checked network connectivity to domain
* Reviewed recent password changes

Commands Used:

```cmd
whoami
net user
ipconfig /all
```

### Step 4: Implement Solution

* Unlocked user account in Active Directory
* Reset user password
* Enabled account if disabled
* Forced password change at next login (if required)
* Verified network connectivity to domain controller

### Step 5: Verify System Functionality

* User successfully logged into system
* Desktop loaded without errors
* Access to network resources restored
* Authentication completed successfully

### Step 6: Document Findings

Root cause identified as account lockout due to multiple failed login attempts.
Issue resolved after unlocking account and resetting password in Active Directory.

---

## 4. Tools Used

* Active Directory Users and Computers (ADUC)
* Command Prompt
* Windows Login Screen
* Network Settings
* Domain Controller
* Event Viewer (optional)

---

## 5. Solution

The issue was resolved by unlocking the user account in Active Directory and resetting the password, restoring successful login access.

---

## 6. Key Learning

* Learned Active Directory user management
* Understood account lockout policies
* Improved domain authentication troubleshooting skills
* Gained experience with Windows Server environments
* Learned login failure diagnostics

---

## 7. Documentation / Screenshots

Include:

* Login error message
* Active Directory user account status
* Account unlock/reset process
* Successful login confirmation screen
