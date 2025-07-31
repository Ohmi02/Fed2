# Fed2
These are Mudlet packages designed for the Federation 2 Community Edition text-based game. See https://federation2.com/ for more information.

Two packages are available: the standalone fed2mapper package that has no UI elements, or the fed2ui package that contains a lightweight UI and includes the mapper. Plese remove the Generic Mapper package before using either of these packages.

## fed2mapper

standalone mapper for Federation 2 Community Edition

This mapper is designed to work with Federation 2 Community Edition. This is the standalone version that does not include any other GUI. Does not support speedwalking. Please remove the Generic Mapper package before using.

The mapper uses GMCP events only and is a bare-bones mapper designed to 'just work'. No need to turn it on, it automatically runs when it receives room data. It will intelligently identify and mark shuttlepads, exchanges, planets, and link gates on the map.

Also included are some aliases allowing light map editing from the command line, such as setting room colors, room symbols, doors (cosmetic only), shifting or moving rooms entirely, as well as resetting rooms or wiping the entire map. See 'fedmap help' for a full list of aliases.

## fed2ui

basic UI and mapper for Federation 2 Community Edition

This is a basic interface that breaks out useful information into separate windows. Exchange spam goes on the left, useful stats on top, a mapper on the top right, and a copy of chat on the bottom right.

Please remove the generic_mapper package, as it may conflict with the fed2mapper.

Currently colors and font sizes are hardcoded. Customization is planned in a future update.

This primarily uses GMCP events to collect information, with some aliases designed to catch outgoing chat and copy it into the chat window. Exchange spam is caught entirely through triggers. T_T The mapper uses GMCP events and is always on, but has some aliases allowing basic map editing. See 'fedmap help' for more information.
