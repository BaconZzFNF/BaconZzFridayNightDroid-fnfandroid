# BaconZzFridayNightDroid-fnfandroid
luckydog7
/
Funkin-android
Public
forked from ninjamuffin99/Funkin
65
1931.4k
Code
Issues
1.4k
Pull requests
3
Discussions
Actions
Projects
Security
Insights
 4 branches
 37 tags
This branch is 575 commits ahead, 205 commits behind ninjamuffin99:master.
Latest commit
@zacksgamerz
zacksgamerz Add files via upload
f6d0079
4 days ago
Git stats
 876 commits
Files
Type
Name
Latest commit message
Commit time
.github
Update issue templates
4 months ago
art
new about
3 months ago
assets
Add files via upload
4 days ago
docs
Initial Commit
9 months ago
example_mods
hi
8 months ago
source
Add files via upload
4 days ago
tools
better mobile controls
6 months ago
.gitignore
fix windows build
6 months ago
.nomedia
hi
8 months ago
CHANGELOG.md
changelog
9 months ago
LICENSE
Create LICENSE
9 months ago
Preloader.hx
Initial Commit
9 months ago
Project.xml
some shit
2 months ago
README.md
Update build instructions lol
3 months ago
hxformat.json
Initial Commit
9 months ago
zackwashere.txt
Update zackwashere.txt
2 months ago
README.md


This is the repository for Friday Night Funkin, a game originally made for Ludum Dare 47 "Stuck In a Loop".

Play the Ludum Dare prototype here: https://ninja-muffin24.itch.io/friday-night-funkin Play the Newgrounds one here: https://www.newgrounds.com/portal/view/770371 Support the project on the itch.io page: https://ninja-muffin24.itch.io/funkin

IF YOU MAKE A MOD AND DISTRIBUTE A MODIFIED / RECOMIPLED VERSION, YOU MUST OPEN SOURCE YOUR MOD AS WELL

download
https://github.com/luckydog7/Funkin-android/releases

screenshots
   
Build instructions
first of all we need to set up haxe and haxeflixel read more here - https://github.com/ninjamuffin99/Funkin
Install haxe 4.2.2 instead of 4.1.5
if you updated it dont forget execute this command 'haxelib upgrade' and press 'y' everywhere
Also get extension-webm using this command: 'haxelib git extension-webm https://github.com/KlavierGayming/extension-webm'
the reason we use a different repo again is cuz of a lil error that happens with the audio sync, just adds a "public var renderedFrames" instead of "var renderedFrames", that's all extra that's needed
after that, download Android studio, Jdk, Ndk revision 15c from these sites
jdk - https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

android studio - https://developer.android.com/studio

ndk - https://developer.android.com/ndk/downloads/older_releases?hl=fi

3.install jdk, android studio

unzip ndk (ndk does not need to be installed)
we need to set up android studio for this go to android studio and find android sdk (in settings -> Appearance & Behavior -> system settings -> android sdk) andr andr2
5.and run command lime setup android

you need to insert the program paths

as in this picture (use jdk, not jre) lime

Now do "lime rebuild extension-webm windows" (in the command line), if you're planning to build for windows. If you're plannin to build for android (which you obviously are), use "lime rebuild extension-webm android". If you get an error, download this and put the folder inside it in C:/HaxeToolkit/haxe/lib/extension-webm/git/ndll

open project in command line cd (path to fnf source)
and run command lime build android -final
apk will be generated in this path (path to source)\export\release\android\bin\app\build\outputs\apk\debug\Funkin-debug.apk
Credits / shoutouts
ninjamuffin99 - Programmer
PhantomArcade3K and Evilsk8r - Art
Kawaisprite - Musician
luckydog (me!) - android port
This game was made with love to Newgrounds and it's community. Extra love to Tom Fulp.

amogus

About
friday night funkin on android

Resources
 Readme
License
 Apache-2.0 License
Releases 21
fnf 0.2.7.1 ver 6
Latest
on May 17
+ 20 releases
Packages
No packages published
Languages
Haxe
99.2%
 
Other
0.8%
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
