http://www.python.org/pypi/tg2exe/

tg2exe is a 'tg-admin' command line utility extension
> which could help you converting the TurboGears project to an
> Stand Alone Application on windows platform.

Advantage

---

The benifit is you can use TurboGears' power to write
Off-line applications with web interface and AJAX.

When the application is running, your computer host as
a web server (Actually it is).

Your user can quickly evaluate your application without install
python or related modules.

Install

---

You could use::

> $ easy\_install tg2exe

command to install this module

pywin32 is required
http://sourceforge.net/projects/pywin32/

Usage

---

Once you installed tg2exe, you'll got an 'makexe' command within
the 'tg-admin' command line utility.

Enter your project folder, type::

> tg-admin makexe

and tg2exe will produce a dist folder for you.

This utility does not make an **.exe, it assembles all the
dependencies and runtime libraries into a single directory,
so that it's easy to wrap everything into a single setup package.**

You are free to package 'dist' folder into an installer (such as InnoSetup).

Notice that the stand alone file are equivalent to production project,
so you need to have a setted prod.cfg. The simple approach is to
rename the sample-prod.cfg to prod.cfg.