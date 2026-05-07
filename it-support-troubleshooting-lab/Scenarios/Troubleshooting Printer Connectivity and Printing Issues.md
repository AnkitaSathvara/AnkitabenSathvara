# Troubleshooting Printer Connectivity and Printing Issues

## 1. Problem Statement

### Issue Occurred

Users reported that they were unable to print documents from their desktop or laptop to the network printer.

### Symptoms

* Print jobs stuck in queue
* Printer showing offline status
* Documents not printing
* Error messages such as “Printer not responding”
* Delayed or failed print jobs

---

## 2. Environment Setup

* Device: Desktop PC / Laptop
* Operating System: Windows 10/11
* Printer Type: Network / Shared Printer
* Connection: Wi‑Fi / Ethernet
* Print Server: Windows Print Server (if applicable)
* Support Method: Local / Remote troubleshooting

---

## 3. Troubleshooting Process

### Step 1: Identify the Problem

* Verified user could not print documents
* Checked printer status from device
* Confirmed issue affected multiple print jobs
* Checked printer queue for stuck jobs

### Step 2: Establish Theory

Possible causes identified:

* Printer offline or powered off
* Network connectivity issue
* Incorrect printer driver
* Print spooler service failure
* IP address change on printer
* Paper jam or hardware issue

### Step 3: Test Theory

Performed diagnostic checks:

* Checked printer power and network cable
* Restarted printer device
* Verified printer IP address
* Checked Windows printer settings
* Restarted Print Spooler service
* Cleared print queue

Commands Used:

```cmd
net stop spooler
net start spooler
ipconfig /all
```

### Step 4: Implement Solution

* Restarted printer and system
* Restarted Print Spooler service
* Cleared stuck print jobs from queue
* Reinstalled printer driver
* Re-added printer using correct IP address

### Step 5: Verify System Functionality

* Test print completed successfully
* Printer status changed to online
* Print queue cleared
* All documents printed correctly

### Step 6: Document Findings

Root cause identified as print spooler service issue and stuck print queue.
Issue resolved after restarting spooler and clearing queue.

---

## 4. Tools Used

* Devices and Printers Settings
* Print Management Console
* Command Prompt
* Print Spooler Service
* Network Settings
* Printer Control Panel

---

## 5. Solution

The issue was resolved by restarting the Print Spooler service, clearing the print queue, and re-establishing the printer connection using the correct IP address.

---

## 6. Key Learning

* Learned printer troubleshooting methodology
* Understood print spooler service role
* Gained experience with network printer configuration
* Improved hardware and driver troubleshooting skills
* Learned how to resolve print queue issues

---

## 7. Documentation / Screenshots

Include:

* Printer offline status
* Print queue screenshot
* Print Spooler service restart
* Printer IP configuration
* Successful test print output
