![Test Logo](images/connective_logo_02_03_2020.png)

***(Logo above is not final, many alternative versions will be placed here.)***

![Test Banner](images/connective_banner_02_07_2020.png)

***(Like the logo, the banner above is not final, many alternative versions will be placed here.)***

# Welcome to Connective C++!

We are dedicated to connecting the world through a high level, modern C++ networking API and related utilities.

## Repositories

[chops-net-ip](https://connectivecpp.github.io/chops-net-ip), a high level, general purpose C++ 20 networking API that simplifies creating TCP and UDP network connections.

[utility-rack](https://connectivecpp.github.io/utility-rack), a small and tasty collection of utilities, although most of them are no longer needed in C++ 20.

[wait-queue](https://connectivecpp.github.io/wait-queue), a header-only C++ 20 MPMC thread-safe queue.

[binary-serialize](https://connectivecpp.github.io/binary-serialize), a header-only C++ 20 library for binary serialization, using `std::format` style syntax (work in progress).

[periodic-timer](https://connectivecpp.github.io/periodic-timer), a header-only C++ 20 asynchronous periodic timer, using Asio facilities.

[shared-buffer](https://connectivecpp.github.io/shared-buffer), header-only C++ 20 reference counted byte buffer classes.

## About

Connective C++ is an open source project providing tasty libraries and code for networking applications written in the C++ language.

#### Why?

There is a need for easy-to-use, efficient, modern, asynchronous C++ libraries for connecting processes and devices.

#### Really?

Yes.

There is specially a need for libraries with nice abstractions for common networking needs.

Historically the useful and tasty abstractions have not been present in C++, or the abstractions did not provide scalability or flexibility. Connective C++ fills that need.

#### Why C++? 

For applications running on servers or workstations, there are many choices in languages and frameworks and environments. However, for smaller devices or mobile environments, efficiency and determinism and small environment footprints often rule out languages other than C or C++. In particular, an interpreted environment (e.g. with Python) or a virtual machine (e.g. JVM for Java) is often not possible, or is too resource intensive.

## People

Principal Author is [Cliff Green](https://github.com/cliffg-softwarelibre).

Principal Co-author is [Thurman Gillespy](https://tgill880.github.io).

Team Members include [Roxanne Agerone](https://github.com/oxenran), [Nathan Deutsch](https://github.com/n-deutsch), and [Stephen Rogers](https://github.com/srcodes12).

Former Team Members include [Casey Ghilardi](https://github.com/Crghilardi), and [Bryan Concari](https://github.com/irql).

Logo and banner designed by Ariel Peretz.

Contributions have been made by Matthew Earulic, Daniel Muldrew, Bob Higgins, and Matthew Briggs.

## Who is Using Connective C++ Software?

Chops Net IP was in use at Sound Life Sciences, a Seattle startup creating medical software and devices using high frequency sound to monitor respiration rate. This allows detection of opiod overdose, early signs of infection, and other breathing related disorders.

## C++ Language Requirements and Alternatives

C++ 20 is the primary baseline for the Connective C++ projects.

A significant number of C++ 11 features are in the APIs and implementations. A C++ 03 version will not be provided in any of the Connective C++ repositories. 

There are numerous C++ 14 and C++ 17 features in use and some C++ 20 features, although many of them could be replaced with Boost (or similar) utilities or rewritten to use only C++ 11 (or 14 or 17) capabilities. For users that don't want to use the latest C++ compilers or compile with C++ 20 flags, Martin Moene provides an excellent set of header-only libraries that implement many useful C++ library features (see [References](doc/references.md)).

While the main production branch will always be developed and tested with C++ 20 features (and relatively current compilers), alternative branches and forks for older compiler versions may be implemented. Collaboration (through forking, change requests, etc) is welcome to achieve older compiler conformance.

## References

Connective C++ would not be possible without articles, libraries, and code examples from the C++ community. The [References](doc/references.md) page lists the primary influences and library providers on this project.

## Team Bios

**Cliff Green** (cliffg at connectivecpp dot com) is a software engineer and has worked for many years writing infrastructure libraries and applications for use in networked and distributed systems, typically where high reliability or uptime is required. The domains where he has worked include wireless networks (in particular cellular 9-1-1), location technology, and large scale embedded and simulation systems in the military aerospace industry. He has volunteered many years at [CppCon](https://cppcon.org/) (when it was in Bellevue, Washington) and presented at BoostCon (before it was renamed to [C++ Now](http://cppnow.org/)).

Cliff previously lived in the Seattle area and you may know him from other interests including volleyball, hiking, railroading (both the model variety and the real life big ones), music, or even parent support activities (if you are having major difficulties with your teen check out the [Changes Parent Support Network](http://cpsn.org)). He now lives in Placitas, New Mexico (15 miles north of Albuquerque).

**Thurman Gillespy** ([GitHub site](https://tgill880.github.io/), thurmang at connectivecpp dot com) is a software engineer although his first career was in diagnostic radiology, with stints at the University of Florida (1985 - 1990), University of Washington (1990 - 2008) and private practice in Seattle (2008 - 2015). In the 1990's, Thurman wrote Dr Razz, the first application that could display and manipulate radiology images on a Macintosh computer. In 2015 Thurman left medicine and went back to school to transform a life long hobby of programming into a second career as a software developer.

**Roxanne Agerone** ([GitHub site](https://github.com/RAgerone), roxanne at connectivecpp dot com) is a software engineer working in the Seattle area and loves classic cars (among other interests). She created the [Seattle C++ Meetup](https://www.meetup.com/Seattle-C-Meetup).

**Nathan Deutsch** ([personal website](http://www.nathandeutsch.com), nathand at connectivecpp dot com) is a software engineer working in Bellevue, Washington. He likes to study and play jazz guitar and go camping. He also claims to be the best pool player in the state, accepting all challengers (if you think you're good enough, contact him!).

**Casey Ghilardi** (caseyg at connectivecpp dot com) is a software engineer in the Seattle area, active in various open source projects. 

**Bryan Concari** (irql at connectivecpp dot com) is a devops engineer in the Seattle area and likes to play guitar and bass. He is a computer enthusiast through and through, with a particular interest in distributed software and systems internals.

**Ariel Peretz** (arielinseattle29 at gmail dot com) is an avid hiker living in the Puget Sound area. He plays indoor soccer, likes drawing, the New York Yankees, Montreal and often says "friends don't let friends drink Starbucks coffee".
