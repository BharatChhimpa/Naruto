## Txt Extractor Bot

This is a Telegram bot that extracts URLs from text files. It supports a variety of apps and can be used to extract URLs from APKs.

## How to Deploy

1. **Configure config.py**
   - Replace all placeholder values in `config.py` with your actual data:
   - `BOT_TOKEN`: Get from [@BotFather](https://t.me/BotFather)
   - `API_ID` and `API_HASH`: Get from [my.telegram.org](https://my.telegram.org)
   - `ADMIN`: Add your Telegram user IDs (comma-separated)
   - `DB_URL`: Your MongoDB connection string
   - `DB_NAME`: Your database name
   - Set up your channel IDs for:
     - `TXT_LOG`
     - `AUTH_LOG`
     - `HIT_LOG`
     - `DRM_DUMP`
     - `CHANNEL`
   - `CH_URL`: Your channel's invite link
   - `OWNER`: Your Telegram profile link
   - `THUMB_URL`: URL for bot thumbnail image

2. **Update msg.py**
   - Find and replace the default username with your Telegram username
   - Customize any message texts if needed

3. **Deploy to Heroku**
   - Click the deploy button below
   - Fill in the environment variables if prompted
   - Wait for the build to complete

## Deploy To Heroku

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https://github.com/&template=https://github.com/BharatChhimpa/Naruto)

## Note
- Make sure all your channels and groups are created before deployment and bot made admin in all the channels
- Keep your API credentials and tokens secure
- Test the bot locally before deploying to production
