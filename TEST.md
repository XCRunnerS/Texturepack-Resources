Pack Stuff You Should Know (Java)
pack.mcmeta
pack.mcmeta is basically how you tell minecraft your pack's version and description, and that its a pack for minecraft!

A basic pack.mcmeta will look something like this:

{ 
  "pack": {
    "pack_format": 8,
    "description": "Visible Pack Description"
    }
}
"pack": is a required peice of metadata, all the rest of the mcmeta file will go inside of this tag

"pack_format": tells minecraft what version your pack is for, current it supports integer values 0-9*

"pack_format": #	Minecraft Version	Notes
"pack_format": 0	1.6-1.7.10	unused
"pack_format": 1	1.6-1.8.9	pvp packs
"pack_format": 2	1.9–1.10.2	-
"pack_format": 3	1.11–1.12.2	-
"pack_format": 4	1.13–1.14.4	0-3 break in 1.13+ (Flattening)
"pack_format": 5	1.15–1.16.1	-
"pack_format": 6	1.16.2–1.16.5	-
"pack_format": 7	1.17.x	-
"pack_format": 8	1.18.x	current
check Minecraft Wiki: Pack_format for more

"description": "visible in game"

supports Formatting Codes
will display a maximum of two lines
more stuff:

uses json format
all items on the same level (in this case description and pack_format) should be seperated by a , symbol
"pack_format": 9 will most likely be used for 1.19.x
pack.png
should be SQUARE dimensions
will be scaled down to roughly 64x64 on 1080p monitors using default scaling
uses nearest neighbor to scale the image up/down (crisp pixel art, pixelated highres art)
assets folder
the actual textures go in here, you should use a tutorial like Mine to extract the default textures, and reference the default folder structure and file names for your pack. use the same minecraft version the pack is made for

Distributing Packs
Use Mega!

no ads
25gb storage limit/acc
clear download button
Credits and Legal
credit all your textures you use. put it in a file called CREDITS.txt or README.md
check for LICENSE and CREDITS files in packs you referenced
try to make sure you dont have any default textures in your pack (mojang usually doesnt care, but its technically against the terms of service)
look at Creative Commons and include a LICENSE that works for you (optional)
