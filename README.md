# Check-USB
A PowerShell GUI tool to check if a USB drive is still plugged in at computer logoff.

If a USB drive is detected this message box will popup and delay the logoff for 60 seconds.

Code can also be added to have it pull the user's name and email and send an email to them.

![Alt text](/../main/Check-USB.png?raw=true "Optional Title")

_

Add this to a Group Policy Logoff script.

powershell.exe -NoLogo -NoProfile -WindowStyle Hidden ".\Check-USB.ps1"
