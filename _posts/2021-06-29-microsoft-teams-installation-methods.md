---
layout: post
title:  "Microsoft Teams Installation Methods"
date:   2021-06-29 12:00:00
categories: Microsoft Teams
---

Microsoft Teams installs to C:\Users\{USER}\AppData\Local\Microsoft\Teams\Current

As such installing Microsoft Teams from [https://www.microsoft.com/en-us/microsoft-teams/download-app](https://www.microsoft.com/en-us/microsoft-teams/download-app) will only install Microsoft Teams for that specific user. The installer would have be rerun if a different user logged into the machine and wants to use Teams.

If the Machine-wide Installer is used from [https://docs.microsoft.com/en-us/microsoftteams/msi-deployment](https://docs.microsoft.com/en-us/microsoftteams/msi-deployment) then a login task is deployed each team a new user logs in or a returning user logs in to install or update Microsoft Teams as appropiate automatically.

If a specific user decides to uninstall Teams from their machine a registry entry is made at HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\PreventInstallationFromMsi which the login task will check before attempting to install Teams and stop.

Source: [https://docs.microsoft.com/en-us/microsoftteams/msi-deployment](https://docs.microsoft.com/en-us/microsoftteams/msi-deployment)
