
# Anorak's Adventure

This is a modification to [Warren Robinett's](http://www.warrenrobinett.com/) classic game [Adventure](http://www.warrenrobinett.com/adventure/index.html) for the [Atari 2600](https://en.wikipedia.org/wiki/Atari_2600).  It represents the version that the character Wade Watts plays at the end of the novel [Ready Player One](https://en.wikipedia.org/wiki/Ready_Player_One) by [Ernie Cline](http://www.ernestcline.com/).

Instead of finding the signature that the original author placed in the game, Wade finds a large white egg which triggers the end of the contest, with a "blinding white flash of light".

In this version, finding the egg results in a signal sent on unused I/O pins on the 2600.  This signal triggers yet other events...

# Credits

Anorak's Adventure was conceived entirely by Evan Allen.  He doing all the hardware, and everything else downstream of the Atari.  I am only doing the game code hacking.

# Building

This codebase can be built with the venerable [dasm assembler](http://dasm-dillon.sourceforge.net/), using a command line such as

    dasm AnoraksAdventure.asm -oAnoraksAdventure.bin -lAnoraksAdventure.list -f3

# Playing

Ideally, you will seek out the one true Atari 2600 at the [i3Detroit MakerSpace](https://www.i3detroit.org/), or a nearby event.  But you can also play it on a real Atari, or in an emulator such as [Stella](https://stella-emu.github.io/).


