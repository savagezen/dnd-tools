# dnd-tools

Interactive command line tools for Dungeons and Dragons 5th Edition.  This is the source code for the  python (v3.6) scripts and install functions used to create the [dnd-tools AUR package](https://aur.archlinux.org/packages/dnd-tools/).

---

#### Features:

- *Compeltely interactive:*  promted with start menu after every function
- *Character generator:*  any or all stat blocks and features can be randomized
- *Save generated character:*  export generated character to text file
- *Dice roller:*  any number of dice, any number of sides
- *Encounter calculator:* calculates modified experience per party size / level and monster party size (and CR)
- *Initiative roller:* random d20 rolls for x number of players (raw / without initiaitve bonus)
- *Tarokka card game:*  Tarrot card game from Curse of Strahd
- *Wild magic effects:*  Effect roller for Wild Magic sorcerers

---

#### Installation / Usage:

**Arch**:
~~~
$ yaourt -S dnd-tools
$ dnd-tools
~~~

**Other Linux**:
~~~
$ git clone https://github.com/gtbjj/dnd-tools
$ cd dnd-tools
$ sudo python setup.py install
$ /usr/bin/dnd-tools
~~~

**Windows:**

- Install [Python for Windows](https://www.python.org/downloads/windows/)
- copy and paste [the raw script](https://raw.githubusercontent.com/gtbjj/dnd-tools/master/scripts/dnd-tools) to Notepad++
- Save as ```dnd-tools.py```
- [Execute script in terminal with Python](http://pythoncentral.io/execute-python-script-file-shell/)

---

**To Do:**

- python 3.6 requirement in SRCINFO
- script features
  - magic shop generator
  - loot generator
  - downtime activities (random roller)
  - move lists / dictionaries to library files?
  - npc generator?
  - random adventure generator?
  - dungeon generator?
