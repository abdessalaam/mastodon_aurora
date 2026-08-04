

# CSS 'Aurora' para Mastodon
Hermoso CSS personalizado para Mastodon, diseñado para [artsculture.media](https://talk.artsculture.media/public?utm_source=github&utm_medium=readme&utm_campaign=aurora) (también [puedes ver un perfil mejorado aquí](https://talk.artsculture.media/@baroquepawel?utm_source=github&utm_medium=readme&utm_campaign=aurora)).

Fecha: 13 de enero de 2023

<img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Timeline2a.webp" width="325px" height="auto"  title="Timeline | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_About.webp" width="325px" height="auto"  title="About the instance | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_DM.webp" width="325px" height="auto"  title="Direct messages | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Moved.webp" width="325px" height="auto"  title="Profile moved | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Profile.webp" width="325px" height="auto"  title="Profile | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_SignUp.webp" width="325px" height="auto"  title="Sign-up page | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;">


## Características

- Optimizado para el tema oscuro como predeterminado
- Reemplaza el botón "Publicar" por "Toot" (todavía no reflejado en todas las capturas de pantalla anteriores)
- Paleta de colores unificada y moderna inspirada en las auroras boreales
- Imagen de encabezado de perfil más grande para permitir mayor creatividad
- Avatar de perfil más grande para hacerlo más personal y cercano
- Enlaces de perfil más limpios en dos columnas (cuadrícula CSS)
- Indicador de enlaces verificados más discreto
- Nombres de autores más grandes en el feed
- Panel de composición ligeramente más espacioso
- Fuentes personalizadas para navegación, encabezados y cuerpo
- Opción de fondo agregada para las páginas de inicio de sesión y registro
- Opción de miniatura personalizada para perfiles trasladados
- Indicación más clara de mensajes directos (acento de color) 
- Punto pulsante para mensajes directos no leídos
- Varios otros pequeños ajustes y cambios
- Enlace "traducir" con estilo personalizado (basado en la implementación de DeepL) 
- Marca en el pie de página (logotipo del fondo transparente de la instancia) 


## Instrucciones

Este tema se puede aplicar sobre una instalación existente simplemente llamando al archivo css:

1. Sube el archivo **mastodon_aurora.css** a la carpeta _your_mastodon/public/system/custom/_.
2. Inicia sesión en tu Mastodon y luego ve a: _Preferencias -> Administración -> Configuración del servidor -> Apariencia_
3. En _CSS personalizado_ coloca:

`@import url("system/custom/mastodon_aurora.css");`


(alternativamente, copia el contenido de este css y pégalo directamente en el campo _CSS personalizado_ en Apariencia)


### CARGAR UNA FUENTE PERSONALIZADA

Puedes importar fuentes con @import, por ejemplo, de Google (se proporciona una opción), pero es preferible colocar las fuentes requeridas en una carpeta local y cargarlas desde allí, para evitar compartir datos con corporaciones externas. 
Las fuentes se pueden descargar desde este repositorio o desde: 

- [Noto Sans Display](https://fonts.google.com/noto/specimen/Noto+Sans+Display)
- [Manrope](https://fonts.google.com/specimen/Manrope?query=manrope)

y luego subirlas a tu servidor, a: _your_mastodon/public/system/custom/fonts_


### FONDO PERSONALIZADO para páginas de inicio de sesión y registro
sube una imagen de tu elección a: _your_mastodon/public/system/custom/graphics/_

### MINIATURA PERSONALIZADA para cuentas trasladadas
puedes descargar un ejemplo desde este repositorio y subirlo a: _your_mastodon/public/system/custom/graphics/_


## Disfruta, comparte, adapta y sígueme en Mastodon: 
[@baroquepawel@artsculture.media](https://talk.artsculture.media/@baroquepawel)

🎵 🎹 🐘


## Licencia (MIT)

Derechos de autor (C) 2022 Pawel Siwczak

Nombre del tema: Mastodon Aurora
URI del tema: https://www.artsculture.media/
Autor: Pawel Siwczak / ArtsCulture.Media
URI del autor: @baroquepawel@artsculture.media

Se concede permiso para usar, copiar, modificar y distribuir esta obra 
con cualquier fin, con o sin tarifa, por la presente,
con la condición de que el aviso de derechos de autor anterior y 
este permiso aparezcan en todas las copias. 

EXCEPCIÓN: ESTÁ PROHIBIDO USAR ESTA OBRA EN RELACIÓN CON 
CUALQUIER CONTENIDO NSFW, ILEGAL O VIOLENTO.

Este material se proporciona "tal cual", sin garantía alguna 
expresa o implícita. Cualquier uso es bajo tu propia responsabilidad.
