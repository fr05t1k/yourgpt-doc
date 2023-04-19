---
title: YourGPT Bot Documentation
sidebar: false # or false to display the sidebar
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: true # or false to display the footer
layout: single
---
## Introduction
The Twitch Bot is a custom bot based on ChatGPT, designed to provide various functionalities for Twitch streamers and their viewers. This documentation provides an overview of the commands available in the Twitch Bot and how to use them.

## Commands

### !yg help
Syntax: `!yg help`

Description: The `!yg help` command displays a list of available commands and their descriptions to help users understand how to interact with the Twitch Bot.

Example usage:
```
!yg help
```

### !yg bio
Syntax: `!yg bio`

Description: The `!yg bio` command displays the biography of the Twitch Bot, which can be customized by the user.

### !yg bio <text>
Syntax: `!yg bio <text>`

Description: The `!yg bio` command allows users to set a custom biography for the Twitch Bot, giving it a personality and providing information such as where it works, what it usually does, and its favorite streamer.

Example usage:
```
!yg bio "Hi, I'm ChatGPT, your friendly Twitch bot! I work at the Twitch HQ, love interacting with viewers, and enjoy watching streams with my favorite streamer, @TwitchStreamer!"
```

### !yg trigger_words 
Syntax: `!yg trigger_words `

Description: The `!yg trigger_words` command displays the current trigger words or phrases that, when mentioned in the chat, will activate the Twitch Bot and trigger a response.

### !yg trigger_words <words separated by comma>
Syntax: `!yg trigger_words <words separated by comma>`

Description: The `!yg trigger_words` command allows users to set trigger words or phrases that, when mentioned in the chat, will activate the Twitch Bot and trigger a response. This allows users to customize the keywords that will activate the bot and engage with their audience.

Example usage:
```
!yg trigger_words hello,hi,greetings,bot
```

Note: Trigger words should be separated by commas without spaces.


### !yg welcome_message
Syntax: `!yg welcome_message `

Description: The `!yg welcome_message` command displays the current welcome message that will be displayed when a new viewer joins the chat.


### !yg welcome_message (true|false)
Syntax: `!yg welcome_message (true|false)`

Description: The `!yg welcome_message (true|false)` command allows users to enable or disable the welcome message that will be displayed when a new viewer joins the chat.

Example usage:
```
!yg welcome_message true
```
