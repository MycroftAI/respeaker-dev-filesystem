Fix the changed repo label

Run
    sudo apt update

Answer yes to the question

Set locale to a generic UTF-8

Run
    sudo update-locale LANG=C.UTF-8

Audio setup

Install etc/udev/rules.d/91-pulseaudio.rules
Install usr/share/pulseaudio/alsa-mixer/profile-sets/seeed-voicecard.conf

Add the files in the directory tree

Install alsa-utils:
sudo apt-get install alsa-utils

Run alsamixer and increase all levels to ~60%

Store alsa settings:

sudo alsactl store

Fix the changed repo label

Run
    sudo apt update

Answer yes to the question

Set locale to a generic UTF-8

Run
    sudo update-locale LANG=C.UTF-8


etc/xdg

    kwinrc
    kdeglobals


