# dnd-tools

Interactive command line tools for Dungeons and Dragons 5th Edition.  This is the source code for the  python (v3.6) scripts and install functions used to create the [dnd-tools AUR package](https://aur.archlinux.org/packages/dnd-tools/).

---

#### Features:

- Compeltely interactive (menu prompt after each function completes)
- Character generator (can be completely random)
- Save generated characer file as text file
- Dice roller (any number of dice, any number of sides)
- Tarokka card game (Tarrot cards from Curse of Strahd)
- Wild Magic effect roller (for Sorcerers)
- Initiative roller (raw / without proficiency bonus)

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

- script features
  - loot generator
  - move lists / dictionaries to library files?
  - npc generator?
  - random adventure generator?