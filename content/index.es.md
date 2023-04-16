---
title: Documentación de YourGPT Bot
sidebar: false # o false para ocultar la barra lateral
sidebarlogo: fresh-white-alt # Desde (static/images/logo/)
include_footer: true # o false para ocultar el pie de página
layout: single
---
## Introducción
El Bot de Twitch es un bot personalizado basado en ChatGPT, diseñado para proporcionar varias funcionalidades para los streamers de Twitch y sus espectadores. Esta documentación proporciona una descripción general de los comandos disponibles en el Bot de Twitch y cómo usarlos.

## Comandos

### !yg help
Sintaxis: `!yg help`

Descripción: El comando `!yg help` muestra una lista de los comandos disponibles y sus descripciones para ayudar a los usuarios a comprender cómo interactuar con el Bot de Twitch.

Ejemplo de uso:
```
!yg help
```

### !yg bio
Sintaxis: `!yg bio`

Descripción: El comando `!yg bio` muestra la biografía del Bot de Twitch, que puede ser personalizada por el usuario.

### !yg bio <texto>
Sintaxis: `!yg bio <texto>`

Descripción: El comando `!yg bio` permite a los usuarios establecer una biografía personalizada para el Bot de Twitch, dándole una personalidad y proporcionando información como dónde trabaja, qué hace normalmente y quién es su streamer favorito.

Ejemplo de uso:
```
!yg bio "¡Hola, soy ChatGPT, tu amigable bot de Twitch! Trabajo en Twitch HQ, me encanta interactuar con los espectadores y disfruto viendo streams con mi streamer favorito, @TwitchStreamer!"
```

### !yg trigger_words
Sintaxis: `!yg trigger_words`

Descripción: El comando `!yg trigger_words` muestra las palabras o frases desencadenantes actuales que, cuando se mencionan en el chat, activarán el Bot de Twitch y provocarán una respuesta.

### !yg trigger_words <palabras separadas por coma>
Sintaxis: `!yg trigger_words <palabras separadas por coma>`

Descripción: El comando `!yg trigger_words` permite a los usuarios establecer palabras o frases desencadenantes que, cuando se mencionan en el chat, activarán el Bot de Twitch y provocarán una respuesta. Esto permite a los usuarios personalizar las palabras clave que activarán el bot y interactuar con su audiencia.

Ejemplo de uso:
```
!yg trigger_words hola,saludos,bot
```

Nota: Las palabras desencadenantes deben estar separadas por comas sin espacios.

### !yg welcome_message
Sintaxis: `!yg welcome_message`

Descripción: El comando `!yg welcome_message` muestra el mensaje de bienvenida actual que se mostrará cuando un nuevo espectador se una al chat.


### !yg welcome_message <texto>
Sintaxis: `!yg welcome_message <texto>`

Descripción: El comando `!yg welcome_message <texto>` permite a los usuarios establecer un mensaje de bienvenida personalizado que se mostrará cuando un nuevo espectador se una al chat. Esto permite a los usuarios personalizar el mensaje que se mostrará cuando un nuevo espectador se una al chat y interactuar con su audiencia.

Ejemplo de uso:
```
!yg welcome_message "¡Bienvenido al canal de {{.Channel}}, @{{.Username}}! Soy {{.Name}}, tu amigable bot de Twitch. Trabajo en la sede de Twitch, me encanta interactuar con los espectadores y disfruto viendo transmisiones con mi streamer favorito, @{{.Channel}}!"
```