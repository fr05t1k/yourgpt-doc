---
title: Documentación del Bot YourGPT
sidebar: true # true para mostrar la barra lateral, false para ocultarla
sidebarlogo: fresh-white-alt # Desde (static/images/logo/)
include_footer: true # true para mostrar el pie de página, false para ocultarlo
layout: single
---
# Documentación del Bot de Twitch

## Introducción
El Bot de Twitch es un bot personalizado basado en ChatGPT, diseñado para proporcionar diversas funcionalidades para los streamers de Twitch y sus espectadores. Esta documentación ofrece una visión general de los comandos disponibles en el Bot de Twitch y cómo utilizarlos.

## Comandos

### !yourgpt help
Sintaxis: `!yourgpt help`layout: single

Descripción: El comando `!yourgpt help` muestra una lista de comandos disponibles y sus descripciones para ayudar a los usuarios a entender cómo interactuar con el Bot de Twitch.

Ejemplo de uso:
```
!yourgpt help
```

### !yourgpt update_bio <texto>
Sintaxis: `!yourgpt update_bio <texto>`

Descripción: El comando `!yourgpt update_bio` permite a los usuarios establecer una biografía personalizada para el Bot de Twitch, dándole personalidad e información como dónde trabaja, qué suele hacer y quién es su streamer favorito.

Ejemplo de uso:
```
!yourgpt update_bio "¡Hola, soy ChatGPT, tu amigable bot de Twitch! Trabajo en la sede de Twitch, me encanta interactuar con los espectadores y disfruto viendo streams con mi streamer favorito, @TwitchStreamer!"
```

### !yourgpt update_trigger_words <palabras separadas por coma>
Sintaxis: `!yourgpt update_trigger_words <palabras separadas por coma>`

Descripción: El comando `!yourgpt update_trigger_words` permite a los usuarios establecer palabras o frases activadoras que, al ser mencionadas en el chat, activarán el Bot de Twitch y provocarán una respuesta. Esto permite a los usuarios personalizar las palabras clave que activarán el bot y interactuar con su audiencia.

Ejemplo de uso:
```
!yourgpt update_trigger_words hola,saludos,bot
```

Nota: Las palabras activadoras deben estar separadas por comas sin espacios.
