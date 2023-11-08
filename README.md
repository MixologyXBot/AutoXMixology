

## Features
— IMDB Template Set

— Index Files Above 2GB

— PreDVD and CamRip Delete Mode

— Multiple File Deletion

— Settings Menu 

— Force Subscription

— Welcome Message

— Automatic File Filtering

— Double Filter Button

— Single Filter Button

— Bot PM File Send Mode

— Auto File Send

— Forward Restriction

— File Protect

— Manual File Filtering

— Global File Filtering

— IMDB

— Admin Commands

— User Broadcast

— Group Broadcast

— Index

— IMDB search

— Inline Search

— Random pics

— ids and User info

— Stats

— Users

— Chats

— User Ban

— User Unban

— Chat Leave

— Chat Disable

— Channel

— Spelling Check Feature

— File Store

— Auto Delete

— And More...

## Commands 🫡
```
/invite - To get the invite link of any chat which the bot is admin
/logs - To get the recent errors
/stats - To get status of files in DB
/connections - To see all connected groups
/settings - To open settings menu
/filter - Add manual filters
/filters - View filters
/connect - Connect to PM
/disconnect - Disconnect from PM
/del - Delete a filter 
/delall - Delete all filters
/deleteall - Delete all indexed files
/delete - Delete a specific file from index
/info - Get user info
/id - Get TG ids
/imdb - Fetch info from IMDB
/search - To search from various sources
/start - To start the bot
/setskip - To skip number of message when indexing files
/users - To get list of my users and ids
/chats - To get list of my chats and ids
/leave - Leave from a chat
/disable - Disable a Chat
/enable - Re-enable chat
/ban - Ban a user
/unban - Unban a user
/channel - Get list of total connected channels
/broadcast - Broadcast a message to all users
/grp_broadcast - Broadcast a message to all connected groups
/batch - Create link for multiple posts
/link - Create link for one post
/status - Your Heroku API key to check dyno, Bot uptime and bot working day prediction
/set_template - Set a custom IMDB template for individual groups
/gfilter - Add global filters
/gfilters - View list of all global filters
/delg - Delete a specific global filter
/delallg - Delete all global filters from the bot's Database
/deletefiles - Delete PreDVD and CamRip files from the bot's Database
```

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com).
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used separated by space )
* `FILE_STORE_CHANNEL`: Channel from were file store links of posts should be made.Separate multiple IDs by space
* Check [info.py](https://github.com/Rohaniscoder/EasyAdvAutoFilter/blob/main/info.py
) for more optional variables


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Rohaniscoder/EasyAdvAutoFilter)

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=https://github.com/Rohaniscoder/EasyAdvAutoFilter&branch=main&name=EasyAdvAutoFilter)

.[![Deploy on Railway](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github/Rohaniscoder/EasyAdvAutoFilter) 

.[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/y0ryFO) 

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/Rohaniscoder/EasyAdvAutoFilter
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>
