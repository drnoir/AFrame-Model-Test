## AFrame Model Test - 
###Magical Atom by Chris Godber
A prototype AR expereince - loading in a 3D model of an atom like shape with autoplaying animation and sound
the model rotates around the camera 360 degress on a looped path using the Camera of the users phone for 
the background. On run the app will ask for permission to access your camera.

It is designed to be a mobile expereince so though it will run on desktop machine
it is not intended for those devices. 

### Libraries / Packages / Dependecies
- AFrame - Core AFrame
- AFrame Extras - Used for Animation triggering on GLB model
- AFrame AR - Used for Init of AR / Cam feed etc

### Hosting 
The app itself is hosted on GitHub Pages via index.html via GitHub Pages
As this is a test project I have just relied on CDN for the associated js required
To host this app properly online you will require a SSL certificate to be present on the domain

## Assets Used
3D Model - CyberCore by Tycho Magnetic Anomaly on SketchFab- https://sketchfab.com/3d-models/cyber-core-d30920ccf2f440fa9586a656ac0f6bee
Music - Somavār by XinXin - https://xinjoe.bandcamp.com/album/xinxin

### Notes
I was given the task of creating a simple AR expereince with AFrame

I tried to approach this in a creative manner and after a few iterations I came up with the idea of a sort 
of spinning atom after trying a few different models and ideas out. As with many of the 3D Web based apps
I have produced before I wanted to give it a feeling of 'me' so I chose an interesting piece of electronic music 
and an interesting 3D model. 

I have incorporated two spotlights which shine and rotate in turn on the model producing an atmospheric effect

### Testing / Issues etc
I have tested the expereince on Android and Chrome and have not found any issues 
For iOS I have tested using browserstack on an iPad running Safari - this seemed to work fine
