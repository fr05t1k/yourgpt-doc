---
title: Documentation du Bot YourGPT
sidebar: false # true pour afficher la barre latérale, false pour la masquer
sidebarlogo: fresh-white-alt # Depuis (static/images/logo/)
include_footer: true # true pour afficher le pied de page, false pour le masquer

---
## Introduction
Le Bot Twitch est un bot personnalisé basé sur ChatGPT, conçu pour fournir diverses fonctionnalités aux streamers de Twitch et à leurs spectateurs. Cette documentation donne un aperçu des commandes disponibles dans le Bot Twitch et de leur utilisation.

## Commandes

### !yourgpt help
Syntaxe : `!yourgpt help`

Description : La commande `!yourgpt help` affiche une liste des commandes disponibles et leurs descriptions pour aider les utilisateurs à comprendre comment interagir avec le Bot Twitch.

Exemple d'utilisation :
```
!yourgpt help
```

### !yourgpt update_bio <texte>
Syntaxe : `!yourgpt update_bio <texte>`

Description : La commande `!yourgpt update_bio` permet aux utilisateurs de définir une biographie personnalisée pour le Bot Twitch, lui donnant une personnalité et fournissant des informations telles que son lieu de travail, ce qu'il fait habituellement et son streamer préféré.

Exemple d'utilisation :
```
!yourgpt update_bio "Salut, je suis ChatGPT, ton bot Twitch amical ! Je travaille chez Twitch, j'adore interagir avec les spectateurs et j'aime regarder des streams avec mon streamer préféré, @TwitchStreamer !"
```


### !yourgpt update_trigger_words <mots séparés par des virgules>
Syntaxe : `!yourgpt update_trigger_words <mots séparés par des virgules>`

Description : La commande `!yourgpt update_trigger_words` permet aux utilisateurs de définir des mots ou des phrases déclencheurs qui, lorsqu'ils sont mentionnés dans le chat, activeront le Bot Twitch et provoqueront une réponse. Cela permet aux utilisateurs de personnaliser les mots-clés qui activeront le bot et d'interagir avec leur audience.

Exemple d'utilisation :
```
!yourgpt update_trigger_words bonjour,salut,bot
```

Note : Les mots déclencheurs doivent être séparés par des virgules sans espaces.

