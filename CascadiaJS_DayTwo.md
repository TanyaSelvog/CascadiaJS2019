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
  * Small boot payload
  * Code splitting 
* Declutter your boot data
  * Embracing the unknown
* Prioritize initial API calls
  * Start API calls early


***
## Accessibility is a Hydra - EJ Mason


When Hercules fought the hydra, its heads would grow back no matter how many times he cut them off. Web accessibility professionals put repeated effort toward fighting accessibility barriers, and often feel like their work is never done. If we want to prevail against accessibility barriers, we have to understand our own hydra: we have to talk about ableism.

Avoid large blocks of text and use headings to separate text

Killing ableism
* Ableism exists in a systems of systems (@tatianaTMac)
* Follow more disabled persons on SM
* Be anti-ableist
















<link rel="stylesheet" type="text/css" media="all" href="main.css" />




