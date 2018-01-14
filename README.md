AospKenzo
===========

Getting Started
---------------

To get started with aospkenzo, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).
Also refer [aosp initializing guide](https://source.android.com/setup/initializing).

To initialize your local repository using the LineageOS trees, use a command like this:

    repo init -u https://github.com/aospkenzo/manifest.git -b oreo-8.1

Then to sync up:

    repo sync

Build the rom
---------------

Do the following:

    source build/envsetup.sh
    lunch device_name
    make otapackage
