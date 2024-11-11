# Navigation

The starting point of the file system is the root folder. It's the `/` folder.

There's also the folder called `root`, but that's a different thing.
It's the user folder for the ``root`` user.

Another important directory is the home directory at `/home`. It contains a folder for each user on the system. `~` leads to the home directory.

So the main shortcuts:
* `/` - root folder
* `~` - home folder

The command `pwd` can be used to see where you are.

`ls` shows the contents of the folder. There are a bunch of options for it, but two to remember are:
* `-l` - shows extra info when listing everything
* `-a` - shows everything, including hidden files

Each directory will contain a `.` (current folder) and a `..` (parent folder).

Some folders of interest that exist in the root folder.
* bin - contains a bunch of binaries that can be executed.
* etc - mainly different configurations.
* media - removable media.
* var - a bunch of things, sometimes of interest is the logs folder within it which contains a bunch of logs.
* The already mentioned root user folder. 