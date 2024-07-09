# discord.py-user
A modification of discord.py that lets you make selfbots.


# How to use?
**NOTE: IF YOU HAVE DISCORD.PY INSTALLED ON YOUR WHOLE PC THEN OPEN IN DIR AND RUN `pip uninstall discord.py` AND `pip uninstall discord`

First, run the command **below**:
```pip install git+https://github.com/eyesdev/discord.py-user.git```

After that, enjoy! You can make a bot with **this example**:
```py
import discord
from discord.ext import commands

bot = commands.Bot(command_prefix='.', self_bot=True)

@bot.command()
async def ping(ctx):
    await ctx.send('pong')

bot.run('here you enter your token')```
