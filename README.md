About this fork
===============

All credits go to [Fushar](http://fusharblog.com/apps/testerdream/).
This fork implements one feature I find very usefull: boilerplate code for stress check on randomly generated test cases. It just adds section for it in code, increases number of test iteration to 100 and passes new seed to child process every time to generate new tests every time. Also prints out seed number in case you need to reproduce a test.

***

TesterDream - A TopCoder Arena Plugin
=====================================

Building TesterDream
------------------------

First, clone a copy of TesterDream git repository by running:

```bash
git clone git://github.com/fushar/testerdream.git
```

You willl need to have Java Development Kit and Apache Ant in order to build TesterDream. After they are installed, run:

```bash
ant
```

in the TesterDream directory.

The built version of TesterDream can be found in the `dist/` subdirectory.

Installing TesterDream in TopCoder Arena
----------------------------------------

Follow the instruction in the official [TesterDream website](http://fusharblog.com/apps/testerdream).

License
-------

TesterDream is licensed under MIT License.
