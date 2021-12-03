# Overview

Travis configuration is stored in a file called `.travis.yml`.

# Understanding

## Understanding the `TRAVIS_TAG`

1. create a "Tag" in the Github User Interface: should return `TAG=$tag_from_github` To test, I ran 
2. push commit to main `TAG=""` To test, I ran `git commit` followed by `git push origin main`
3. push branch in github `TAG=""`. To test, I ran `git push origin new_branch`

## Understanding Deployments on Tag

Travis has a feature allowing conditional deployments on tags.

1. push commit to main and no deployment should occur.
2. create a tag and a deployment should occure.


# Reference

https://docs.travis-ci.com/user/getting-started/
