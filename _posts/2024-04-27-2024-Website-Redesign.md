---
layout: post
title: "2024 Website Redesign"
date:   2024-04-7 08:00
categories: Website
published: true
---

Welcome to the new [danielcberman.com](https://www.danielcberman.com)!

First screen shots!

| Original                 |  2024 Revision           |
:-------------------------:|:-------------------------:
![](/assets/2023-old-danielcberman-com.png)  | ![](/assets/2024-new-danielcberman-com.png)

This site is still hosted on Github Pages but the theme has been updated from Minima 2.5.1 back in 2019 to the latest 3.0 version forked from [https://github.com/jekyll/minima](https://github.com/jekyll/minima) in April 2024.

The following changes have been made,

1. Minima 3.0 Dark Theme activated in _config.yml
2. The content window has been widened in CSS from 800 pixels to 1600 pixels. This was done to taken advantage of modern screen widths. Text still reflows properly when the site is viewed on mobile.
3. Robots.txt from [https://shellsharks.com/robots.txt](https://shellsharks.com/robots.txt) has been added and personalized for this site. Mike Sass has come up with the most comprohensive Robots.txt for blocking "AI" bots that I have found.
4. URLs have been rewritten use /blog/ as a base and the post title with the .html removed at the end of the URLs. The following code is used in my _config.yml. [Code] permalink: /blog/:title/ [/Code]
5. Paginate Jekyll plugin  has been enabled in _config.yml with 10 posts per page.
6. Site search has been added with Lunr.js using the tutorial from [https://jekyllcodex.org/without-plugin/search-lunr/](https://jekyllcodex.org/without-plugin/search-lunr/). The search results page has also been customized to be left hand justified to fit within the rest of the site.
7. Site search icon comes from [https://fluenticons.co](https://fluenticons.co).
8. Sitemap Jekyll Plugin has been enabled in _config.yml. Generated file can be seen at [https://www.danielcberman.com/sitemap.xml](https://www.danielcberman.com/sitemap.xml)
9. [404 Page](https://www.danielcberman.com/404.html) has been updated with a link to the search page to not leave visitors hanging. 
10. The Favicon comes from SourceURL and includes icons for website tabs as well as adding danielcberman.com to your homescreen if desired. This favicon was generated using the Abyssinica SIL Font. Copyright (c) 2000-2022 by SIL International. Source: [https://fonts.gstatic.com/s/abyssinicasil/v5/oY1H8ezOqK7iI3rK_45WKoc8J6UZBFOVAXuI.ttf](https://fonts.gstatic.com/s/abyssinicasil/v5/oY1H8ezOqK7iI3rK_45WKoc8J6UZBFOVAXuI.ttf). License: SIL Open Font License, 1.1 [http://scripts.sil.org/OFL](http://scripts.sil.org/OFL)
11. HTML for posts and pages is automatically minified on build in Liquid using this jekyll layout overlayed over the top of the Minima theme  [https://jch.penibelst.de](https://jch.penibelst.de).
12. About page content has been updated with some life and professional changes that happened during COVID and tries to place it all in some type of context as I move forward into cyber-security.
