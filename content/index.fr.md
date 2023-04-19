---
title: Documentation YourGPT Bot
sidebar: false # or false to display the sidebar
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: true # or false to display the footer
layout: single
---
## Introduction
Le Twitch Bot est un bot personnalisé basé sur ChatGPT, conçu pour fournir différentes fonctionnalités aux streamers Twitch et à leurs spectateurs. Cette documentation fournit un aperçu des commandes disponibles dans le Twitch Bot et de leur utilisation.

## Commandes

### !yg help
Syntaxe: `!yg help`

Description: La commande `!yg help` affiche une liste de commandes disponibles et leurs descriptions pour aider les utilisateurs à comprendre comment interagir avec le Twitch Bot.

Exemple d'utilisation:
```
!yg help
```



### !yg bio
Syntaxe: `!yg bio`

Description: La commande `!yg bio` affiche la biographie du Twitch Bot, qui peut être personnalisée par l'utilisateur.

### !yg bio <text>
Syntaxe: `!yg bio <text>`

Description: La commande `!yg bio` permet aux utilisateurs de définir une biographie personnalisée pour le Twitch Bot, lui donnant une personnalité et fournissant des informations telles que où il travaille, ce qu'il fait habituellement et son streamer préféré.
### !yg bio
Syntaxe : `!yg bio <bio>` 

Description : La commande `!yg bio` permet aux utilisateurs de définir la biographie du bot Twitch. Cela peut inclure des informations sur le bot, son créateur, ses centres d'intérêts et bien plus encore.

Exemple d'utilisation :
```
!yg bio "Salut, je suis ChatGPT, votre bot Twitch amical ! Je travaille au siège de Twitch, j'adore interagir avec les spectateurs et j'aime regarder des streams avec mon streamer préféré, @TwitchStreamer !"
```


### !yg trigger_words 
Syntaxe : `!yg trigger_words` 

Description : La commande `!yg trigger_words` affiche les mots ou les phrases déclencheurs actuels qui, lorsqu'ils sont mentionnés dans le chat, activeront le bot Twitch et déclencheront une réponse.

### !yg trigger_words <mots séparés par des virgules>
Syntaxe : `!yg trigger_words <mots séparés par des virgules>` 

Description : La commande `!yg trigger_words` permet aux utilisateurs de définir des mots ou des phrases déclencheurs qui, lorsqu'ils sont mentionnés dans le chat, activeront le bot Twitch et déclencheront une réponse. Cela permet aux utilisateurs de personnaliser les mots-clés qui activeront le bot et d'engager leur public.

Exemple d'utilisation :
``` 
!yg trigger_words bonjour,salut,greetings,bot
```

Note : Les mots déclencheurs doivent être séparés par des virgules sans espaces. 

### !yg welcome_message
Syntaxe : `!yg welcome_message `
Description : La commande `!yg welcome_message` affiche le message de bienvenue actuel qui sera affiché lorsqu'un nouveau spectateur rejoint le chat.

### !yg welcome_message (true|false)
Syntaxe : `!yg welcome_message (true|false)`

Description : La commande `!yg welcome_message (true|false)` permet aux utilisateurs d'activer ou de désactiver le message de bienvenue qui sera affiché lorsqu'un nouveau spectateur rejoint le chat.

Exemple d'utilisation :
``` 
!yg welcome_message true
```
