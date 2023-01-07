## Background 
I thought switching to a Mac from Linux would be a breeze, but oh boy was I wrong! The keyboard mapping has been giving me a run for my money. The fact that I'm using the Nordic layout doesn't make things any better either, as I've found that the Nordic layout on a Mac is almost unbearable for programming (three keys have to be pressed to make a curly bracket). But hey, at least I have a shiny new computer to show for it.

This repo contains a config file for Karabiner which I have used to remap the keyboard to a Windows/Linux Keyboard layout, without the need for switching command and ctrl in the macOS preferences.

## Set up shortcuts for Karabiner
1. Install Karabiner:   https://github.com/pqrs-org/Karabiner-Elements
2.  Move the config-file to the Karabiner directory: <code>cp karabiner.json ~/.config/karabiner/karabiner.json </code>

## Edit shortcuts 
1.  Open shortcuts in VScode:
      * <code>code ~/.config/karabiner/karabiner.json</code>
2. Move config-file back to this repo
      * <code>cp ~/.config/karabiner/karabiner.json karabiner.json</code> 
3. Deactivate the standard system-shortcuts in macOS


## Other tools 
* AltTab
* Rectangle 
* 

<!-- # Overall idea
- Make macOS behave more like Microsoft Windows
- No need to switch command and ctrl in macOS preferences

## Install shortcuts to Karabiner
1. Install Karabiner
2. cp ./karabiner.json ~/.config/karabiner/karabiner.json

## Open karabiner file and edit it in VS Code
code ~/.config/karabiner/karabiner.json

## Log files such as parse errors
code ~/.local/share/karabiner/log/console_user_server.log

## Copy Karabiner configuration to this folder
- cp ~/.config/karabiner/karabiner.json ./karabiner.json

## Reminder
- On an external keyboard:
  * ctrl: command ⌘
  * windows: ctrl ⌃
  * alt: option ⌥
  * shift: shift ⇧


## Karabiner resources
- https://github.com/aerobounce/karabiner-elements-keycodes/blob/master/key_code.hpp
  * Key codes
- https://karabiner-elements.pqrs.org/docs/
  * Documentation
- https://support.apple.com/en-us/HT201236
  * macOS default shortcuts that can’t be disabled via preferences
- https://support.apple.com/sv-se/guide/terminal/trmlshtcts/mac
  * Terminal shortcuts


## Other apps to install to make macOS more Windows like
- uBar
  * Windows like navigation bar
  * https://brawersoftware.com/products/ubar
- AltTab
  * Windows like Alt+Tab
  * https://alt-tab-macos.netlify.app/
- Rectangle
  * Move and resize windows in macOS using keyboard shortcuts or snap areas
  * https://rectangleapp.com/
- Shortkeys (Chrome extension)
  * Custom shortcuts for Chrome
  * https://chrome.google.com/webstore/detail/shortkeys-custom-keyboard/logpjaacgmcbpdkdchjiaagddngobkck?hl=en-US&gl=US

## macOS keyboard preferences
- Disable all shortcuts
- Mission Control
  * Move space left/right
- Screenshots
  * Copy image to pasteboard
- Spotlight
  * Show Spotlight


## Navbar
- Auto hide

## Rectangle
- Map win+left/right/up/down

## Shortkeys (Chrome extension)
- not remapped in Karabiner:
  * f5, reload, Reload page
- normally works, but Karabiner word navigation shortcut messed it up
  * ctrl+left, back, Go back
  * ctrl+right, forward, Go forward -->
