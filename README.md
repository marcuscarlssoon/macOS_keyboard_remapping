## Background 
I thought switching to a Mac from Ubuntu would be a breeze, but oh boy was I wrong! The keyboard mapping has been giving me a run for my money. The fact that I'm using the Nordic layout doesn't make things any better either, as I've found that the Nordic layout on a Mac is almost unbearable for programming (three keys have to be pressed to make a curly bracket). But hey, at least I have a shiny new computer to show for it.

This repo contains a config file for Karabiner which I have used to remap the keyboard to a Windows-like layout with Ubuntu-like shortcuts, without the need for switching command and ctrl in the macOS preferences.

## Set up shortcuts for Karabiner
1. Install Karabiner:   https://github.com/pqrs-org/Karabiner-Elements
2. Clone this repo, it contains a cofig-file for Karabiner, aswell ass a Applescript to open the terminal at the current location in finder.
3. Move the config-file to the Karabiner directory: <code>cp karabiner.json ~/.config/karabiner/karabiner.json </code>
4. Disable **ALL** macOS shortcuts under keyboard -> shortcuts in the settings.

## Edit shortcuts 
1.  Open shortcuts in VScode:
      * <code>code ~/.config/karabiner/karabiner.json</code>
2. Move config-file back to this repo
      * <code>cp ~/.config/karabiner/karabiner.json karabiner.json</code> 

 I have these two set up as an aliases in zsh: 
 
 For editing in VScode: <code>echo 'alias shortcut_edit="code ~/.config/karabiner/karabiner.json"' >> ~/zshrc</code>. To run it, just write write shortcut_edit in an zsh-terminal.
 
 For syncing the config-file with the repo: <code>echo 'alias shortcut_sync="cp ~/.config/karabiner/karabiner.json ~/YOUR REPO PATH/karabiner.json' >> ~/.zshrc</code>. Run it by writings hortcut_sync in an zsh-terminal.

Documentation for Karabiner json: https://karabiner-elements.pqrs.org/docs/json/

## Other tools I use to make macOS feel more like Linux
* AltTab: https://alt-tab-macos.netlify.app/
* Rectangle: https://rectangleapp.com/
* CopyQ: https://github.com/hluk/CopyQ
