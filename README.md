# Discord TicketBot

## Installation on a Linux Server:


1. Make sure Node.js is installed on your Linux server.

2. Navigate to the directory where the Discord bot is located and run the command npm install to install all dependencies.

3. Open the file config.json and fill in the following fields:

```json

{
    "token": "YOUR_DISCORD_BOT_TOKEN",
    "ticketChannel": "ID_OF_TICKET_CHANNEL",
    "ticketCategory": "ID_OF_TICKET_CATEGORY",
    "roleSupport": "ID_OF_SUPPORT_ROLE"
}

```
Replace YOUR_DISCORD_BOT_TOKEN with the bot token you obtained from the Discord Developer Portal. Replace ID_OF_TICKET_CHANNEL, ID_OF_TICKET_CATEGORY, and ID_OF_SUPPORT_ROLE with the corresponding IDs from your Discord configuration.

You can find and copy emojis from https://getemoji.com/ to use them in the configuration.

Save config.json.


Start the bot using the command npm start. The bot should come online and be ready to use.


Installation on a Windows Server:

Ensure Node.js is installed on your Windows system.

Open Command Prompt or PowerShell and navigate to the directory of the Discord bot.

Run the command npm install to install all dependencies.

Edit config.json following the instructions in the Linux installation.

Start the bot by typing npm start in Command Prompt or PowerShell.

The bot should now be online and available on Discord.



If you need further assistance, please join our Discord and open a ticket. We are happy to help!

Discord: https://discord.gg/kXf3G9DMPt
