# Overview

Travis configuration is stored in a file called `.travis.yml`.

# Sections in the .travis.yml File

- `language:`: which lanugage to use
- `rvm` or similar: list defining which versions(s) of the language to use when running tests.

# Understanding

## Understanding the `TRAVIS_TAG`

1. create a "Tag" in the Github User Interface: should return `TAG=tag_from_github`
2. push commit to master `TAG=""`
3. push branch in github `TAG=""`

# Reference

https://docs.travis-ci.com/user/getting-started/
