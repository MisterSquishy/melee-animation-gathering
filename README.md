# melee animation gathering
Makes Super Smash Brothers Melee characters cycle through most of their animation states instead of the wait animation. Only really useful if you enter a single player game using the debug menu--each animation will only be done once so if there are multiple characters then no one character will do them all. Also note that dolphin can't load the game if there are too much gecko code to load, so this can't be used in conjunction with the Melee Netplay Community Settings.

I also uploaded most of vanilla Fox's animations. I parsed out the animation states using the debug HUD and [avidemux2.6](https://avidemux.en.softonic.com/).

For a quick explanation of how to add a gecko code in dolphin try [this](https://www.youtube.com/watch?v=Abq72U7_AYc). For a long and extremely awesome explanation go [here](https://www.youtube.com/playlist?list=PL6GfYYW69Pa2L8ZuT5lGrJoC8wOWvbIQv).

Written in PPC--to compile into machine code use [the ASM<-->Wiird tool](http://code.google.com/p/geckowii/), though you only need to compile it yourself if you change the assembly code.
