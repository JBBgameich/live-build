## building the debian package

Please make sure you have installed devscripts and build-essential.

* `git clone http://github.com/jbbgameich/live-build.git`
* `cd live-build`
* `dpkg-buildpackage -S`
* `dpkg-buildpackage`

To install the built package use:

* `sudo dpkg -i ../live-build*.deb`

There is a prebuild version available [here](http://bit.ly/2p5lr46).