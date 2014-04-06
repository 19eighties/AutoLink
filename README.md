## esoTalk – AutoLink plugin

- When you post an URL, AutoLinks automatically embeds images, MP3 and videos.
- Currently supported are:
  * images
  * mp3d
  * Youtube
  * Google Video
  * Facebook Video
  * Vimeo
  * Metacafe
  * Dailymotion
  * Myspace
  * SPIKE
  * Redlasso
  * OnSMASH
  * Tangle.com
  * LiveLeak


### Installation

Browse to your esoTalk plugin directory:
```
cd WEB_ROOT_DIR/addons/plugins/
```

Clone the AutoLink plugin repo into the plugin directory:
```
git clone git@github.com:esoTalk-plugins/AutoLink.git AutoLink
```

Chown the AutoLink plugin folder to the right web user:
```
chown -R apache:apache AutoLink/
```
