# :robot: Doraemon
**A multipurpose Discord Bot that has the commands commonly used on every server, like Moderation, Fun, Playing Music and much more.**

[![Doraemon's Widget](https://api.botlist.space/widget/709321027775365150/4 "Doraemon's Widget")](https://botlist.space/bot/709321027775365150?utm_source=bls&utm_medium=widget&utm_campaign=709321027775365150&rounded=true&shadows=true)

[Invite the bot to your server](https://discord.com/api/oauth2/authorize?client_id=709321027775365150&permissions=8&scope=bot)

<ins>**Bot Commands**</ins>

**__General__**

`-about` - To know about the bot.  
`-ping` - Check the bot's latency.  
`-github` - Github Repo.  
`-stats` - Check the bot's stats.  
`-invite` - Get the invite link for the bot.  

**__Fun__**

`-8ball <your question>` - Play magic 8 Ball and get the answers to all your questions.  
`-meme` - Get a random meme from reddit.  
`-gif <query>` - Get a random GIF from tanor on the specified query.  
`-reddit <subreddit>|<query>` - Search for posts in the specified subreddit.  

**__Reactions__**

`-laugh`
`-shrug`
`-hug <user>`
`-cry`
`-pat <user>`

**__Moderation__**

`-clear <amount of messages>` - Clears the specified no. of messages.(default=1)  
`-kick <member> <reason>` - Kicks a member out of the server.  
`-ban <member> <reason>` - Bans a member in the server.  
`-unban <member>` - Unbans the member in the server.  
`-count` - Count of messages in a channel.  
`-info` - General Info of a member.  
`-serverinfo` - General Info of the Server  

**__Utility__**

`-lmgtfy <question>` -  Returns a [lmgtfy.com](https://lmgtfy.com/) link.  
`-poll <title>|<description>|<option 1>|<option 2>|<option n>` - Create polls on strawpolls right in discord.  


<ins>**Coming Soon**</ins>

- Music
- Web Dashboard


<ins>**Setup**</ins>

- Clone the repo with `git clone https://github.com/pratishrai/doraemon`
- Install the requirements using `pip3 install -r requirements.txt`
- Create a `.env` file with the following:
    > `BOT_TOKEN=<your bot token>`  
     `URI=<your mongodb URI>`  
     `TENOR_API=<your tenor API>`  
     `CLIENT_ID=<your reddit application id>`  
     `CLIENT_SECRET=<your reddit application secret>`  
     `STRAWPOLL_KEY=<your strawpoll api key>`
- You can now run the bot using `python3 doraemon.py`


