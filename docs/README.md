first_nes project - Your first NES game!
=================


<!---
[![GitHub issues](https://img.shields.io/github/issues/kashaiahyah85/NES-Game.svg)](https://github.com/kashaiahyah85/NES-Game/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/kashaiahyah85/NES-Game.svg)](https://github.com/gregkrsak/kashaiahyah85/NES-Game/)
-->
[![Assembly language](https://img.shields.io/badge/language-assembly%20language-blue.svg)](https://github.com/kashaiahyah85/NES-Game/blob/master/first_nes.s)


Create your own games for the Nintendo Entertainment System with this "starter" project!


Boilerplate code is provided!       |  Instantly get up and playing!
------------------------------------|-----------------------------------
![Image: Editing](https://i.imgur.com/EabWh01.png "Boilerplate code is provided! Just add custom libraries, and graphics if you'd like.")  |  ![Image: Running](https://i.imgur.com/GcwC0tR.png "Instantly get up and playing!")


Getting started
===========

Install the cc65 binutils:

### Linux
```
sudo apt-get install -y cc65
```

### OSX
```
brew install cc65
```

### Windows
Make sure git and [make](https://sourceforge.net/projects/gnuwin32/files/make/3.81/make-3.81.exe/download?use_mirror=iweb&download=) are installed and download the cc65 binutils from [here](https://sourceforge.net/projects/cc65/files/latest/download) and extract it to somehwere in your system path.

### All
Now start your project from this template, click "use template" at the top of this page.

```
MY-USER-NAME= Your Username on github
NES-Game= The name you gave your new repo made from this template
git clone https://github.com/${MY-USER-NAME}/${NES-Game}
cd ${NES-Game}
make
```

Now go ahead and run the ```${NES-Game}.nes``` file. You can move the copyright-neutral-green-construction-worker character back and forth with the A and B buttons.


Credits
=======

Authors:
--------

- Written by Greg M. Krsak ([email](mailto:greg.krsak@gmail.com)), 2018

Standing on the shoulders of giants:
------------------------------------

- Based on the [NintendoAge "Nerdy Nights" tutorials](http://nintendoage.com/forum/messageview.cfm?catid=22&threadid=7155), by bunnyboy

- Based on ["Nintendo Entertainment System Architecture"](http://fms.komkon.org/EMUL8/NES.html), by Marat Fayzullin
 
- Based on ["Nintendo Entertainment System Documentation"](https://emu-docs.org/NES/nestech.txt), by Jeremy Chadwick

Additional thanks to:
---------------------

- [@elennick](https://github.com/elennick) for testing the Mac OS quick start instructions (Issue [#22](https://github.com/gregkrsak/first_nes/issues/22)).

- [@hxlnt](https://github.com/hxlnt) for expanding the credits (PR [#33](https://github.com/gregkrsak/first_nes/pull/33)).

- Reddit user u/Rocky99433 for prompting me to fix the Windows quick start instructions (Issue [#21](https://github.com/gregkrsak/first_nes/issues/21)).

- [@ericandrewlewis](https://github.com/ericandrewlewis) for correcting some bad comments (PR [#53](https://github.com/gregkrsak/first_nes/pull/53)).


About my Development Environment
================================

- **Target CPU:** 8-bit, [Ricoh RP2A03](https://en.wikipedia.org/wiki/Ricoh_2A03) (6502), 1.789773 MHz (NTSC)

- **Assembler:** ca65 (cc65 binutils)


Tested on:
----------

- Linux with Nestopia UE 1.47

- Windows with Nestopia UE 1.48


Additional Resources
====================

NES programming in general:
---------------------------

- [Wikibooks: NES Programming](https://en.wikibooks.org/wiki/NES_Programming)

- [NesDev](http://nesdev.com/)

The ca65 assembler:
-------------------

- [ca65 Documentation](http://cc65.github.io/doc/ca65.html)

- [cc65 GitHub repository](https://github.com/cc65/cc65)

Building this project:
----------------------

- This project's [Makefile](https://github.com/gregkrsak/first_nes/blob/master/Makefile)

- [Makefiles: A Tutorial by Example](http://mrbook.org/blog/tutorials/make/)


first_nes was written by [Greg M. Krsak](https://github.com/gregkrsak/), 2018. You may send him an email using [this address](mailto:greg.krsak@gmail.com). If you'd like to contribute to his project, [click here](https://github.com/gregkrsak/first_nes/blob/master/docs/CONTRIBUTING.md) to learn how.
