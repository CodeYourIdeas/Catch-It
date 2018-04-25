# Catch-It

## Basic Info 

This is the traditional egg catching game made in Python. 
The user can make the basket move both sides using the arrow keys to collect as many eggs as he/she can which is the scoring factor but, he should avoid minions and bombs. 
There is also a provision to check out the highest score which is implemented using the files system.

## Instructions 

 * Ensure that you have Python (I prefer version 3.5+) installed on your system and the path is properly configured. </li>
 * Install the Git client. </li>
 * Clone this repository to your local machine. ` ` ` git clone https://github.com/jamesgeorge007/Catch-It ` ` `
 * Install pygame via the pip package manager => Open command prompt and type in py -m pip install pygame. 
 * You can find the main source file within the src directory. Run the code and you have the game 
 * Fork this repository and suggest me your ideas in the form of a pull request and also don't forget to star my repositories. 
  
  ## Screenshots 
  
  ### Main Menu 
  
  ![Main Menu](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/menu.JPG)
  
  ### Instructions 
  
  ![Instructions](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/instructions.JPG)
  
  ### High Score 
  
  ![High Score](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/high_score.JPG)
  
  ### Crashed 
  
  ![Crashed](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/crashed.JPG)
  
  ### Game Over 
  
  ![Game Over](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/game_over.JPG)
  
  ### Credits  
  
  ![Credits](https://github.com/jamesgeorge007/Catch-It-Egg-Catching-Game-in-Python/blob/master/res/Screenshots/credits.JPG)

About pygame
============

     Pygame is a cross-platfrom library designed to make it easy to
     write multimedia software, such as games, in Python. Pygame
     requires the Python language and SDL multimedia library. It can
     also make use of several other popular libraries.

     http://www.pygame.org

|TravisBuild|_ |AppVeyorBuild|_ |LaunchpadBuild|_ |PyPiVersion|_ |PyPiLicense|_ |Python2| |Python3|

Installation
============

     pip install pygame

     You should definitely begin by installing a binary package for your
     system. The binary packages usually come with or give the
     information needed for dependencies. Choose an appropriate
     installer for your system and version of python from the pygame
     downloads page. http://www.pygame.org/download.shtml

     Installing from source is fairly automated. The most work will
     involve compiling and installing all the pygame dependencies. Once
     that is done run the "setup.py" script which will attempt to
     auto-configure, build, and install pygame.

     Much more information about installing and compiling is available
     in the install.html file.

Help
====

     If you are just getting started with pygame, you should be able to
     get started fairly quickly. Pygame comes with many tutorials and
     introductions. There is also full reference documentation for the
     entire library. Browse the documentation from the documenantation
     index. docs/index.html.

     On the pygame website, there is also an online copy of this
     documentation. You should know that the online documentation stays
     up to date with the development version of pygame in hg. This may
     be a bit newer than the version of pygame you are using.

     Best of all the examples directory has many playable small programs
     which can get started playing with the code right away.

Credits
=======


     Thanks to everyone who has helped contribute to this library.
     Special thanks are also in order.


     Marcus Von Appen - many changes, and fixes, 1.7.1+ freebsd maintainer.

     Lenard Lindstrom - the 1.8+ windows maintainer, many changes, and fixes.

     Brian Fisher - for svn auto builder, bug tracker and many contributions.

     Rene Dudfield - many changes, and fixes, 1.7+ release manager/maintainer.

     Phil Hassey - for his work on the pygame.org website.

     DR0ID for his work on the sprite module.

     Richard Goedeken for his smoothscale function.

     Ulf Ekström for his pixel perfect collision detection code.

     Pete Shinners - orginal author.

     David Clark - for filling the right-hand-man position

     Ed Boraas and Francis Irving - Debian packages

     Maxim Sobolev - FreeBSD packaging

     Bob Ippolito - MacOS and OS X porting (much work!)

     Jan Ekhol, Ray Kelm, and Peter Nicolai - putting up with my early
     design ideas

     Nat Pryce for starting our unit tests

     Dan Richter for documentation work

     TheCorruptor for his incredible logos and graphics

     Nicholas Dudfield - many test improvements.

     Alex Folkner - for pygame-ctypes

     Thanks to those sending in patches and fixes: Niki Spahiev, Gordon
     Tyler, Nathaniel Pryce, Dave Wallace, John Popplewell, Michael Urman,
     Andrew Straw, Michael Hudson, Ole Martin Bjoerndalen, Herve Cauwelier,
     James Mazer, Lalo Martins, Timothy Stranex, Chad Lester, Matthias
     Spiller, Bo Jangeborg, Dmitry Borisov, Campbell Barton, Diego Essaya,
     Eyal Lotem, Regis Desgroppes, Emmanuel Hainry, Randy Kaelber
     Matthew L Daniel, Nirav Patel, Forrest Voight, Charlie Nolan,
     Frankie Robertson, John Krukoff, Lorenz Quack, Nick Irvine,
     Michael George, Saul Spatz, Thomas Ibbotson, Tom Rothamel, Evan Kroske,
     Cambell Barton.

     And our bug hunters above and beyond: Angus, Guillaume Proux, Frank
     Raiser, Austin Henry, Kaweh Kazemi, Arturo Aldama, Mike Mulcheck,
     Michael Benfield, David Lau

     There's many more folks out there who've submitted helpful ideas, kept
     this project going, and basically made my life easer, Thanks!

     Many thank you's for people making documentation comments, and adding to the
     pygame.org wiki.

     Also many thanks for people creating games and putting them on the
     pygame.org website for others to learn from and enjoy.

     Lots of thanks to James Paige for hosting the pygame bugzilla.

     Also a big thanks to Roger Dingledine and the crew at SEUL.ORG for our
     excellent hosting.



Dependencies
============

     Pygame is obviously strongly dependent on SDL and Python. It also
     links to and embeds several other smaller libraries. The font
     module relies on SDL_tff, which is dependent on freetype. The mixer
     (and mixer.music) modules depend on SDL_mixer. The image module
     depends on SDL_image, which also can use libjpeg and libpng. The
     transform module has an embedded version of SDL_rotozoom for its
     own rotozoom function. The surfarray module requires the python
     numpy package for its multidimensional numeric arrays.

Todo / Ideas (feel free to submit)
==================================

       http://www.pygame.org/wiki/todo

License
=======

     This library is distributed under GNU LGPL version 2.1, which can
     be found in the file "doc/LGPL". I reserve the right to place
     future versions of this library under a different license.
     http://www.gnu.org/copyleft/lesser.html

     This basically means you can use pygame in any project you want,
     but if you make any changes or additions to pygame itself, those
     must be released with a compatible license. (preferably submitted
     back to the pygame project). Closed source and commercial games are
     fine.

     The programs in the "examples" subdirectory are in the public
     domain.




.. |TravisBuild| image:: https://travis-ci.org/illume/pygame.svg?branch=master
.. _TravisBuild: https://travis-ci.org/illume/pygame

.. |AppVeyorBuild| image:: https://ci.appveyor.com/api/projects/status/d9mypp9f4ubrmqf7?svg=true
.. _AppVeyorBuild: https://ci.appveyor.com/project/pygame/pygame-temp-m8dun

.. |LaunchpadBuild| image:: http://pygame.org/images/launchpad_build.svg?svg=true
.. _LaunchpadBuild: https://code.launchpad.net/~pygame/+recipe/pygame-daily

.. |PyPiVersion| image:: https://img.shields.io/pypi/v/pygame.svg?v=1
.. _PyPiVersion: https://pypi.python.org/pypi/pygame

.. |PyPiLicense| image:: https://img.shields.io/pypi/l/pygame.svg?v=1
.. _PyPiLicense: https://pypi.python.org/pypi/pygame

.. |Python2| image:: https://img.shields.io/badge/python-2-blue.svg?v=1
.. |Python3| image:: https://img.shields.io/badge/python-3-blue.svg?v=1




