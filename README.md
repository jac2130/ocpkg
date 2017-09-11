## Collection of scripts

#### ocpkg
* It is a script to install an OpenCog development environment on a fresh installation of Ubuntu >= 14.04 . It has options to selectively download, build, test, install and package OpenCog projects. Don't use the package option, as it
is still work in progress.

For a quick start using Ubuntu version >= 14.04, run
```
 wget http://raw.github.com/opencog/ocpkg/master/ocpkg -O octool && chmod +rx octool && ./octool -h
```

For detailed instructions see [here](http://wiki.opencog.org/wikihome/index.php/Building_OpenCog#octool_for_ubuntu)

#### octool-wip
The separate octool script is not yet ready so use the ocpkg's file renamed as octool. See above.

#### ocbootstrap
(This hasn't been tested for a while)
A script to create an OpenCog build environment on ''any'' Linux system.

#### ocfeedbot
An IRC bot of some sort, purpose not clear.

Uses debootstrap. Requires ocpkg.

#### octool_rpi
For installing opencog on a Raspberry Pi Computer running Raspbian. 
The readme [here](https://github.com/opencog/opencog_rpi/blob/master/README.md) will be helpful.


#### Usages
* To install all dependencies necessary to build OpenCog:
```
 ./octool -rdpcalv
```

* To install all dependencies necessary to build AtomSpace and MOSES:
```
 ./octool -rdcv
```

* To install all dependencies necessary to build Cogutils:
```
 ./octool -rdv
```
