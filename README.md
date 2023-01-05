# Mastodon 'Aurora' CSS
Beautiful custom css for Mastodon, designed for [artsculture.media](https://talk.artsculture.media/public) (preview it there and [see an enhanced profile here](https://talk.artsculture.media/@baroquepawel))

Date: 5 January 2023

<img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Timeline2a.webp" width="325px" height="auto"  title="Timeline | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_About.webp" width="325px" height="auto"  title="About the instance | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_DM.webp" width="325px" height="auto"  title="Direct messages | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Moved.webp" width="325px" height="auto"  title="Profile moved | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_Profile.webp" width="325px" height="auto"  title="Profile | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;"><img src="https://cdn.bach.club/sdg/Mastodon/Aurora/mastodon_aurora_css_SignUp.webp" width="325px" height="auto"  title="Sign-up page | Mastodon Aurora CSS" alt="Screenshot of Mastodon with Aurora CSS applied" style="padding:1rem;">


## Features

- optimized for dark theme as default
- Replaced "Publish!" button with "Toot!" (not yet reflected in all the screenshots above)
- unified, modern colour palette inspired by Northern Lights
- larger profile header image to allow for more creativity
- larger profile avatar to make it more personal and relatable
- cleaner profile links in two columns (CSS grid)
- more discreet verified links indication
- larger names of authors in the feed
- slightly more spacious compose panel
- custom fonts for navigation, headers, and body
- added background option for login and sign-up pages
- custom thumbnail option for moved profiles
- clearer indication of direct messages (colour accent) 
- pulsating dot for unread direct messages
- various other small tweaks and changes
- styled "translate" link (based on DeepL implementation) 
- footer branding (transparent backgroung logo of the instance) 


## Instructions

This theme can be applied on top of an existing installation by simply calling the css file:

1. Upload the **mastodon_aurora.css** to _your_mastodon/public/system/custom/_ folder.
2. Login to your mastodon, then go to: _Preferences -> Administration -> Server Settings -> Appearance_
3. in _Custom CSS_ put:

`@import url("system/custom/mastodon_aurora.css");`


(alternatively, copy the content of this css and paste directly into the _Custom CSS_ field in Appearance)


### CALLING A CUSTOM FONT

You can @import fonts, e.g. from google (an option is provided), but it is preferable to put required fonts in a local folder and call them from there, to avoid sharing data with external corporations. 
The fonts can be downloaded from this repository, or from: 

- [Noto Sans Diplay](https://fonts.google.com/noto/specimen/Noto+Sans+Display)
- [Manrope](https://fonts.google.com/specimen/Manrope?query=manrope)

and then to be uploaded to your server, to: _your_mastodon/public/system/custom/fonts_


### CUSTOM BACKGROUND for Login & Sign-Up pages
upload an image of your choice to: _your_mastodon/public/system/custom/graphics/_

### CUSTOM THUMBNAIL for accounts that moved
you can download an example from this repository, upload to: _your_mastodon/public/system/custom/graphics/_


## Enjoy, share, adapt, and follow me on mastodon: 
[@baroquepawel@artsculture.media](https://talk.artsculture.media/@baroquepawel)

🎵 🎹 🐘


## License (MIT)

Copyright (C) 2022 Pawel Siwczak

Theme Name: Mastodon Aurora
Theme URI: https://www.artsculture.media/
Author: Pawel Siwczak / ArtsCulture.Media
Author URI: @baroquepawel@artsculture.media

Permission to use, copy, modify, and distribute this work 
for any purpose with or without fee is hereby granted,
provided that the above copyright notice and 
this permission appear in all copies. 

EXCEPTION: IT IS FORBIDDEN TO USE THIS WORK IN RELATION TO 
ANY NSFW, ILLEGAL, OR VIOLENT CONTENT.

This material is provided "as is", with absolutely no warranty 
expressed or implied. Any use is at your own responsibility.


