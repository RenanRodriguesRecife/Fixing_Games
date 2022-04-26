How to get Fur Fighters PC Version Working Correctly on a Modern Computer

So a few days ago, in this post I learned that there was a PC release for Fur Fighters. If you read my comments there, I found it to be buggy and unplayable on a modern PC. From old forum posts I found around the web, the game was buggy to begin with, and modern computers that are hundreds of times more powerful that what was available 18 years ago make it even worse.

I never got to finish this game as a kid. I've tried playing it again on the Dreamcast, but the controls are just impossible after almost two decades of dual joystick controllers and PC gaming. I also don't own any iThings to play the iOS Version.

So, I tinkered around with the PC version until I got it working correctly. I'm about 40-50% through the game and haven't been stopped by any game breaking bugs yet.

Here's how I did it.

Step 1: Obtain the Game

The PC version appears to be totally abandoned. It's no longer for sale anywhere besides some overpriced used copies on Amazon. Some not so creative Googling will find you an ISO of the install disc though.

There's also a patch that appears to be for getting the game to work on Windows ME and some language fixes. Who knows what other things they fixed with it, so I installed it too.

Step 2: Install the Game

You'll need to burn the ISO image to a disc (it'll fit on a CD-R) or mount it to make Windows pretend it's in a CD-ROM drive. The disc will need also to be mounted or the disc inserted in order to play the game after installation.

There really aren't any options when installing the game. When it prompts you to install DirectX 7, skip it.

The patch is a self extracting .zip file. Extract it to the directory where you have the game installed, or use something like 7-zip to open the patch file and copy the files to the directory yourself. By default, the game installs to C:\Program Files (x86)\Acclaim Entertainment\Fur Fighters

Step 3: Get the Game Running

If you just try running the game after installation, not much happens. You'll need to go back to the installation directory, right click furfighters.exe and set it to run with compatibility mode for Windows XP and to run as an administrator.

I also suggest setting the task bar to auto hide. The game will force your computer to change the monitor resolution to run at the resolution you select, but still runs in a window. It'll be slightly squished to make room for the task bar if you don't hide it.

Every time you start the game, it will ask you to choose the graphics options. Choose your GPU (not Direct3D or HAL). For some reason, it lists my Graphics cards once for each monitor, so I get six options. The first two seem to work fine.

When I first launched the game, it came up as a blank white square. This thing was hiding behind it, and I had to click Install this Feature. The game won't let you move it once it's running, so you may need to start it in 640x480 the first time so it doesn't cover the window.

At this point, you should be able to play the game, but some bugs will prevent you from rescuing some of the babies or cause you to die when you shouldn't.

Step 4: Fixing the Bugs

Like most Dreamcast games, the physics and many animations are tied to the frame rate. Dreamcast games ran at 30FPS, but the devs for some reason read your monitor's refresh rate and set the frame rate to that. This probably wasn't a problem in 2000 when computers were glorified potatoes, but basically anything now can easily run the game at the full 60FPS/60Hz of a standard monitor. This makes anything tied to the frame rate happen either twice as fast or at half speed. On my 144Hz monitor, the game was going complete bonkers. I couldn't open doors at all, couldn't push objects, treadmills would send me flying, and Chang couldn't fit into small spaces.

So, first thing, if you have a 144Hz monitor, you can lower the refresh rate back down to 60. This will get you to the "playable but with bugs" level. This isn't necessary if you follow the next step though.

Somebody please comment if you know a way to do this with AMD or Intel graphics.

If you have Nvidia graphics, you can use Nvidia Inspector to limit the frame rate. After downloading the .zip file, extract it to wherever you want. I made a folder in Program Files (x86) for it, but you can put it wherever you want.

Run Nvidia Profile Inspector. Select the FurFighters(furfighters.exe) profile. Change the setting for Frame Rate Limiter to somewhere around 30FPS. The higher you go, the more buggy the game will be, but don't go lower than 30. The game seems to work OK up to around 40-ish.

I found this may not work on newer drivers? I'm currently running 385.69. You can use a tool like FRAPS to show the frame rate on screen to verify it's working. Set it to show in the lower left or right corner. The title bar will cover it up if you leave it on top as the game doesn't seem to realize it's there.

If you can't limit your frame rate, I also found an old forum post where someone said they ran a stress testing tool like Prime95 to max out their CPU and slow down the game for the parts where the game was bugging out. That may work for you, but just be aware that running a synthetic full load on your CPU will make it very hot. I don't suggest doing it for a long period of time on laptops or PCs without properly working cooling.
