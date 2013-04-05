Chocolatey Dev Machine
======================

A [Chocolatey](http://chocolatey.org/) package config for getting a new developer machine up and running.

Wait, what?
-----------

Chocolatey is like Nuget for applications and more.  Installation of [Chocolatey](http://chocolatey.org/) is super easy, and the instructions are right on the homepage.  

THIS package tries to get your new dev machine up and running in no time.  It installs a bunch of apps that most Windows devs will/should use.  If you want to know what those are, just take a peak at the very clean .config file (the only other file in the repo).

Usage
-----

Assuming you've installed [Chocolatey](http://chocolatey.org/), just run this from the repo folder:

    cinst .\chocolatey_packages.config

That's it!  Everything in the current package should install silently, but check it every so often to make sure it's still going.
