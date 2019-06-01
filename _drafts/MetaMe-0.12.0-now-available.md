---
layout: post
author: Andrew
title: MetaMe 0.12.0 now available
---

We are happy to announce that MetaMe 0.12.0 is now available. This version has an improved dashboard, more granularity in the overview charts and many other improvements. This version also contains performance optimizations and many bug fixes.

##### Updating
You can update to 0.12.0 by going to settings > update then clicking "check for updates".  You can also download the latest version [here](/download.html)

##### Changes

###### New Features
- Redesigned dashboard
   - Removed unproductive bar chart and heat maps and relocated the most used applications
   - Overview bar chart granularity increased to 15 minutes from 1 hour
   - Overview bar chart shows activity from beginning of day
   - Productive bar chart now shows 96 data points instead of 48
   - Dashboard layout improved for higher resolution screens
- Goal progress notifications
   - Receive a notification when you are at 80% of your goal
- Notifications settings
   - Have granular control over what notifications you would like to receive from MetaMe
- Hide application from dashboard
   - Hide an application by right clicking the application on the most used widget

###### Enhancements
- Greatly improved dashboard performance
- The first close event now notifies the user that MetaMe is still running in the system tray. 
- Upgrade to Pro button only appears on second launch 
- Empty productive group state now handled more elegantly
- Triggering update within the app now backs up the user's data to the "backup" folder

###### Bug Fixes
- Fixed issue causing users to get stuck on the loading screen
- Fixed issue causing MetaMe to not install on Windows 10 32-bit machines
- Fixed bug in application selection screen when sorting by "usage"
- Fixed dashboard charts resizing issues 
- Fixed issue where "View Meta" from a minimized state does not respect maximized state
- Handled UnauthorizedException more elegantly when scanning for applications
- Fixed minor time-vector bugs when triggered by group changes

Thanks!<br/>
Andrew




