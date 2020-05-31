# Discord-Reaction-GeneratorBOT
A discord reaction generator Bot! Free to use, simple to set up and very efficient!

# How to Download
- First step of using this bot is to download it (obviously). Click on the green 'Download now' button in the repository page, and save it on your PC.
- Alternatively, you could download this from the command line (if you have Git installed)
- Use the command: git clone https://github.com/4-04/Discord-Reaction-GeneratorBOT/

# Requirements
- You need Python 3.7+ installed
- You need PIP installed. (comes by default with python)
- You need a BOT application and the Bot's token. 

# How to change preferences of this Bot
- make sure to go to the 'discord developer' page and create a new BOT application. If you need help, i'm sure you can find many tutorials on the web on how to make a discord bot, and get the token of that bot, including how to invite it to your server.
- Once you have downloaded this bot you would need to edit the 'config.json' file, which you can find in the 'src' folder. 
- Open it using a text editor (like notepad). Change the value of each key, like this: {"token": "change this over here"}
- Now, as you're done with that, it's still some last part we got to cover. 
-

# How to add generators
- Adding new generators in this bot is actually pretty simple.
- The first thing you got to do when you want to add a new generator is to make a folder. And make sure the folder's name starts with gen_
- So the folder name looks something like this: 'gen_(your generator name here)'
- You can add as many generators as you would like.

# How to add files in the generators
- When you have added the folders, you would need to add files in the folder. Creating a file is simple, you can also rename the file to what you want. Just make sure to put the file in the correct folder!
- In each file of all generators you need to put two mandatory things. In the first line you would need to put the EMOJI ID that you wish to use.
- In the second line of the file you would need to but the cooldown for that file (in second). If you want to cooldown simply set that line to 0.

# Bot commands
- Once you have added the folders, and some files inside the folders, including the emoji ID and the Cooldown in all files you are ready to go!
- Make sure you have Python installed and Pip. I recomend searching for some youtube tutorials on how to download those.
- (If you encounter any bugs, such as 'module discord not found'), then run this command from terminal: 'pip install (module that was not found)'
- When you have set that up, you are soon finished!
- First of all you would need to start the bot. Run the 'main.py' file, either by double clicking or by using the terminal.
- Once you have started the bot you can run this command in the server of the bot: (prefix)start (generator name)
- The bot will automatically recognize all files in the generator as valid files, and the reactions will automatically added and the cooldown automatically applied. You can run as many generators at a time as you would want.
