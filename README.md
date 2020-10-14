# Micro-Project-Android

## Overview


## Option 1: Run script outside Docker - in your host OS

Two scripts are available:

* `build-html-docker.sh` -> builds the .html-pages in the folder gh-pages
* `publish-gh-pages.sh` -> builds and deploys the gh-pages

additionally is a script `build-pdf-docker.sh` for creating a pdf document.


## Option 2: [preferred] Run script inside Docker-container

* First create a `.env`-file with
```
GIT_GLOBAL_MAIL=<your email>
GIT_GLOBAL_USER_NAME=<your git - username>
```
* Then run the script `run-inside-docker.sh`.
* The url of the created gh-page will be displayed. 

## How to use Asciidoctor

Download the latest [release](https://github.com/htl-leonding-college/asciidoctor-docker-template/releases) in your project and run the shell-scripts.

## Demo Documents

You can find demo documents in the `asciidocs.demo`-folder:

- System Specification (Pflichtenheft)
- Minutes of Meeting
- some additional demos

