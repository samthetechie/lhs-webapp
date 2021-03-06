Webapp
======

__author__ = "Samuel Carlisle"

__copyright__ = "Copyright 2012"

__credits__ = ["Samuel Carlisle, Martin Clarke, Alan Ross"]

__license__ = "GPL Affero"

__version__ = "3"

__maintainer__ = "Samuel Carlisle"

__email__ = "samuelcarlisle@gmail.com"

__status__ = "Prototype"


```
                                                   ____
       ___                                      .-~. /_"-._        ________________________________
      `-._~-.                                  / /_ "~o\  :Y      /We made Sukey.io so that people \
          \  \                                / : \~x.  ` ')      |can have fun during the protests|
           ]  Y                              /  |  Y< ~-.__j      |and, on the way, keep each other|
          /   !                        _.--~T : l  l<  /.-~      < safe, mobile and informed (;..;)|
         /   /                 ____.--~ .   ` l /~\ \<|Y          \________________________________/
        /   /             .-~~"        /| .    ',-~\ \L|
       /   /             /     .^   \ Y~Y \.^>/l_   "--'
      /   Y           .-"(  .  l__  j_j l_/ /~_.-~    .
     Y    l          /    \  )    ~~~." / `/"~ / \.__/l_
     |     \     _.-"      ~-{__     l  :  l._Z~-.___.--~
     |      ~---~           /   ~~"---\_  ' __[>
     l  .                _.^   ___     _>-y~
      \  \     .      .-~   .-~   ~>--"  /
       \  ~---"            /     ./  _.-'
        "-.,_____.,_  _.--~\     _.-~
                    ~~     (   _}  
                            `. ~(
                              )  \
                             /,`--'~\--'

```

This README.md file is part of Sukey.io.

Howto Sukey Community
=====================
* Follow us on twitter @sukeyio say hey with #sukey

* Say hi over at sukey.org@gmail.com so we know you are interested in developing Sukey and then we can say hi back.

* Join us on #sukey on irc.freenode.net and lurk with us. :)

* Submit pull requests on Github and add new python scripts and ideas: https://github.com/sukey/webapp

* Submit issues on the issue tracker: https://github.com/sukey/webapp/issues

Howto Frontend
==============
* Install XMPP or Apache or ...

* Symlink or copy the 'Frontend' folder over to the Apache web directory for Testing in the browser on http://127.0.0.1/Frontend (linux /var/www) or (windows /www/htdocs)

Howto Backend
=============
* Install Python 2.7.3

* Signup as a developer over at http://human.io/

* Do their HelloWorld Tutorial: http://human.io/docs/tutorial1

* Download their python SDK: http://human.io/static/humanio-python-api.tgz

* Download and play with some of their other examples: https://groups.google.com/forum/#!topic/humanio-discuss/FWHzvWTUuus

* You can get in touch with the human.io developers here: https://groups.google.com/forum/?fromgroups#!forum/humanio-discuss

* Run Sukey backend scripts. e.g. python shameonyou.py (I often use a screen session in linux terminal to minimse the number of open terminal windows)


Description
===========
Sukey.io is a frontend webapp designed for mobile phones (mainly tested with a Galaxy S2) and a backend collection of python scripts for the human.io platform which faciliate and foster collaboration between protesters by inviting people at the demo who use sukey.io to support each other by completing microtasks (think amazon Mechanical Turks for protests). All this is done while they are at the demonstration but there are also ways in which people can support a demonstration, wherever they are in the world by helping to verify information coming out from the protest by searching and using datasets (e.g. twitter, twitpic, google street view and google maps searches). By participating you can help solve a real need of people on the ground. For example some groups of people will take photos of banners and placards, while some others rate them. Some people will observe which roads have been closed or are slow to travel down and report them as such while will suggest alternative routes.

How people can help from other countries
========================================
* Non-Lingual Micro-Tasks (participant's lingua franca different from country where protest is taking place).

Introduction / Theory
=====================
Sukey.io, in concept, is a sequence of Stimulus:Response mappings which have been devised in order to help demonstrators collaborate effectively during a demonstration.

Example:

Stimulus0: We find a tweet online which says "there is a kettle forming on Whitehall, OMG, get out of there!"

Response0: We launch a localised (to whitehall's co-ordinates and the immediate locality) micro questionnaire which simply asks: "Is there a Kettle here?" and can you take a photo of it?

Stimulus1: We receive photos and verification of the fact that the kettle is on

Response1: We can then faithfully tweet out a report that the kettle is indeed happening.
