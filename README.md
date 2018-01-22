# Get-AZCopyGUI
## A simple GUI wrapper for AZCopy.exe to simplify the process of importing .PSTs into Exchange Online.

A simple GUI wrapper for AZCopy.exe to simplify the process of importing .PSTs into Exchange Online. For more information about the usage, please see this post on my blog.

**Requirements:**

This script will work natively in PowerShell 2.0+
This script requires the Microsoft Azure AZCopy Tool with default installation path - get it here

**Usage:**
There are no parameters or switches, simply execute the script: .\Get-AZCopyGUI.ps1

When using the Verbose option, a log file is named AzCopyVerbose.log will be created in %LocalAppData%\Microsoft\Azure\AzCopy if no "Log Location" is specified.

**Screenshots:**

![alt text](https://www.cgoosen.com/wp-content/uploads/2015/05/Capture.png)
