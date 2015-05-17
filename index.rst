*********************
GIFs as Documentation
*********************

This is a short guide to using GIFs *in* documentation and *as* documentation.
Animated GIFs are a great tool for making documentation, but it takes some special care and attention to make them work.

This guide was started on May 16, 2015 by Daniel D. Beck on his flight to Portland, Oregon
en route to attend the Write the Docs conference.
Your contributions to this guide are welcome!
If you have a suggestion to improve this guide, please `open an issue on GitHub`__ or `tweet @ddbeck`__.

.. __: https://www.github.org/ddbeck/gifs-as-documentation/issues
.. __: https://twitter.com/ddbeck

.. note::

   This guide will use "animated GIF" and "GIF" interchangeably.
   GIFs aren't necessarily animated, but this guide is only considering GIFs that are animated.


Why GIFs?
=========

The phrase "animated GIF" conjures up something frivolous but animation in general has a long history of being used to
to do everything from `telling engaging stories`__ to helping people understand `complicated technical subjects`__.
GIFs, as a specific form of short animation, have many strengths that make them a good tool for technical communicators:

.. __: http://
.. __: http://

.. todo:: Add link to Apollo entry, descent, and landing animation.
.. todo:: Add link to some old, famous animated movie.

* GIFs are much easier to make than high definition video.
  GIFs have lower audience expectations, because GIFs are silent and often grainy, short, and low-resolution.
  A series of animated GIFs can be made at lower cost than making a full-length video.

* GIFs can be used for numerous contexts.
  GIFs can instruct users, illustrate problems for customer support, or mockup a new idea for the design process.

* GIFs support content reuse.
  A GIF made for documentation can be reused in marketing or support contexts (and vice-versa).

