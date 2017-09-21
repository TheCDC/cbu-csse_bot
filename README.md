# Description
A bot for the CBU ACM Computing Club Slack channel

# Setup
This bot is designed to be deployed on heroku. 

First create a file named `.env` in the root directory of the repo. Its contents should look like this:
```
SLACK_BOT_TOKEN=x***-************-************************
BOT_ID=*********
```

This `.env` file is how Heroku supplies environment variables to the app. These environment variables are necessary for the bot to interact with/have access to a particular channel.

When the .env is in place you can run the bot locally with `heroku local`.