---
layout: post
title: "Website Redesign"
date:   2024-04-26 12:00
categories: Website
published: false
---

Welcome to the new danielcberman.com!

First a screen shot of the original site and then a screenshot of the new site.

This site is still hosted on Github Pages but the theme has been updated from Minima 2.5.1 back in 2019 to the latest 3.0 version forked from https://github.com/jekyll/minima in April 2024.

The following changes have been made,

1. Minima 3.0 Dark Theme activated in _config.yml
2. The content window has been widened in CSS from 800 pixels to 1600 pixels. This was done to taken advantage of modern screen widths. Text still reflows properly when the site is viewed on mobile. 
3. URLs have been rewritten to remove the .html at the end of the URLs with the following code in _config.yml. [Code] permalink: /:categories/:year/:month/:day/:title/ [/Code]
4. Paginate has been enabled with 10 posts per page.
5. Site search has been added with Lunr.js using the tutorial from https://jekyllcodex.org/without-plugin/search-lunr/. The search results page has also been customized to be left hand justified to fit within the rest of the site.
6. Site search SVG icon comes from https://fluenticons.co.
7. The Favicon comes from SourceURL and includes icons for website tabs as well as adding danielcberman.com to your homescreen if desired.
8. TODO HTML for posts and pages is automatically minified on build in Liquid using this jekyll layout overlayed over the top of the Minima theme  https://jch.penibelst.de.
9. About page content has been updated with some life and professional changes that happened during COVID and tries to place it all in some type of context as I move forward into cyber-security.Had a request from a friend to reset the Windows password on their computer. Almost all of the instructions you find online about resetting a windows password talk about booting the device via USB or CD/DVD Drive first.

What if the device refuses to boot via USB?

With physical access to the computer and a USB to SATA adapter, I decided to remove the hard drive from the computer, and boot my laptop with an Ubuntu Linux USB stick. From there I installed chntpw (https://www.chntpw.com), cleared the password on the offline copy of Windows 10 and exited. From there I reconnected the hard drive to the original system and booted the system. With no password assigned to the account, the system logged in automatically.

While my friend will be happy, and I have done everything with her permission, this is a great example of why maintaining physical control of your computer is so important.
