"Rice Racer" - A tribute to Sega's 1988 Arcade Game "Power Drift"

Play online at: https://py2.codeskulptor.org/#demos-riceracer.py

I was trying to think of which classic arcade game would be a good match for the tools provided
by CodeSkulptor and SimpleGUI. SimpleGUI's most exciting graphical feature is the ability to
scale and rotate images, so I started thinking of the sprite-scalers from the mid-80's, like
Space Harrier, Out Run and Afterburner. However, the one I remember most vividly is an outrageous
driving game called Power Drift, which challenged the player to race around tracks that resembled
roller coasters more than motor racing circuits.

Programming - Steven Knock
Music       - Andy Denton
Graphics    - Car, courtesy of Pete Carpenter of http://www.rc-airplane-world.com
            - Trees, from http://www.immediateentourage.com
            - Horizon, http://en.wikipedia.org/wiki/File:Spitzkoppe_360_Panorama.jpg
            - Track, generated using Paint Shop Pro

Current Version (v1.4 - 11th July 2013):
  in which I updated the code to work with CodeSkulptor's new integer and float rules.

Earlier versions:
v1.3 - 13th March 2013:
  in which I added the horizon, music, sound effects, player images, new track, new car images
  and increased the difficulty.

v1.2: http://www.codeskulptor.org/#user8-gRnuT0e3vD-0.py
  in which I updated the code to work with the latest version of CodeSkulptor.

v1.1: http://www.codeskulptor.org/#user6-UbZVApbT6ahIJnI.py
  in which I added a mini-map and increased the frame rate.

v1.0: http://www.codeskulptor.org/#user6-oD2uRenZ5yXlpWp.py

There are a few important points:

The game requires a moderately quick computer to run at an acceptable rate, and I strongly recommend
running it in Chrome rather than Firefox. In Chrome, I get a steady 20fps (v1.1), which is fine,
whereas in Firefox I get 5fps which is unplayable.

To add additional opponents, simply add names to the PLAYERS array defined at the top of the code.

It's also straightforward to create your own tracks. The pre-defined tracks are defined inside a
routine called _define_tracks() and consist of pairs of coordinates and tangent vectors, collectively
called "control points". Search the web for "Hermite Curves" for more information.

Apologies for the single character indents, but this was necessary to reduce code size since I
exceeded CodeSkulptor's 64k limit.

The game loads several images when it starts. Sometimes, an image inexplicably doesn't get loaded
and so the game will keep telling you that it is waiting for images to load. If this happens, the
easiest thing is just to restart the game.

Burn rubber!
