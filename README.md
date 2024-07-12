# Discord-raider
A discord bot to delete all channels , roles , custom emojis and ban all members from a discord server. In short raiding a server.
Disclaimer:
This is for educational purposes only. Use this only if you have the consent of the server owner. I am not responsible for any damage done by this bot.
Setup
Make sure you have Python and Git

Create a new app on the Developer Portal

Make sure to enable the Members intent on the portal

Download repo using git clone https://github.com/kry0sc0pic/Raider.git

Open the raider folder

Open the config.json file

Copy and paste the code block and fill in necessary details

TOKEN bot token from the developer page
TRIGGER Trigger word to initiate deletion
INVITE_LINK Invite link for the bot with required permissions integer , used to invite bot to the server to be deleted
BAN_MESSAGE Message used as reason for ban
NEW_NAME Name the server name has to be edited to be
IMAGE_PATH Path to the new server icon you want


{
    "TOKEN": "<YOUR-BOT-TOKEN>",
    "TRIGGER": "<TRIGGER-WORD>",
    "INVITE_LINK": "<INVITE-LINK>",
    "BAN_MESSAGE": "<BAN-REASON>",
    "NEW_NAME": "<NEW-SERVER-NAME>",
    "IMAGE_PATH": "<PATH-TO-NEW-LOGO-FILE>"
}
