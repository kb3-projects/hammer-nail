# hammer-nail
#### a music focused kodi skin for car
This started off by working with the "carPC" skins avialable across the web.  Mostly pulled from CarPC-xtouch, with some CarPC-Carbon bits and pieces.  Many thanks to all the effort put into those skins by thier respective authors.

Wanted a music focused skin to put in a car and this is the result.  Effort also went into rescaling everything for a 720p for use on RasPi.   In hindsight, the rescaling probably was not needed.  But it did force a somewhat standard look to all the windows.

Why the name?  Using the old expression, "To a child with a hammer, everything is a nail"   I am very much a child when it comes to skinning for Kodi, and the skinning engine has been used as a hammer on this skin.

### A few usage notes:

#### Dependency:
script.listhammer is needed for the skin to fully function.  It available in the same repository as this skin.  

#### Control:
* This will work with a keyboard and mouse.   
* Touch functions will generally work, but not for everything.
* A custom keyboard file is in the /other folder.  
  * It allows F1 through F4 to control the soft buttons at the bottom of most windows.  
  * F5 will function as select/enter as appropriate, and a longpress F5 will bring up context menus (this is important for playlists, below)
  * The user needs to move it to the proper location so Kodi will recognize it.   (i.e. \userdata\keymaps\)
  
#### Playlists:
The playlists window has a menu that functions the same as a context window.  Longpress F5 will produce a popup selection allows - 
* Choose an icon for the playlist.  Images for the icons are stored in /media/playlist.icons, and can be readily replaced with any other images.
* Create a new playlist
* Edit an existing playlist
* Delete an existing playlist

#### Skin Settings:
* The skin colors are user selectable from a menu.
* Under options, the softbuttons can be disabled.  But they remain visible for use via keyboard only, when using the custom keyboard file.
