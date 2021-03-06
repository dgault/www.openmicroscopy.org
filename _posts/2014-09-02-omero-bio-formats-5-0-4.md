---
layout: post
title: Release of OMERO & Bio-Formats 5.0.4
intro-blurb: The OME Consortium is pleased to announce the release of OMERO & Bio-Formats 5.0.4
---
Today we are launching 5.0.4, a bug-fixing release.

For OMERO this includes:

-  fixes for Java 8 issues - both the OMERO clients and OMERO.server should now be compatible with this Java update
-  a fix for uploading masks in OMERO.matlab

Bio-Formats improvements include:

-  multiple fixes for the .ND2 formats
-  Java 8 fixes
-  support for PicoQuant .bin files (thanks to Ian Munro)


Full details are available on the OMERO Github milestone[1] and the Bio-Formats Github milestone[2] pages.

The software is available from
[archived downloads](http://downloads.openmicroscopy.org/omero/5.0.4/)
and
[archived downloads](http://downloads.openmicroscopy.org/bio-formats/5.0.4/)

For information on upgrading your server, see the upgrade guide for system administrators - [http://www.openmicroscopy.org/site/support/omero5/sysadmins/server-upgrade.html](http://www.openmicroscopy.org/site/support/omero5/sysadmins/server-upgrade.html)

Note that you need to upgrade your OMERO.server to take advantage of the improved support for .ND2 in Bio-Formats.

For full details of the next major release, see the 5.1 milestone page- http://trac.openmicroscopy.org.uk/ome/milestone/5.1.0
We currently intend 5.0.4 to be the last update to the 5.0.x series. Our development focus is now on the OME 5.1 line and updating the OME Data Model for the next schema release, and while we will continue to support both 4.4.11 and 5.0.4 through early 2015, we will only perform critical bug fixes on the 5.0.x line and do not intend any fixes on the 4.4.x line.


[1] https://github.com/openmicroscopy/openmicroscopy/issues?q=milestone%3A5.0.4+is%3Aclosed

[2] https://github.com/openmicroscopy/bioformats/issues?q=milestone%3A5.0.4+is%3Aclosed
