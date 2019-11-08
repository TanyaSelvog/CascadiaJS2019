# CascadiaJS - November 7th & 8th


## (Re)building a Faster, Better Slack - [Samantha Siow](https://github.com/samanthasiow)

> A new version of Slack is rolling out for our desktop customers, built from the ground up to be faster, more efficient, and easier to work on. In this talk, I’ll focus on our move from an eager data model to a lazily loaded and incomplete data model, and how that made for a speedier Slack experience.

Modern Architecture - Slack
* All UI components built in React
* Single process for multiple workspaces
* Lazily-loaded & incomplete data model


Modern app loads 33% faster


How they improved Slack:

* Load less code upfront
  * Used service worker to cache assets
  * Client-side rendering
* Declutter your boot data
* Prioritize initial API calls


***
# Accessibility is a Hydra - EJ Mason




















<link rel="stylesheet" type="text/css" media="all" href="main.css" />




