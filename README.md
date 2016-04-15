#yakuake
Fork of Yakuake with minor tweaks. It ensures when a terminal is split vertically or horizontally, the working directory is also switched instead of `$HOME` 


#Objective
Everytime a terminal is split vertically or horizontally the default folder is `$HOME`. I wanted to have the behaviour similar to `terminator` [home page](http://gnometerminator.blogspot.in/)

#Changes 
- Added a slot to track when current working directory of the `KonsolePart` changes [see ref](http://api.kde.org/4.x-api/applications-apidocs/konsole/html/classKonsole_1_1Part.html) 
- Locally update the current directory path
- When a new Terminal object is created, set it with the previous path

#TODOs
- No intention to add anything more :)
