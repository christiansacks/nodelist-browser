# nodelist-browser

Installation;
clone the repo, and then copy/move/link the mL-nlparse.mpy file into your scripts directory.

Configuration;
To configure the script, it requires you only edit one variable;

NODELIST = "/mystic/data/nodelist.txt"

Change this to point to wherever your mystic install is so it can see the nodelist.txt file.

Then in mystic configuration utility, edit your chosen menu, and add a new item, using this
as a guide;

╔════════════════════ Command Options ════════════════════╗
║                                                         ║
║ Command    │ (GY) Execute Python 2 Script               ║
║ Data       │ /mystic/scripts/mL-nlparse.mpy             ║
║ Access     │                                            ║
║ Grid Event │ Selected                                   ║
║                                                         ║
╚═════════════════════════════════════════════════════════╝

That's it. Assuming you put the correct directory in the NODELIST variable, and have set up
mystic to run this script in the way documented above, everything will be fine.

Go have a brew, then run the nodelist browser and start visiting all those yummy BBSes in
your nodelist.
