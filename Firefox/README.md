## Installation

- In the ```about:config``` page on your Firefox browser, set the following parameters to **True** :
  - ```toolkit.legacyUserProfileCustomizations.stylesheets```
  - ```layers.acceleration.force-enabled```
  - ```gfx.webrender.all```
  - ```svg.context-properties.content.enabled```
- Copy the userChrome.css file from this repository to your **chrome** folder. You can find the **chrome** folder here :
  - ```$HOME/.mozilla/firefox/######.default-release/chrome/```
  - If it doesn't exist already create a folder called chrome
