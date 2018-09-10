# Fusee launcher for R4S dongle

If you like my work, you can... <a href='https://ko-fi.com/E1E0BN94' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi4.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

Based on [atlas44](https://github.com/atlas44) sam-fusee-launcher (https://github.com/atlas44/sam-fusee-launcher)

Current code seems to run slower on the R4S dongle than in a trinket M0 (takes around 5 secs to launch while it loads instantly with a trinket M0). Dunno why (i'm using autoRCM, but i don't think that has anything to do with it). Feel free to fork and improve, or PR.

The dongle seems to be using a SAM D21E microcontroller with the red LED on PA16.

Read the PDF manual (English and Spanish versions included) for update instructions. 

You will have to create your own update files, as i won't provide any file apart from the header file included and the UF2 file you can find in UF2 directory (this one is for CTCaer hekate 4.0), so you can compile the source code.

It's been tested with several CTCaer hekate versions and mods and works with all of them. That's what i use, so didn't test any other. Should work with any payload tho.

As usual, use at your own risk! :)

Have fun!

