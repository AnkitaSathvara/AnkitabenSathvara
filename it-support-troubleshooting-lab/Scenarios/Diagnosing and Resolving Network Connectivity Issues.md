# Diagnosing and Resolving Network Connectivity Issues

## 1. Problem Statement

### Issue Occurred

Users in a Small Office/Home Office (SOHO) environment were unable to connect to the internet through Wi‑Fi.

### Symptoms

* No internet access
* Limited connectivity warning
* Websites not loading
* Network icon showing disconnected status
* Unable to access online services

---

## 2. Environment Setup

* Device: Desktop PC / Laptop
* Operating System: Windows 10/11
* Network Type: Wi‑Fi Router
* ISP Connection: Broadband
* Support Method: Remote Support / Local Access

---

## 3. Troubleshooting Process

### Step 1: Identify the Problem

* Verified users could not browse websites
* Checked Wi‑Fi connection status
* Confirmed multiple devices were affected
* Checked network icon and internet status

### Step 2: Establish Theory

Possible causes identified:

* Router issue
* Incorrect IP configuration
* DNS server issue
* Disabled network adapter
* ISP outage
* Weak Wi‑Fi signal

### Step 3: Test Theory

Performed diagnostic checks:

* Restarted Wi‑Fi router
* Checked network adapter settings
* Verified IP configuration
* Tested internet connectivity using ping command
* Tested DNS resolution
* Ran Windows network troubleshooter

Commands Used:

```cmd
ipconfig /all
ipconfig /release
ipconfig /renew
ping 8.8.8.8
ping google.com
nslookup google.com
```

### Step 4: Implement Solution

* Restarted the router
* Renewed IP configuration
* Reset TCP/IP settings
* Updated DNS settings to Google DNS (8.8.8.8)
* Reconnected system to Wi‑Fi network

### Step 5: Verify System Functionality

* Successfully connected to the internet
* Websites loaded normally
* Ping tests successful
* Network status displayed as connected

### Step 6: Document Findings

Root cause identified as DNS configuration and IP conflict issue.
Issue resolved after renewing IP configuration and updating DNS settings.

---

## 4. Tools Used

* Command Prompt
* Network Settings
* Device Manager
* Wi‑Fi Router Admin Panel
* Ping Utility
* IPConfig Commands
* Windows Network Troubleshooter

---

## 5. Solution

The issue was resolved by restarting the router, renewing the IP configuration, resetting TCP/IP settings, and updating DNS configuration to Google DNS (8.8.8.8).

---

## 6. Key Learning

* Learned structured troubleshooting methodology
* Improved understanding of TCP/IP networking
* Gained hands-on experience with network diagnostics
* Learned DNS troubleshooting techniques
* Improved command-line networking skills

---

## 7. Documentation / Screenshots

Include:

* Before vs after internet connectivity status
* Command Prompt outputs
* IP configuration screenshots
* Router settings screenshots
* Successful ping test results
