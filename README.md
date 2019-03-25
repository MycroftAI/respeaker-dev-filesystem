Steps needed to update the base image

Install all the config files in the repo.

## Fix the changed package repository label

Run
    `sudo apt update`

Answer yes to the question

## Fix unicode issues in python

Set locale to a generic UTF-8

Run
    `sudo update-locale LANG=C.UTF-8`

## Audio stuff

Install alsa-utils:
    `sudo apt-get install alsa-utils`

Run alsamixer and increase all levels to ~60%

Store alsa settings:

    `sudo alsactl store`
