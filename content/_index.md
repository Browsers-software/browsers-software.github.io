+++
title = "Browsers"
sort_by = "weight"
+++

# Browsers

**Browsers** is an intuitive context menu that pops up when you press a link in an app other than a web browser.

- Does not run in the background
- Non-obtrusive design, looking more like a context menu
- Supports user profiles for browsers based on Chrome and Firefox
- Supports Firefox containers (also
  need [Open external links in a container](https://addons.mozilla.org/en-US/firefox/addon/open-url-in-container/)
  extension installed until [#1726634](https://bugzilla.mozilla.org/show_bug.cgi?id=1726634) is resolved)
- Runs on Mac and Linux (Windows is also considered [if there is interest](https://github.com/Browsers-software/browsers/discussions/1))
- Supports opening following desktop applications directly:
    - Figma
    - Linear
    - Notion
    - Spotify
    - Telegram
    - Zoom

# Installation

Download for your platform

- macOS - [**Browsers.dmg**](https://github.com/Browsers-software/browsers/releases/latest/download/Browsers.dmg) (Apple
  Silicon and Intel based Macs)
- Linux - [**browsers_linux.tar.gz**](https://github.com/Browsers-software/browsers/releases/latest/download/browsers_linux.tar.gz) (
  arm64 and x86_64)
- Windows - no plans yet, [vote if you are interested](https://github.com/Browsers-software/browsers/discussions/1)

The app will prompt to set it as default browser on launch which you would need to allow.

# How to Use

- By default, it lists all browsers
- To hide a browser, right click and choose `Hide browser` (or browser profile)
- To restore a hidden browser, click the bottom right menu and find it from the `Restore` submenu
- To move the order of a browser up or down, right click and choose `Move up/down`
- To open a link in incognito/private mode hold down <kbd>⇧ Shift</kbd> while clicking on the browser
- You can also use keyboard to choose the browser:
    - Select previous: <kbd>↑</kbd> or <kbd>⇧ Shift</kbd> + <kbd>⇥ Tab</kbd>
    - Select next: <kbd>↓</kbd> or <kbd>⇥ Tab</kbd>
    - Open in selected browser: <kbd>↵ Enter</kbd> or <kbd>Space</kbd>
- To copy web address to clipboard, click on the web address in the bottom

# FAQ

**Q: Firefox shows two profiles: `default` and `default-release`?**

**A:** Modern Firefox versions use `default-release` as the default profile for stable Firefox release,
so you can hide the `default` profile by right-clicking and choosing `Hide Firefox default`.

If you want to double check which Firefox profile is the default one, open Firefox and enter `about:profiles`
in the address bar and find the profile with `Default Profile` set to `yes`.
