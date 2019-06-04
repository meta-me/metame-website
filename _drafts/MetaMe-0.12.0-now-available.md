---
layout: post
author: Andrew
title: MetaMe 0.12.0 now available
---

We are happy to announce that MetaMe 0.12.0 is now available. This version gives you greater visibility on your time spent, a redesigned dashboard and some major performance optimizations and bug fixes.

##### Review your day with greater precision

The new 15 minute overview chart gives increased visibility of your activities within each hour. The increased granularity is great for anything from filling out timesheets to seeing your pomodoros.

<img class="my-3" srcset="/assets/15-minute-overview-4x.png 4x, /assets/15-minute-overview-3x.png 3x, /assets/15-minute-overview-2x.png 2x, /assets/15-minute-overview-1x.png 1x" src="/assets/15-minute-overview-1x.png" alt="15 minute overview chart" width="480"/>

##### Redesigned dashboard

We have removed less popular components of the dashboard to make it less cluttered. The unproductive heatmap and chart has been removed and components rearranged.

##### Performance improvements

Significant changes have been made under the hood to increase performance. This version has increased responsiveness whilst consuming less CPU and memory usage.

<br/>
##### Updating

You can update to 0.12.0 by going to settings > update then clicking "check for updates". You can also download the latest version [here](/download.html)

<br/>
##### Changes

###### New Features

- Redesigned dashboard
  - Overview bar chart granularity increased to 15 minutes from 1 hour
  - Overview bar chart shows activity from beginning of day
  - Productive bar chart now shows 96 data points instead of 48
  - Dashboard layout improved for higher resolution screens
  - Removed unproductive bar chart and heat maps and relocated the most used applications
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
