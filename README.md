## Install

https://discord.com/oauth2/authorize?client_id=1232394493546856609

> # __Current Version__
> ## Version 1.0.3


**xBEARR.AI** requires the ability to:
- send messages
- read message history (data is not collected)
	- EXCEPTION: Prompts and **userID's** are collected for logging purposes
- add attachments
	- not a feature thats available now, but something that will be added later

## Version 1.0.0
- Introduced groq implementation using GROQ API.
	- `!groq <query>`
- Introduced `!ping` command to test if bot was online/available

## Version 1.0.1
- Changed prefix to `x` to be uniform with xBEARR
- Added and about page
	- `xabout`
- Added Slash functionality

## Version 1.0.2
- Added `xf1stats` to list of commands available
  	- `results`
  	- `standings`
  	- `nextrace`
  	- `drivers`
  	- `leaderboard`
- Added custom emojis to some responses

## Version 1.0.3
- Changed `xbearr` to `xq` or `/q` for queries 
- Added `xsummarize` to list of commands
	- Takes the following parameters:
 		- `topic:`
   		- `number of messages`
- Removed `xf1stats` because the command tree was too convoluted
- Changed Groq model for summaries to `Mixtral 8x7B (32756)`


## Roadmap 2024
- [ ] Add Websearch functionality
- [ ] Beautify with emojis and embed features 
- [ ] Ability to choose models? (Haven't decided yet)
- [ ] Migrate to a server to handle more servers
- [ ] Attachments and Image Generation




