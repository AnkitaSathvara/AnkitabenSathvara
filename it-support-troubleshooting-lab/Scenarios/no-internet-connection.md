# Scenario 2: No Internet Connection

## Problem
User reports that they are unable to access the internet.

## Possible Causes
- Network cable unplugged
- Wi-Fi not connected
- Invalid IP address
- DNS issue
- Router problem

## Troubleshooting Steps
1. Check if Wi-Fi is connected or Ethernet cable is plugged in
2. Run `ipconfig /all` to check IP address
3. Run `ping 8.8.8.8` to test internet connectivity
4. Run `ping google.com` to check DNS
5. Restart router and computer
6. Renew IP using `ipconfig /release` and `ipconfig /renew`

## Outcome
Internet connection restored after renewing IP address and restarting the router.
