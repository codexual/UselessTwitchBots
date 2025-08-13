# Fossabot Twitch Moderator Setup & Auto-Ban Tutorial

Follow these steps to set up Fossabot with your Twitch channel and start auto-banning useless Twitch bots listed in a `.txt` file.
I will be updating the ban.txt file from time to time!
---

### 1. Login & Give Mod Permission

- Go to [Fossabot.com](https://fossabot.com) and **login with your Twitch account**.
- In your Twitch chat, give Fossabot moderator permissions by typing:

/mod Fossabot

---

### 2. Enable the `!filesay` Command

- From the Fossabot Dashboard, navigate to: Commands -> Default Commands

- Find the `!filesay` command and **enable it**.

---

### ⚠️ WARNING: Auto-Banning Bots Incoming!

The next step will cause Fossabot to start banning usernames listed in the `.txt` file from the GitHub repo.  
**If you see a bot you actually use, make sure to unban it manually before running this!**

---

### 3. Start the Auto-Ban Process

In your Twitch chat, type: !filesay https://github.com/codexual/UselessTwitchBots/blob/main/ban.txt

Watch as Fossabot begins purging the useless Twitch bots! >:D

---

### 3a. How to Stop the Bot

If you want to stop the banning process at any time:

- Make sure the `!filesaystop` command is enabled in Fossabot.
- Then type in chat: !filesaystop


This will immediately stop the bot's auto-ban operation.

---

Enjoy a cleaner chat! 👾




