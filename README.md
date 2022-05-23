# nodelist-browser

Description;
This is a replacement nodelist browser/bbs lister for Mystic BBS written in Mystic Python.
The original idea came from Ktulu as he was showing me an idea he had that was a replacement
for the BBS lister to list Araknet BBSes, I had previously thought about making one to run
from the nodelist, but it was Ktulu's idea that gave me the final nudge to get it going. A
couple of days later, this is what came out.

Thanks to Ktulu for sharing his idea with me.


Installation;
clone the repo, and then copy/move/link the mL-nlparse.mpy file into your scripts directory.

Configuration;
To configure the script, it requires you only edit one variable;

NODELIST = "/mystic/data/nodelist.txt"

Change this to point to wherever your mystic install is so it can see the nodelist.txt file.

Then in mystic configuration utility, edit your chosen menu, and add a new item, using this
as a guide;

![image](https://user-images.githubusercontent.com/40481087/169669331-21279f91-2976-44ea-b338-1ff8dded5eab.png)

That's it. Assuming you put the correct directory in the NODELIST variable, and have set up
mystic to run this script in the way documented above, everything will be fine.

Go have a brew, then run the nodelist browser and start visiting all those yummy BBSes in
your nodelist.
