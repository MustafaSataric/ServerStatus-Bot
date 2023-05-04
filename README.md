# FiveM-Status-Discord-Bot by Mustafa
 

# Do not put this in your server resources, this is ment to run outside of your server and will not work if you try to run it of your server

FiveM server status bot, this will display how many users are online in your server thru the status of a discord bot.
Please try to find out why your code is not working your self before trying to contact me because this a really simply project and should not be hard to understand.

# Instruction to set up the Bot

Open the config.json file add your Bot Token, Servername, Server IP and Ports you can find it here:

Discord Developer Portal | https://discord.com/developers/applications

# Instruction to run the Bot on an linux machine:

>1. Install the bot and update the machine </br>
`git clone https://github.com/MustafaSataric/ServerStatus-Bot` </br>
`sudo apt-get update && sudo apt-get upgrade` </br>
`cd /ServerStatus-Bot`

>2. Install Node JS </br>
`sudo apt-get install nodejs`

>3. Check Node JS installation, if it doesn't work you have to fix it to launch the bot. </br>
`node -v`

>4. Now you have to install pm2 to run the bot in the background </br>
`npm install pm2 -g`

>5. Now you have to run the index.js </br>
`pm2 start index.js`




