# uBlock unhook
Minimalistic and fast uBlock Origin filters list, that mimics [unhook](https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) browser extension and makes YouTube less distracting.

###  Features
You can enable and disable features by (un/)comenting (removing/adding `!`)  

Things that this list blocks by default:
- Shorts - all ocuences of youtube shorts, and shorts player.
- Recomendations - videos recomended on sidebar and after the video
- Autoplay - next video wont play.
  
Features that are present and could be enabled:  
- Comments - hide comment section
- Channel - creator channel pfp and redirection

Note: this currently doesn't work well wih mobile devices, but I will try to implement it sometime in future.

### Installation
It is imported as any other filter list - just simply open your uBlock Origin __settings__ then go into __My filters__  tab and click __Import and append__ and choose the correct file.

### Why?
I found that the unhook firefox extension slow, also I din't like the default settings. I use uBlock Origin on all my devices (and you should too btw) so I created drop in filter list that replaces it functionality. Also less browser extensions is better for both privacy and performance.
