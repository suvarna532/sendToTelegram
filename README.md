Open Telegram and go to the search bar. Type "BotFather" and select the BotFather chat. Then, click on "start" to initiate a conversation with BotFather.
In the BotFather chat, type "/newbot" or click on "/newbot" in the menu displayed by BotFather.
Follow the instructions provided by BotFather. You'll need to give your bot a name and a username. Once you've completed the process, BotFather will provide you with an API Key for your new bot. Copy and securely store this API Key. To ensure the bot is created successfully, start a chat with it by sending a message like "Hello."
Download the "sendMessageToTelegram.py" script from the this repository and save it on your local machine. Open the script and replace the value of the "bot_token" variable with the API Key provided by BotFather.
Edit the message content within the "payload" variable, which is formatted as "text" in JSON.
Save the changes to the Python file and execute it. Upon execution, the message specified in the "payload" variable will be sent to your Telegram bot's chat.
