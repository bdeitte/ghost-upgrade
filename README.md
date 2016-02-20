# ghost-upgrade

A command-line tool for upgrade Ghost.  It takes the instructions from [Ghost support](http://support.ghost.org/how-to-upgrade/) and makes them automagic.

[![Build Status](https://secure.travis-ci.org/bdeitte/ghost-upgrade.png?branch=master)](http://travis-ci.org/bdeitte/ghost-upgrade)

[![NPM](https://nodei.co/npm/ghost-upgrade.png)](https://nodei.co/npm/ghost-upgrade/)

## Usage

```
npm install -g ghost-upgrade
ghost-upgrade
```

## Command-line options

```
  -y, --yes  Yes I want to really upgrade and have prepared for it as
             discussed in http://support.ghost.org/how-to-upgrade/
  -l, --location  Location of Ghost install
  -c, --copy-casper Whether to copy Casper files
```

## Cavaets

This tool requires Node 4 or higher.

This tool skips one optional step in the manual steps, to chown the files.  If you have a permissions problem after running this script, that's what happened.  Run chown on your ghost directory to change to the needed user to fix up.

This was created to simplify the steps in [a Ghost on AWS guide](https://github.com/bdeitte/ghost-on-aws) and for use on one small personal blog.  Any issues destroying your own blog with these upgrade steps... well, I'm very sorry if that does happen!  It is a very simple program, as you can see in bin/ghost-upgrade.  Make sure you understand what the upgrade really does before running it.

## Submitting changes

Thanks for fixing up anything broken in here! Here's all you need to do:

1. Run "npm install"
2. Add your changes in your fork.
3. Run "npm test"
4. Update the HEAD section in CHANGES.md with a description of what you have done.
5. Push your changes and create the PR, and I'll try to get this merged in right away.
