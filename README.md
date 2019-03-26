Steps needed to update the base image

## Install all the config files in this repo.

* `cd ~`
* `git clone https://github.com/mycroftai/respeaker-dev-filesystem`
* `cd respeaker-dev-filesystem`
* `sudo cp -r * /`

## Fix the changed package repository label
* `sudo apt update`<br/>
  Answer yes to the question

## Install Lottie
* `sudo apt-get install qml-module-org-kde-lottie`

## Fix unicode issues in python
Set locale to a generic UTF-8

* `sudo update-locale LANG=C.UTF-8`

## Audio setup
Install alsa-utils:
* `sudo apt-get install alsa-utils`

Start alsamixer and 
* `alsamixer`<br/>
   increase all levels to ~60% (using arrow keys)

Store alsa settings:
* `sudo alsactl store`

## Device setup

* ```sudo nmtui```<br/>
  Change hostname to respeakercorev2-mycroft

## Create "respeaker" user, password "mycroft"
I did this by renaming "phablet" user.  It was a mess, but got done.

------------------------------------

# First use

## Setup network

* ```nmtui```<br/>
  pick you favorite network and enter the password
