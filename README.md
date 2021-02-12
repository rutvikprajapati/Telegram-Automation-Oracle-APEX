# Telegram-Automation-Oracle-APEX

Steps to configure this application.

1. Create telegram bot and get API token.
2. Add the bot in your Telegram group and promote it as an Admin.
3. Login to Application and add API token in "Bot Setting" menu.
4. Go to Groups and click on Refresh button to get the chat-id of Telegram group. If the group does not appear then send a message in your telegram group from your account and try again. This is expected as sometime we get blank response from getUpdates method. 
5. Create and schedule the message. 
