---
title: BlackBerry Open Source
layout: default
---

# Announcing the Native Open Source Components Initiative

(Oct 18th, 2011) Today [Research in Motion](http://rim.com) announced its Native Open Source Components Initiative at DevCon 2011 America.
As part of this initiative, RIM is contributing initial ports of commonly used Open Source Libraries and Games to
the QNX-based BlackBerry&copy; Tablet OS.  RIM will collaborate with the existing open source communities to
incorporate these these changes into the upstream repositories.

RIM is also releasing under an Open Source license some new convenience libraries and frameworks and some samples that show how
to use all this components to create applications for the BlackBerry&copy; PlayBook.

The initial list of components covered in the initiative include:

**Media Components**

The following compoments are related to multi-media processing:

* ALUT
* OpenAL
* SDL

**Gaming Components**

The following components are Physics Engines, Game Engines or Games:
* Box2D
* Bullet
* Cocos2D-X
* GamePlay
* Wesnoth
* OpenTTD
* DosBox

**General Libraries**

These are general purpose libraries, languages, or frameworks:
* Lua
* PCRE
* Erlang-OTP
* SpiderMoneky
* TouchControlOverlay
* Qt
* Boost

----

## Research In Motion at GitHub

Welcome to the home for [RIM](http://rim.com) projects at GitHub.

The first repository in this [organization](https://github.com/blog/674-introducing-organizations) was [WebWorks](https://github.com/blackberry/WebWorks/commit/1a7373cb155756fb6be7ccce893d6d790ec10abf), created during [DevCon 2010](http://devblog.blackberry.com/2010/09/blackberry-webworks-and-the-open-source-community/).  Since then we have added six more repositories covering runtimes, tools, documentation, and code samples and we expect more projects to follow.
For the latest, and an archive of older, news, check [here](news); also see the official [BlackBerry DevBlog](http://devblog.blackberry.com/).

Projects fall into one of the following categories:

**RIM-led Projects** - In these projects:

* The overal direction of the project is under RIM leadership,
* RIM assigns a _technical lead_ to represent it in the project,
* RIM assigns several of its engineers to contribute to the project.
* We welcome and encourage participation from non-RIM employees at any level.
* The majority (all so far) of the projects are licensed under ASL2 ([wikipedia](http://en.wikipedia.org/wiki/Apache_Software_License), [Apache](http://www.apache.org/licenses/)).
* We strive to operate transparently

Participation details at [How to Contribute](howToContribute.html).  Note that contributions from non-RIM employees require an agreement like at ASF: [CCLA](http://www.blackberry.com/legal/pdfs/webworks/Research_In_Motion_Limited_CCLA_021811_cl.pdf), [ICLA](http://www.blackberry.com/legal/pdfs/webworks/Research_In_Motion_Limited_ICLA_021811_cl.pdf).


**RIM-Sponsored Projects** - These are non-RIM-led Open Source projects in which RIM participates actively.  In general RIM will participate in the relevant open source community, but some projects may also be listed here for several reasons.  More information on this category shortly.

## A Tour through a Project

Projects are encouraged to maintain information in these pages.  Using WebWorks as an example:

* Top Project [description page](webworks/index.html).
* The master [Git](http://en.wikipedia.org/wiki/Git_%28software%29) repository at GitHub at [blackberry/webworks](http://github.com/blackberry/WebWorks), including:
* The usual GitHub features, like [pulls](https://github.com/blackberry/WebWorks/pulls), [commit history](https://github.com/blackberry/WebWorks/commits/master), [network graph](https://github.com/blackberry/WebWorks/network), etc.
* The list of [Contributors to WebWorks](https://github.com/blackberry/WebWorks/contributors),
* A Project [Roadmap](https://github.com/blackberry/WebWorks/issues/milestones),
* Defect tracking via [GitHub Issues](https://github.com/blackberry/WebWorks/issues)

## List of Repositories

### WebWorks

* [WebWorks](http://github.com/blackberry/WebWorks) - The runtime for the BlackBerry OS Platform.
* [WebWorks-TabletOS](http://github.com/blackberry/WebWorks-TabletOS) - The runtime for the QNX-based BlackBerry Tablet OS Platform.
* [WebWorks-API-Docs](https://github.com/blackberry/WebWorks-API-Docs) - The official API documentation.
* [WebWorks-Samples](https://github.com/blackberry/WebWorks-Samples) - RIM and Community-provided samples for WebWorks.
* [WebWorks-Community-APIs](http://github.com/blackberry/WebWorks-Community-APIs) - New APIs, contributed by RIM and the Community, that could be considered for move to the official APIs.

### Ripple Emulator

* [Ripple-Framework](https://github.com/blackberry/Ripple-Framework) - Basic Framework for the Ripple Emulator
* [Ripple-UI](https://github.com/blackberry/Ripple-UI) - Presentation elements for Ripple.

### Alice

* [Alice.js](https://github.com/blackberry/Alice) - (A Lightweight Independent CSS Engine) is a micro JavaScript library for generating rich visual effects in modern browsers.

### WebKit

* [WebKit-SmartPhone](https://github.com/blackberry/WebKit-Smartphone) - RIM contributions to WebKit for BlackBerry Smartphones.

WebWorks, Ripple, and Alice are RIM-led projects.  These repositories are the "master" repositories.
WebKit is maintained by the [WebKit.org](http://webkit.org) community.

