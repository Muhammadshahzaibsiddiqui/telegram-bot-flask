# Python Flask Telebot

This project entails setting up a Flask website integrated with a MySQL database.

## Setup

1. **Import MySQL Database:**
   Import the provided MySQL database into your system.

2. **Setup Website:**
   - Initialize the website application in `app.py`.
   - Create necessary templates for the website.

3. **Configure Database:**
   Configure the database connection in the `app.py` file.

# Bot

The Telegram bot operates through polling to receive and send messages between users and groups. Once configured and running, the bot will respond to commands, process incoming messages, and perform automated tasks as programmed.

## Setup

1. **API Token Setup:**
   Add the following api token to your bot-related files:
   ```python
   bot = telebot.TeleBot('YOUR_API_TOKEN')
2. **Telebot Folder Setup:**
   - Run this `getChannelMembers.py` to create neccessary files.

3. **Cron Job Setup:**
   - Configure a cron job for the `getChannelMembers.py` file.
   - After the first cron job completes, set up a cron job for the `addMembersToGroup.py` file.

4. **Bot Auto-Reply:**
   - Ensure `botReply.py` runs continuously to auto-reply to users.

4. **To Run:**
   - Python `botReply.py`


