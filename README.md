# dnd-tools

... is a set of interactive command line tools for Dungeons and Dragons 5th Edition.  This is the source code for the  python scripts and install functions used to create the [dnd-tools AUR package](https://aur.archlinux.org/packages/dnd-tools/).  The aim of this project, inspired by [donjon](http://donjon.bin.sh/), is to create an offline, cross-platform, gamemaster tool set -- since you probaly have too many browser windows open already :-D

---

#### Features:

- *Compeltely interactive:*  promted with start menu after every function
- *Character generator:*  any or all stat blocks and features can be randomized
- *NPC generator:*  35 NPC classes with stat blocks populate as with character creation.  Fixed NPC stats are in the Monster Manual and many places online.
- *Save generated character:*  export generated character to text file
- *Dice roller:*  any number of dice, any number of sides
- *Encounter calculator:* calculates modified experience per party size / level and monster party size (and CR)
- *Loot generator:* random loot tables based on CR, and indivdual or horde enemies
- *Initiative roller:* random d20 rolls for x number of players (raw / without initiaitve bonus)
- *Tarokka card game:*  Tarrot card game from Curse of Strahd
- *Wild magic effects:*  Effect roller for Wild Magic sorcerers

---

#### Installation / Usage:

**Arch**:
- See [Arch Wiki for Installing AUR Packages](https://wiki.archlinux.org/index.php/Arch_User_Repository#Installing_packages)
- [Download snapshot from AUR](https://aur.archlinux.org/packages/dnd-tools/)

**Other Linux**:
~~~
$ git clone https://github.com/gtbjj/dnd-tools
$ cd dnd-tools
$ sudo python setup.py install
$ /usr/bin/dnd-tools
~~~

**Windows:**

- Install [Python for Windows](https://www.python.org/downloads/windows/)
- copy and paste [the raw script](https://raw.githubusercontent.com/gtbjj/dnd-tools/master/scripts/dnd-tools) to a text editor
- Save the script as ```dnd-tools.py```
- [Execute script in terminal with Python](http://pythoncentral.io/execute-python-script-file-shell/)

---
**To Do / Feature Requests:**
If you would like a feature added, first check [issues tagged as enhancements](https://github.com/savagezen/dnd-tools/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement).  If you do not see the feature you are looking for, follow the [issue template for feature requests](https://github.com/savagezen/dnd-tools/blob/master/feature_request.md).

**Bugs:**
Please review [issues tagged as bugs](https://github.com/savagezen/dnd-tools/labels/bug) before making a new issue report.  Be as clear and descriptive as possible when making bug reports, including output logs and what steps you've attempted to remedy the problem yourself.

**Contributing:**
See [CONTRIBUTING.md](https://github.com/savagezen/dnd-tools/blob/master/CONTRIBUTING.md).
