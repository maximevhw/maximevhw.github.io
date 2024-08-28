---
layout: default
---

# Honeypot Project

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [git-url-extractor](https://github.com/maximevhw/git-url-extractor)
When pentesting fellow students honeypot project I noticed some git cloned their project repo directly into the web facing folder. Thus publishing the .git folder aswell.  

This python script automaticly checks a given list of domains for the precense of the .git folder.

Then the INDEX file gets extracted and a list of all files present gets extracted using [gin - a Git index file parser](https://github.com/sbp/gin).

Leaving us with alot of information.
