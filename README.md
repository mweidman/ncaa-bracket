ncaa-bracket
============

What is this?
-------------

Interactive and printable bracket for the annual NCAA March Madness basketball tournament.  This is not responsive, but please feel free to fork this and make it so. We accept pull requests! Demo: http://www.bracketadvisor.com/interactive-bracket/

![interbrack](screenshots/interbrack.png)

Credits
---------

Nelson Hsu

Assumptions
-----------

* Google docs
* jQuery
* Miso

What's in here?
---------------

The project contains the following folders and important files:

* ``index.html`` -- Blank bracket
* ``/js`` -- Javascript
* ``/css`` -- Strangely enough, stylesheets

How to use this
---------------

1. Make a copy of this Google doc: https://docs.google.com/spreadsheet/ccc?key=0AurS2EUbrPERdHBkR3VuR3FRSC00QlpmWXJPcnBhUGc&usp=sharing
2. The teams for each region are in separate tabs including the play-in games.  All the labels are in the last tab. Once you have entered all the teams and information, "Publish to the web..."
3. In the Publish window, you'll find a URL that will contain a key. Copy that and paste into line 16 of js/bracket.js

License
----------

This code is available under the MIT license. For more information, please see the LICENSE file in this repo.


