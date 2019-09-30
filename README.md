
# ShuviBot

This repository merely exists to document all legal stuff regarding my Discord Bot Shuvi.

# License

Shuvi itself along side It's website, while closed source, are licensed under <code>Apache License 2.0</code> you can find the License in [this repository](https://github.com/ShuviBot/Shuvi-Legal/blob/master/LICENSE).

# Copyright Notices

### discord.js-commando 
Shuvi uses a modified version of [discord.js-commando](https://github.com/Gawdl3y/discord.js-commando/blob/master/LICENSE) which is licensed under <code>Apache License 2.0</code>

The following changes were made:
- Changed all default responses to no longer mention the user.
- Changed the text of some default responses
- Removed Support for Direct Messages
- Added Support for disabling categories and commands on a channel specific base and disabling specific channels entirely.
- Added support for disallowing roles specific commands
- Added support for Sub-Commands
- Reworked command parsing to allow parsing of flags (i.E: --hidden)
- Removed prompts entirely
- Changed how argument validation is handled (now returns a message if validation fails)
- Extended Guild Extension with Custom Settings
- Rewrote the Entire Provider Function to be more reasonable with MySQL
- Renamed Commando references to Shuvi (i.e CommandoClient -> ShuviClient)
- Removed args-typing system
- Added support for in-depth Music manipulation
