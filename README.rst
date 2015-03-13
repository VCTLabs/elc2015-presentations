Just a repo for ELC 2015 slides and stuff; see prebuilt directory for PDFs or other binary output.

Buildroot: Embedded Linux for Small Devices and Makefile Enthusiasts 
====================================================================

Abstract
--------

With the impressive success of the Yocto Project in persuading board vendors to
maintain BSP layers for the Yocto/OpenEmbedded build system, one might wonder
whether other embedded Linux build systems are destined to fade away. Such is
indeed the fate for certain build systems, such as the LTIB project (formerly
maintained by Freescale)... but not so for Buildroot! Buildroot lives on, with
as active a community as ever (5246 commits by 183 committers during 2014).
This presentation will focus on a couple of niches where Buildroot is
especially appealing: working with with low-cost MMU-less hardware, and
projects short on time with developers lacking in bitbake experience. The
latter point regarding a low learning curve will be illustrated with a full
example of customizing Buildroot via normal configuration, adding skeleton
files, and adding a new package.

Slides
------

.svg format, produced in Inkscape with JessyInk extension (http://wiki.inkscape.org/wiki/index.php/Tools#JessyInk)

prebuilt/buildroot_paths.svg - fonts converted to paths, for viewing not editing
buildroot/buildroot.svg - non-embedded fonts, for editing (need proper fonts installed)

Notes on .svg slides
--------------------

* view in a modern browser with javascript enabled
  * for navigation, use left/right arrows to do the fade-in effects, or up/down arrows to skip them#
* edit using Inkscape with JessyInk extension installed
  * JessyInk extension homepage http://code.google.com/p/jessyink/
  * probably already installed with recent Inkscape versions (look for /usr/share/inkscape/extensions/jessyInk.js)


Security Architecture in the IOT Age
====================================

Abstract
--------

Modern embedded Linux systems are now normally networked into a larger system,
taking advantage of Linux's strength in networking. Unfortunately, embedded
engineers all too often fail to spend enough time understanding and mitigating
security risks faced by networked devices; recent CVE summaries for popular
Linux home routers provide some glaring examples of insufficient attention to
security. Today it is critical that embedded engineers increase their attention
to security while developing products, rather than merely reacting to specific
exploits discovered after release. A good starting point is to learn and apply
security architecture best practices that have been documented over the years
by system architects/engineers using a modern "system of systems" approach and
the latest NIST standards, guidance, and risk management framework. 

Slides
------

prebuilt/security_assessment_slides.pdf
security_IoT/security_assessment_slides.odp
