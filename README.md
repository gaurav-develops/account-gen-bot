<h1 align="center">
	  DISCORD GENERATOR BOT
</h1>

<h3 align="center">
	  INFO
</h3>

It uses a database to store the accounts, which people can generate. The bot has many customization options which can be changed in config.json (will make it even more customizable in next upd). It supports cookies or user/mail : pass.

I haven't made logs yet but i will add it when i feel like updating it.

* Highly customizable.
* Easy to use and lightweight.

<h3 align="center">
	  ERRORS

</h3>

Make sure you have everything installed. Put this inside a `requirements.txt` file
```
discord.py==2.3.2
Requests==2.31.0
typing==3.7.4.3
datetime==5.2
```
Open a console in the folder u made the file in and run this:
```
pip install -r requirements.txt
```

If you get an error related to Privileges/intents go to [discord.dev](https://discord.dev) and enable all the intents for your application. 
(discord.dev -> applications -> choose your application -> bot -> scroll down a bit -> there should be 'Privileged Gateway Intents' -> enable all)

The bot is not sending any messages? Make sure your intents are enabled and the bot has permission to send messages in the channel you're using the bot in. (You also have to specify the channels where the generate command can be used in.)

You dont get a dm from the bot? Make sure your dms are open.

If you have any other errors make a issue about it or you can also message me in discord (you can find my discord on my profile.)
