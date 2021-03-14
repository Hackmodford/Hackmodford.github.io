---
title: How To Improve the macOS Dock
tags: [macOS]
style: border
color: info
description: These four “clean code” tips will dramatically improve your engineering team’s productivity
---

Screen space on a laptop comes at a high premium. On macOS one of the most important interface elements is the Dock. Unfortunately it’s in the way more times than not. If you’re like me, you might have tried hiding the dock but eventually switch back because of how long it takes for the dock to re-appear when the mouse is at the edge of the screen.

I believe I have found a solution for this problem. Try these two commands in terminal:

```
defaults write com.apple.dock autohide-delay -int 0
defaults write com.apple.dock autohide-time-modifier -float 0.4
killall Dock
```

These commands will disable the delay but also leave the pleasantly smooth animation intact.
We care about these things because we’re macOS users. 😉

If you decide this tweak isn’t for you, you can enter this into the terminal

```
defaults delete com.apple.dock autohide-delay
defaults delete com.apple.dock autohide-time-modifier
killall Dock
```

Enjoy!