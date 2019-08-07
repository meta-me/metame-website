---
layout: post
author: Andrew
title: MetaMe 0.14.0 now available
---

MetaMe 0.14.0 is now available. This version has a new theme system, two new color schemes and improved usability for common actions.

### Theming system

Change the MetaMe color scheme via settings > themes. Your can now try two exciting new themes: Thalassophile and Tyson dark.

<div class="my-3">
<img class="m-2" srcset="/assets/thalassophile-1x.png 1x, /assets/thalassophile-2x.png 2x, /assets/thalassophile-3x.png 3x, /assets/thalassophile-4x.png 4x" src="/assets/thalassophile-1x.png" alt="MetaMe thalassophile theme" title="MetaMe thalassophile theme" width="300"/>
<img class="m-2" srcset="/assets/tyson-dark-1x.png 1x, /assets/tyson-dark-2x.png 2x, /assets/tyson-dark-3x.png 3x, /assets/tyson-dark-4x.png 4x" src="/assets/tyson-dark-1x.png" alt="MetaMe tyson dark theme" title="MetaMe tyson dark theme" width="300"/>
</div>

### Improved usability for common actions

In previous versions, editing goals, groups and categorizing applications was not easily discoverable. This version of MetaMe now uses a hover + keyboard press system which should increase discoverability and learnability.

<div class="my-3">
<img class="m-2" srcset="/assets/categorize-app-1x.png 1x, /assets/categorize-app-2x.png 2x" src="/assets/categorize-app-1x.png" alt="Categorizing an app" title="Categorizing an app" width="300"/>
<img class="m-2" srcset="/assets/edit-goal-1x.png 1x, /assets/edit-goal-2x.png 2x" src="/assets/edit-goal-1x.png" alt="Edit goal" title="Edit goal" width="300"/>
<img class="m-2" srcset="/assets/edit-group-1x.png 1x, /assets/edit-group-2x.png 2x" src="/assets/edit-group-1x.png" alt="Edit group" title="Edit group" width="300"/>
</div>

<br/>
### Updating

Update to this version by going to settings > update then clicking "check for updates". You can also download the latest version [here](/download.html)

<br/>
### Changes

##### New

- Themes selection page - Select your favourite color scheme from settings > themes page. Select from the following:
  - Thalassophile - a low contrast theme based on solarized dark
  - Tyson dark - a more vibrant color scheme based on default

##### Improved

- Edit goal action
  - Hover + keyboard button press (X) replaces the previous pencil edit button action
- Edit group action
  - Hover + keyboard button press (X) replaces the previous dot menu actions
- Categorize application action
  - Hover + keyboard button presses replaces previous context menu actions
    - Hovering over the app then pressing X,C,V,B would categorize as productive, unproductive, neutral and hidden respectively
- Keyboard shortcut Alt + ~ now minimizes MetaMe instead of hiding it.

##### Fixed

- Messenger.com and other webpages stealing focus
- Minor gridline animation issue in activity chart
- Heat map data issue when productive groups are updated
- Performance issues which may be causing the dashboard to get stuck loading after long periods of idleness
- Possibility of getting stuck on the loading page due to concurrency race condition

##### Removed

- Search functionality removed due to weak user response
- Upgrade to Pro button removed.

Thanks!<br/>
Andrew
