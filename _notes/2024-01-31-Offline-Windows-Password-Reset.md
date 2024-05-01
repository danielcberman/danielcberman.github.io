---
title: "Offline Windows Password Reset"
date:   2024-01-31 21:45:00
categories: Sysadmin
---

Had a request from a friend to reset the Windows password on their computer. Almost all of the instructions you find online about resetting a windows password talk about booting the device via USB or CD/DVD Drive first.

What if the device refuses to boot via USB?

With physical access to the computer and a USB to SATA adapter, I decided to remove the hard drive from the computer, and boot my laptop with an Ubuntu Linux USB stick. From there I installed chntpw (https://www.chntpw.com), cleared the password on the offline copy of Windows 10 and exited. From there I reconnected the hard drive to the original system and booted the system. With no password assigned to the account, the system logged in automatically.

While my friend will be happy, and I have done everything with her permission, this is a great example of why maintaining physical control of your computer is so important.
