---
layout: default
title: API Libraries
---

## API Implementations ##

Libraries for accessing the GitHub API from your favorite language.

### C Sharp ###

[GitHubSharp][gs] looks pretty slick - hot off the press.

[gs]: http://github.com/erikzaadi/GithubSharp

### Javascript ###

[github-api][ghjs] is a Javascript library with no dependencies for interop
with the github API. Currently supports a large portion of V2, with more to
come. Tries to map directly to the HTTP API, but in a JS style.

[ghjs]: http://github.com/fitzgen/github-api

The [node-github][ng] library is a port of [php-github-api][pga] to JavaScript for [node.js][node]. It provides an asynchronous object oriented API and is fully tested.

[ng]: http://github.com/ajaxorg/node-github
[node]: http://nodejs.org/

### Perl ###

The [Net::GitHub][net-perl-github] library for Perl encapsulates much
of the functionality of the GitHub v2 API.  You can also download it
from [CPAN][net-perl-cpan].

[net-perl-cpan]: http://search.cpan.org/dist/Net-GitHub/
[net-perl-github]: http://github.com/fayland/perl-net-github/tree/master


### PHP5 ###

The [php-github-api][pga] is fully tested and documented.

[pga]: http://github.com/ornicar/php-github-api

### Python ###

[Dustin Sallings'][dustin] [py-github][py-github] project was the
first third-party implementation of the v1 API and is tracking the v2
API in a branch as new API endpoints are published. [Fork
it][py-github] it and help keep it awesome.

There is alo a new Python library for the GitHub v2 API called
[python-github2][python-github2].  It has nearly the full API feature
list.

[Kenneth Reitz's][kennethreitz] [GistAPI.py][gistapi] is a Python wrapper for the Gist API. New Gist API features will be introduced as the API endpoints are published.

[dustin]: http://github.com/dustin
[kennethreitz]: http://github.com/kennethreitz
[py-github]: http://github.com/dustin/py-github
[python-github2]: http://github.com/ask/python-github2
[gistapi]: http://github.com/kennethreitz/gistapi.py

### Ruby ###

#### API Version 1 ####

The [github-control][github-control] library is currently doing work
using the v1 API. The aim is to build a library which others can build
on top of.

It currently has features which need to be enabled on the v2 API as
they were in pre-release when developed.

The [github-party][gh-party] library is also using the v1 API.

[github-control]: http://github.com/halorgium/github-control
[gh-party]: http://github.com/technicalpickles/github-party

#### API Version 2 ####

The [octopi][octopi] library is one of the first emerging for the
GitHub API v2. There's also [octopussy][op].

[octopi]: http://github.com/fcoury/octopi/
[op]: http://github.com/pengwynn/octopussy

### Objective-C ###
[Clint Shryock's fork of CocoaREST][CocoaREST] extended the base CocoaREST library, a set of Cocoa classes to interact with RESTful services, to support Github's v1 API
[CocoaREST]: http://github.com/ctshryock/CocoaREST
