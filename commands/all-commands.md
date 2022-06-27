# All Commands

### Command Usage

When using a command, prefix it with a `/`\
``Then start typing out the name of the command or select it via the slash command menu.

![Slash Command Menu](<../.gitbook/assets/image (2).png>)

If you click on the PoroScout icon on the left, you can jump to all of the PoroScout commands.\
Click on a command.\
If there are any required arguments, you will need to type them in. When you are done typing in an argument, click `TAB` and it will bring you to the next required argument. When you are finished, once again hit `TAB` to escape the argument typing section. \
Any optional arguments will show up now.\
To provide an optional argument, click on it in the menu and type. Once you are done, click `TAB`

When you finish typing everything, click enter to send the command.\
You should see a **Sending Command...** or a **PoroScout is thinking...**\
Congratulations, you have sent your first PoroScout command!

### All Commands

A list of all PoroScout commands.\
Any argument ending with `*` means it is required.

| Name                                                 | Arguments               | Description                                                                                  |
| ---------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| abilities                                            | `championName*`         | Shows a description of all the abilities of the selected champion.                           |
| about                                                | None                    | Shows info about the bot.                                                                    |
| best                                                 | `elo`, `lane`           | Shows the top champions for the provided elo and lane. (Defaults to low elo and all lanes)   |
| champion                                             | `championName*`, `lane` | Shows a champion's tier, winrate, pickrate, banrate, build path, upgrade path, and runes.    |
| configure patchnotes                                 | `#channel*`             | Start/stop receiving patch note notifications in the provided channel.                       |
| counters                                             | `championName*`, `lane` | Shows a champion's counters.                                                                 |
| link                                                 | `username*`, `region*`  | Link your summoner to the bot.                                                               |
| live                                                 | `username`, `region`    | Check if a summoner is in a game.                                                            |
| mastery                                              | `username`, `region`    | Check the top 10 masteries of a summoner.                                                    |
| matches                                              | `username`, `region`    | Check the last 5 games of a summoner.                                                        |
| patchnotes                                           | None                    | Show the latest patch notes.                                                                 |
| profile                                              | `username`, `region`    | Show a summoner's profile (level, top 3 masteries, recent game, live game, and ranked stats. |
| rotation                                             | None                    | Show the champions on free rotation.                                                         |
| synergies                                            | `championName*`, `lane` | Show a champion's synergies.                                                                 |
| [ultimatebravery](https://www.ultimate-bravery.net/) | None                    | Random champion, random runes, random items, and random summoner spells.                     |
| [graph lp](lp-tracking.md)                           | `username`, `region`    | Displays the summoners LP graph.                                                             |
