---
title: YourGPT Bot Documentation
sidebar: true # or false to display the sidebar
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: true # or false to display the footer
layout: single
---

# Twitch Bot Documentation

## Introduction
The Twitch Bot is a custom bot based on ChatGPT, designed to provide various functionalities for Twitch streamers and their viewers. This documentation provides an overview of the commands available in the Twitch Bot and how to use them.

## Commands

### !yourgpt help
Syntax: `!yourgpt help`

Description: The `!yourgpt help` command displays a list of available commands and their descriptions to help users understand how to interact with the Twitch Bot.

Example usage:
```
!yourgpt help
```


### !yourgpt update_bio <text>
Syntax: `!yourgpt update_bio <text>`

Description: The `!yourgpt update_bio` command allows users to set a custom biography for the Twitch Bot, giving it a personality and providing information such as where it works, what it usually does, and its favorite streamer.

Example usage:
```
!yourgpt update_bio "Hi, I'm ChatGPT, your friendly Twitch bot! I work at the Twitch HQ, love interacting with viewers, and enjoy watching streams with my favorite streamer, @TwitchStreamer!"
```


### !yourgpt update_trigger_words <words separated by comma>
Syntax: `!yourgpt update_trigger_words <words separated by comma>`

Description: The `!yourgpt update_trigger_words` command allows users to set trigger words or phrases that, when mentioned in the chat, will activate the Twitch Bot and trigger a response. This allows users to customize the keywords that will activate the bot and engage with their audience.

Example usage:
```
!yourgpt update_trigger_words hello,hi,greetings,bot
```


Note: Trigger words should be separated by commas without spaces.
