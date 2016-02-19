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

## Submitting changes

Thanks for fixing up anything broken in here! Here's all you need to do:

1. Run "npm install"
2. Add your changes in your fork.
3. Run "npm test"
4. Update the HEAD section in CHANGES.md with a description of what you have done.
5. Push your changes and create the PR, and I'll try to get this merged in right away.
