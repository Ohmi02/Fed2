# Fed2
These are [Mudlet](https://wiki.mudlet.org/w/Main_Page) packages designed for the [Federation 2 Community Edition](https://federation2.com) text-based space trading game.

Two packages are available: the standalone fed2mapper package that has no UI elements, or the fed2ui package that contains a lightweight UI and includes the mapper. Plese remove the Generic Mapper package before installing the fed2mapper. The fed2ui package will uninstall Generic Mapper on its own.

## fed2ui screenshot
![Screenshot of the v1.2 fed2ui interface](https://raw.githubusercontent.com/Ohmi02/Fed2/refs/heads/main/fed2ui_screenshot.PNG)

## Install Instructions
- Download either fed2ui.mpackage or fed2mapper.mpackage and place it in the directory of your choice.
- Open Mudlet, click on the 'Packages' button in the menu bar.
- Select 'Install new package' in the window that appears, navigate to where you placed your mpackage, and select it.

## Change Log
- *fed2ui v1.3*:
  + Fixed adjustable windows not actually being adjustable
  + Cargo window will now clear itself before displaying cargo
  + Added a toggle so you can tell the UI not to automatically build istelf on install
  + Added auto uninstall of Generic Mapper
- *fed2ui v1.2*:
  + UI will automatically build itself on install
 ## To Do
 - Fuel and Stamina should turn alarming colors when low
 - Better triggers/logic for catching exchange spam
 - Aliases so the UI will respect when the in-game default colors for chat and exchange messages are changed
 - Add logic to catch XT chat 

# fed2mapper
standalone mapper for Federation 2 Community Edition

This mapper is designed to work with Federation 2 Community Edition. This is the standalone version that does not include any other GUI. Does not support speedwalking. Please remove the Generic Mapper package before using. Display the map by clicking on the 'Map' icon in the Mudlet toolbar.

The mapper uses GMCP events only and is a bare-bones mapper designed to 'just work'. No need to turn it on, it automatically runs when it receives room data. It will intelligently identify and mark shuttlepads, exchanges, planets, and link gates on the map.

Also included are some aliases allowing light map editing from the command line, such as setting room colors, room symbols, doors (cosmetic only), shifting or moving rooms entirely, as well as resetting rooms or wiping the entire map. See 'fedmap help' for a full list of aliases.

# fed2ui
basic UI and mapper for Federation 2 Community Edition

This is a basic interface that breaks out useful information into separate windows. Exchange spam goes on the left, useful stats on top, a mapper on the top right, and a copy of chat on the bottom right.

Currently colors and font sizes are hardcoded. Customization is planned in a future update.

This primarily uses GMCP events to collect information, with some aliases designed to catch outgoing chat and copy it into the chat window. Exchange spam is caught entirely through triggers. T_T The mapper uses GMCP events and is always on, but has some aliases allowing basic map editing. See 'fedmap help' for more information.
