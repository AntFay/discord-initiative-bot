# Initiative Bot for Discord
Discord bot script for tracking turn order in Tabletop RPGs

## Commands
- **$add [name] [initiative roll]** - add a unit to the initiative order
- **$order** - show initiative order
- **$remove [rank]** - removes a unit from the specified rank in initiative
- **$switch [rank 1] [rank 2]** - swaps units at specified ranks
- **$name [rank] [new name]** - renames a unit at the specified rank in initiative
- **$reset** - clears the initiative table

## Setup

### Windows
1. Install [node.js] (https://nodejs.org/en/)
2. Clone the project in desired folder: `git clone https://github.com/AntFay/discord-initiative-bot.git`
3. Alternatively, use the green download button at the top of the page to download a zip folder containing the project files.
4. Set up a new bot account through your discord [application page] (https://discordapp.com/developers/applications/)
5. Change `config.json.example` in the project directory to `config.json`, and add your discord application's auth token from your bot's application page.
6. Run `npm install` in the main project directory.
7. Run `node bot.js` to start the bot.
