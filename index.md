---
layout: default
title: Cheng Sun - Home
---

# Blog

{% for post in site.posts %}
* {{ post.date | date: "%Y-%m-%d" }} &ndash; [{{ post.title}}]({{ post.url }})

{% endfor %}

# JavaScript Hackery

* Revision question sets
    * [OCR AS Economics](economics.html) questions
    * [OCR AS Physics material vocab](physics.html) questions

* [ocreMutiny](ocremutiny.html) -- a tiny (just over 1K) emulator for the OCR A2 Electronics assembly language

* Verlet integration experiments
    * [Ribbon](verletribbon.html) in low gravity
    * [Triangles](verlettri.html)
    * [Interactive ragdoll game](verletrag.html)
    * [Interactive bridge simulation](verletbridge.html) (unfinished)

* 3D experiments with 2D canvas
    * [Morphing points](points.html)
    * [Rotating 3D cube](cube.html)

* Fractals and automata
    * [Animated Julia set](julia.html). Uses randomised backwards iteration
    * [Tinkerbell map](tinkerbell.html)
    * [Langton's ant](walk.html) I used this to visualise [a PE problem](http://projecteuler.net/problem=349). There is a bug when the ant hits the edge of the simulation; the glider pattern is meant to continue forever.

* [Minesweeper](mine.html)

* [Snake in 1K](snake.html)

# Things I do

* I am part of [Systemetric](http://systemetric.org/), the Hills Road Sixth Form College robotics team. We build and code autonomous robots for the [Student Robotics](https://www.studentrobotics.org/) competition. Find us on [GitHub](https://github.com/Systemetric).

* I worked on the [VLC Mozilla browser plugins](https://github.com/chengsun/gtk-npapi-vlc) as part of [Google Code-In 2011](http://google-opensource.blogspot.co.uk/2012/02/google-code-in-2011-grand-prize-winners.html).

* I developed the [Mozilla SPDY indicator](https://addons.mozilla.org/en-US/firefox/addon/spdy-indicator/), a Firefox addon that indicates when a web page was served through [SPDY](http://www.chromium.org/spdy).

* I do competitive algorithmic coding, and was part of the [British team](http://olympiad.org.uk/2011/index.html) in the [International Olympiad in Informatics 2011](http://www.ioi2011.or.th/).

# Other stuff

I am a user (and big fan) of [Arch Linux](https://www.archlinux.org/). Give it a try -- it's fun!

I sometimes play NetHack on <a href="http://alt.org/nethack/plr.php?player=infinigon">NAO</a>.

[![Project Euler](http://projecteuler.net/profile/infinigon.png)](http://projecteuler.net)