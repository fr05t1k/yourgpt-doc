---
title: Documentation de votre bot YourGPT
sidebar: false # ou false pour afficher la barre latérale
sidebarlogo: fresh-white-alt # À partir de (static/images/logo/)
include_footer: true # ou false pour afficher le pied de page
layout: single
---
## Introduction
Le bot Twitch est un bot personnalisé basé sur ChatGPT, conçu pour fournir différentes fonctionnalités aux streamers Twitch et à leur audience. Cette documentation donne un aperçu des commandes disponibles dans le bot Twitch et de leur utilisation.

## Commandes

### !yg help
Syntaxe: `!yg help`

Description: La commande `!yg help` affiche une liste des commandes disponibles et de leurs descriptions pour aider les utilisateurs à comprendre comment interagir avec le bot Twitch.

Exemple d'utilisation:
```
!yg help
```

### !yg bio
Syntaxe: `!yg bio`

Description: La commande `!yg bio` affiche la biographie du bot Twitch, qui peut être personnalisée par l'utilisateur.

### !yg bio <texte>
Syntaxe: `!yg bio <texte>`

Description: La commande `!yg bio` permet aux utilisateurs de définir une biographie personnalisée pour le bot Twitch, lui donnant une personnalité et fournissant des informations telles que où il travaille, ce qu'il fait habituellement et son streamer préféré.

Exemple d'utilisation:
```
!yg bio "Salut, je suis ChatGPT, ton bot Twitch amical ! Je travaille au siège de Twitch, j'adore interagir avec les spectateurs et j'aime regarder des streams avec mon streamer préféré, @TwitchStreamer!"
```

### !yg trigger_words
Syntaxe: `!yg trigger_words `

Description: La commande `!yg trigger_words` affiche les mots ou phrases déclencheurs actuels qui, lorsqu'ils sont mentionnés dans le chat, activeront le bot Twitch et déclencheront une réponse.

### !yg trigger_words <mots séparés par des virgules>
Syntaxe: `!yg trigger_words <mots séparés par des virgules>`

Description: La commande `!yg trigger_words` permet aux utilisateurs de définir des mots ou phrases déclencheurs qui, lorsqu'ils sont mentionnés dans le chat, activeront le bot Twitch et déclencheront une réponse. Cela permet aux utilisateurs de personnaliser les mots-clés qui activeront le bot et d'interagir avec leur audience.

Exemple d'utilisation:
```
!yg trigger_words bonjour,salut,salutations,bot
```

Note : Les mots déclencheurs doivent être séparés par des virgules sans espaces.

### !yg welcome_message
Syntaxe: `!yg welcome_message `

Description: La commande `!yg welcome_message` affiche le message de bienvenue actuel qui sera affiché lorsque qu'un nouveau spectateur rejoint le chat.


### !yg welcome_message <texte>
Syntaxe : `!yg welcome_message <texte>`

Description : La commande `!yg welcome_message <texte>` permet aux utilisateurs de définir un message de bienvenue personnalisé qui sera affiché lorsqu'un nouvel utilisateur rejoint le chat. Cela permet aux utilisateurs de personnaliser le message qui sera affiché lorsque qu'un nouvel utilisateur rejoint le chat et d'interagir avec leur audience.

Exemple d'utilisation :
```
!yg welcome_message "Bienvenue sur la chaîne de {{.Channel}}, @{{.Username}}! Je suis {{.Name}}, votre bot Twitch amical ! Je travaille au siège de Twitch, j'adore interagir avec les spectateurs et j'aime regarder les diffusions avec mon streamer préféré, @{{.Channel}}!"
```
