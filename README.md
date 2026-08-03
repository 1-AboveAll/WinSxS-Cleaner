## Overview

This project is based on the Tiny11 Core script. Unlike the original Tiny11 builds, this script does **not** remove built-in Windows apps. Instead, it focuses on reducing WinSxS folder only. I recommend running this script after all other customizations.

The script performs the following tasks:

* Cleans the **WinSxS** component store.
* Option to enable .NET Framework 3.5.
* Removes **Windows Recovery Environment (WinRE)**.
* Removes **Microsoft OneDrive**.
* Disables or removes **Windows Update services**.
* Applies **registry tweaks** 
* Cleans temporary folders from script.
* Enables previous version of setup.
* Disables high ESD compression, switching from **Recovery** to **Fast** compression for improved processing speed.
* Fixed **ARM64** image entries.

## Guide
Open PowerShell as Administrator.
Set the PowerShell execution policy to Bypass.
Download NSudo and run it as Administrator.
In NSudo:
Select TrustedInstaller as the user.
Enable All Privileges.
Launch the script through NSudo.
Follow the on-screen instructions until the process is complete.
