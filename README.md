Firefox CSS theme to maximize the vertical space of your monitor.

![alt text](pics/overall.png?raw=true)
(Background: [Tempano Port by Duwon Lee](https://www.artstation.com/artwork/dB84A))

## Contents
- [Compatibilty](#compatibilty)
- [Features](#features)  
- [Suggested Tweaks](#suggested-tweaks)  
- [Toggle PDF reader dark mode](#toggle-pdf-reader-dark-mode)  
- [Credits](#credits)  

## Compatibilty
Tested on:   
* Ubuntu 20.04.3 LTS
* Windows 10 20h1   

Soon:
*  macOS Catalina 10.15.5 and Big Sur 11.6   
Problem: [No toolbar!](https://github.com/hakan-demirli/Firefox_Custom_CSS/issues/3)

## Features
 * Horizontal tabs are removed. Use [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) or [Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
 * Dark mode for the default PDF reader:  
   ![alt text](pics/dark_mode.png?raw=true)

 * Dark mode for hover URL menu:  
 ![alt text](pics/dark_hover_menu.png)
 
 * Search with Google text removed:  
 ![alt text](pics/search_with_google.png)

 * Thinner scroll bars:  
 ![alt text](pics/scroll_bar.png)

## Suggested Tweaks
**Enable Compact Mode**    
_about:config > browser.compactmode.show > True_    

**Toolbar**  
_Customize mode > Density > Compact_    

**Startup Image**  
_about:config > browser.startup.preXulSkeletonUI > False_    

**Startup Tabs**    
_Settings > General > Startup > Open previous windows and tabs > True_    
(Otherwise size of the top sites will change everytime you open the browser.)

## Toggle PDF reader dark mode
The PDF viewer dark mode is active by default. To deactivate it, just add ```?normal``` to the end of your pdf URL.
![alt text](pics/pdf_dark_mode.png)

## Credits
  * [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/) 
