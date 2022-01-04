---
layout: default
---
# Introduction

![](media/images/screenshot.jpg)
No more need to memorize shortcut keys! Osara(お皿) brings Command Platte to all your apps. With Osara, you can access all the menu items via a simple shortkey.

<p class="producthunt-link">
<a href="https://www.producthunt.com/posts/osara?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-osara" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=295829&theme=light" alt="Osara - Osara brings Command Palette for app menus to all your apps | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</p>

# Features

- Fuzzy match
    - Use leading `:` to force exact match with fuzzy match enabled!
- Customizable shortcut key
- Customizable appearance
- Dark mode support

# Download

The newest version can be downloaded at [AppCenter](https://install.appcenter.ms/users/waynezhang/apps/osara/distribution_groups/public).

# Installation

1. Unzip downloaded file and place `Osara.app` into `/Applications`.
2. At the first launch, app will ask you to grant Accessibility permission. Open `System Preferences` -> `Security & Privacy` -> `Accessibility` and check `Osara.app`.
3. Open `Preference` of Osara from menu bar and set a shortcut.
4. Try that shortcut in some app!

# Changelogs

- 2021/10/17 v1.9.0
    - Support PageUp(Fn + Up Arrow) and PageDown(Fn + Down Arrow) in search results
- 2021/10/17 v1.8.0
    - Experimental Added Remember last used menu. It can be turned on from Preference
    - Fixed Issue Text field can not be focused on sometimes.
- 2021/05/21 v1.7.1
    - Truncate long title correctly
    - Fix text color issue in dark mode
    - Performance improvement
- 2021/05/07 v1.7.0
    - First public release
![](media/images/installation.jpg)

# FAQ

- Is Osara free?
    > Yes. Osara is free of use. Please consider <a href='https://ko-fi.com/S6S44JFTQ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi3.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a> to support the development if you find it useful.
- Why Osara is not distributed via App Store?
    > Osara uses Accessibility API to gather menu information from other applications. This is disabled in Sandbox apps. But don't worry. Osara is [nortarized](https://developer.apple.com/documentation/security/notarizing_macos_software_before_distribution) by Apple and signed by a valid developer certificate.
