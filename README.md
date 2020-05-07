# miband4_watchface
Codes , tools ,files behind
Drag the json/bin file to the 
Animation Syntax Watchface.exe to generate the bin file / extract the bin file 

Location of watchfaces in android 
~Internal shared storage\Android\data\com.xiaomi.hm.health\files\watch_skin_local
.bin file name must be same as the folder name 
To get name displayed in Mi Fit app edit th XML file ine the folder 
Use Notepad++ to edit the json file 

Syntax of animation 
"Other": {
"Animation": {
"AnimationImage": {
"X": 20, //Coordinate
"Y": 140,
"ImageIndex": 79,// The starting picture number
"ImageCount": 326, / / the total number of pictures
"X3": 0
},
"x1": 0, / / picture interval time, below 50 will not flash.
"y1": 50, / / number of loops
"Interval": 200
}
}
