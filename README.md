# elevenbot
You'll need a Discord bot to get started. Here is a reference for how to set one up

https://discord.com/developers/docs/getting-started

You'll also need to grab your API key from your ElevenLabs profile

## run
```docker
# create container and run
sudo docker run -d --name elevenbot --env DISCORD_BOT_TOKEN="discord-bot-api-key" --env ELEVENLABS_API="elevenlabs-api-key" tylerplesetz/elevenbot:latest
