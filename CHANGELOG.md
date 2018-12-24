# Changelog

### 2.4.0
- add tab audio indicators for Pale Moon 28.3.0+
- update in-browser developer tools

### 2.3.1
- fix version number

### 2.3.0
- sync global stylings with Pale Moon 28
- remove redundant devtools styling
- mark as compatible with Pale Moon 28 only
- use non-prefixed -inline syntax
- update media controls
- improve menubar appearance on Linux

### 2.2.0
- add PM28 newtab styling
- add tabbrowser findbar styling
- improve about:permissions sizing
- fix disappearing titlebar in private and lwtheme modes on macOS
- fix favicon sizes in password manager

### 2.1.0
- add initial Pale Moon 28 support
- don't use background image on standalone image viewer

### 2.0.1
- set minimum supported version to Pale Moon 27.5.0
- fix statusbar progressmeter custom colors
- re-implement toolbarbutton-style all-tabs button
- more closely emulate Firefox 3 toolbarbutton styling
- don't use filters on extension icons
- re-implement back-forward dropmarker in icons+text and text modes
- improve statusbar appearance
- improve titlebar styling on non-compositor Windows when tabs are in titlebar
- Win10: use white window backgrounds on active windows with no accent color applied
- Linux: redesign appmenu button
- minor cleanup

### 2.0.0
- refactor toolbarbutton styling
- refactor tab styling
- unify platform stylings
- add basic OS X support
- add CSS variables for increased customization
- add private browsing indicator in menubar and (Linux only) tabbar
- sync devtools styling with default
- fix appmenu/caption button margins when tabs are in the titlebar
- improve tab appearance in tabs in titlebar mode
- add missing HTTPS icon for devtools network panel
- ensure that all notification panel icons are shown correctly
- fix notification icon selectors
- fix page info dialog styling
- sync plugins UI with default
- PM27.5: draw a background on Win10 for better accent color detection
- remove Social API components
- major cleanup of stylings

### 1.6.0
- sync about:support styling with default
- sync about:permissions styling with default
- add image document favicon when viewing standalone images
- fix "learn more" links in notification popups

### 1.5.1
- provide icon for visited livemarks
- sync devtools styling with default
- style toolbarbutton-badge and allow extensions to style it
- reference download icons correctly
- add border to download items

### 1.5.0
- support PM27's devtools
- drop PM26 support
- use correct margins on all downloads view

### 1.4.0
- PM27: add statusbar styling
- PM27: add styling for downloads panel components
- PM27: style devtools
- improve appearance of about:

### 1.3.0
- titlebar colorisation for Windows 10
- use dark window frame detection on Windows 8/10
- refactor media controls for Pale Moon 26.3
- use unified close button icons
- use dark toolbar detection in Pale Moon 26.3 to detect dark system themes

### 1.2.1
- (PM26) add download location styling

### 1.2.0
- (PM26) add history menu button
- show more icons in history/bookmarks menus
- stability improvements
- correctly style alert box
- fix media controls
- improve alltabs button's appearance when not in the tab bar
- correctly style page info dialog
- use correct new tab button at all times in the tab bar

### 1.1.3
- (Win10) shade window background on Pale Moon 26 builds later than b2

### 1.1.2
- fix vertical toolbar borders

### 1.1.1
- fix tab heights in multirow bars

### 1.1.0
- Pale Moon v26 compatibility
- fix window borders on Windows 10

### 1.0.5
- re-use some browser.css code from previous versions (re-re-base on FF3FF4)
- lift searchbar code directly from Firefox 3
- lift #identity-box and #urlbar code from Firefox 3
- fix download icon
- fix toolbar background + borders
- fix back/forward dropmarker in icons+text mode
- reduce menubar height
- various improvements

### 1.0.4
- re-base several components on Kempelton Reloaded
  - fixes Linux issues
- use PM25's about:addons
- add back/forward dropmarker

### 1.0.3
- use more FF3 icons
- tab bar + new tab fixes

### 1.0.2
- further Firefox 3 stylings

### 1.0.1
- titlebar fix

### 1.0.0
- initial release
- add full Pale Moon compatibility
- integrate userstyles into theme