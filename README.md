# Request Bot
Request bot allows server owners to keep their "request" channels organized. Whether you get 10, 100, or 1,000 requests by your community, request bot keeps requests inside an embed.  

## Prefix: `!`

## Add Bot: 

https://discord.com/api/oauth2/authorize?client_id=1041848229517611018&permissions=68608&scope=bot

## Permissions needed: 

• Read Messages

• Send Messages

• Manage Messages (only needed for a specific channel)

• Read Message History

## Admin Setup:
There are three commands you need to use to setup Request bot. You can also have the user command and request embed list in the same channel.

`!sync` command will register the bots slash commands to your server.

`!dump` command is for the channel that will post the users requests inside an embed.

`!request` command is to register the public request channel. 

## Admin Commands:
`/unrequest #` command allows an admin to remove a specific request from the embed list. (ex: `/unrequest 3`)

`/edit # <message>` command allows an admin to overwrite a specific request that currently exists. (ex: `/edit 3 my new request`)

`/clear #` command allows an admin to clear a specified amount of messages in the channel.

## User Command
`/request` is the slash command that your community will use to make requests. (ex: `/request More features please`)