* Animated GIFs do not have the negative associations of auto-playing video (because they're intrinsically silent).
  With a GIF, you can get away with showing something to a viewer that they might not otherwise have been receptive to.

* Compared to traditional web video, GIFs are relatively frictionless from the perspective of your audience.
  Unlike a YouTube video, there's no need to click play, because browsers automatically load and run GIFs.
  GIFs are natively supported by effectively all browsers, unlike many video formats and players,
  so your audience doesn't need to install a plugin to see it.

* Compared to a sequence of still images, GIFs are less cognitively demanding.
  Your viewer doesn't have to mentally interpolate frames between still images, because the frames actually exist.
  For example, trying to follow step-by-step drawings of how to tie a knot can be much more challenging than watching
  an animated equivalent.

* GIFs can be embedded pretty much anywhere and be reasonably expected to work.
  So you can use a GIF in a technical document just as easily as in a tweet or an email.

* GIFs can be used as prototypes or storyboards for full-scale video production.
  You can use GIFs to make a proof-of-concept for a video or as part of the script writing process.

* Finally, GIFs are fun.
  They can add a dash of excitement, action, or texture that static text and graphics can't.

Of course, GIFs aren't ideal for every situation.
At least for the time being, they're useless in print media.
And for many applications and audiences, they cannot replace traditional video or well-placed still images.
But with judicious use, you may find that animated GIFs complement your existing documentation tools and skills.



Guidelines for Using GIFs
=========================

If you're convinced to give GIFs a try, don't just start littering your docs with memes and scrolling text.
Consider these guidelines for using GIFs:

* GIFs should be **supplementary to** other kinds of documentation
  or be **supplemented by** other kinds of documentation.
  GIFs are rarely a substitute for writing things down.
  Also remember that members of your audience may have reduced vision or blindness.
  An over-dependence on GIFs and video poses serious accessibility problems.
  Screen readers can't read images (yet) and it can be difficult to write meaningful alt text for animations.

* GIFs should be used sparingly.
  Many animations visible on screen can be distracting or confusing, especially if they're mixed with other text.
  Too much visual noise from competing animations can hinder your audience's ability to appreciate anything on screen.

* GIFs should be small.
  GIF isn't an efficient image format and GIFs don't load particularly gracefully, so keep your file sizes in check.
  If overused, GIFs can cause your page size to balloon out of control,
  to the point that your audience may give up and leave your documentation rather than waiting on your page to load.

* GIFs should be short.
  If you can't quickly tell where in the action the animation is (i.e. beginning, middle, or end),
  it's hard to learn anything from the animation.
  You can get away with longer animations if you add some kind of signposting
  (e.g., numbered steps, a time stamp, or a pause at the beginning of the sequence),
  but at some point the lack of playback control (e.g., play, pause, and rewind) proves too frustrating,
  even if the GIF's file size doesn't catch up with you first.



Kinds of GIFs
=============

I've identified or conceived of a few ways GIFs may be used in documentation and as documentation:
decorative, demonstrative, familiarizing, instructional, and narrative.
This is probably not comprehensive, but it might help you get started.


Decorative
----------

Decorative GIFs that don't add anything to the subject matter of the documentation per se,
but serve to connect you and your audience through shared cultural touchstones, jokes, and enthusiasm.
This is by far the most common way GIFs are used in documentation, but they're rarely ever used *as* documentation
(except in this document, go figure).

**Patterns:**

* Success or failure intensifiers
* In-jokes
* Memes

**Examples:**

*  It's happening!

 .. todo:: add Ron Paul "It's happening!" GIF

*  Deal with it

 .. todo:: add Riker beard GIF



Demonstrative
-------------

Demonstrative GIFs show what something is or what it does,
but without the expectation that the viewer is meant to be able to reproduce the demonstration themselves.
This is the most common kind of GIF as documentation that I've seen.

**Patterns:**

*  Showing the behavior of the end result of a process that your documentation teaches.
*  Showing a 360-degree walk around of a product

**Examples:**

*  The documentation for a Python library I wrote, Oraide, shows how the library simulates someone typing text.
   The GIF doesn't show the the interface to produce the results, just the result.
   The GIF alone provides insufficient information for the viewer to do the same.

   .. todo:: Add Oraide GIF

*  The Node.js library ADDNAME provides an interface for generating a graphical user interface (GUI) with curses.
   Their README contains a long animated GIF that shows what the library produces (that is to say, the GUI),
   but not the code to produce the interface.
   There's no way that a viewer could produce the same results themselves by watching the GIF alone.

   .. todo:: Add Node.js library name and link
   .. todo:: Add link to curses description.
   .. todo:: Add curses GIF


Familiarizing
-------------

Acquainting the the viewer with something that they're going to do themselves,
but with the expectation that more detail is forthcoming.

**Patterns:**

*  The preview GIF that shows the performance of complicated task as an introduction to step-by-step instructions
*  The screencast in miniature

**Examples:**

  .. todo:: Add examples! Maybe one of those tie-a-bowtie GIFs I've seen.


Instructional
-------------

Instructional GIFs show something that the viewer is meant to do themselves.

**Patterns**:

*  Showing a single step of a task.
*  Showing a single step of a task with annotations.
*  The screencast in miniature

**Examples**:

*  Crochet GIFs.

   .. todo:: Add crochet GIF.


Narrative
---------

Narrative GIFs tell a story.
Telling a story with a GIF can connect the thing you're trying to teach your user on a personal level.
Narratives help contextualize your documentation in the world that your audience lives in.

**Patterns**:

*  A before-and-after sequence
*  Warnings or cautions by showing an incorrect action followed by a negative consequence

**Examples**:

.. todo:: I don't actually have an example of this yet, though I do have an idea for doing one myself.


How to Make a GIF
=================

There's generally three ways to make a GIF:

* Record directly to the GIF format
* Record video and convert to GIF
* Convert two or more still images into a GIF animation

This section attempts to suggest tools and other resources for using such


Recording directly to GIF
-------------------------

* LICEcap captures part of your screen, like other screencasting software, and saves the result as an animated GIF.
  This is quite possibly the easiest way to make an animated GIF,
  though it's only useful for making software-related documentation.

  .. todo:: Add link to LICEcap

.. todo:: Add links to GIF apps for Android


Converting video to GIF
-----------------------

.. todo:: Add link to tutorial that shows how to use ffmpeg or ImageMagick to convert video to GIF



Converting stills to GIF
------------------------

.. todo:: Add link to tutorial that shows how to use ImageMagick to convert a directory of frames to GIF.



Additional resources
====================

* GIFsicle is a useful tool for optimizing GIFs.
  It can significantly reduce your GIF's file size,
  enabling you to use it bandwidth or file-sized constrained contexts like mobile browsers and Twitter.
  (which imposes a somewhat draconian file size limitation).

  .. todo:: Link to GIFsicle

.. todo:: Add links to image hosting services

.. todo:: Add link to giphy