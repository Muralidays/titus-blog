My Addonics Storage Tower Just Works.  Wow.
###########################################

:author: C\. Titus Brown
:tags: disks
:date: 2010-02-28
:slug: addonics-storage-tower
:category: misc


Over New Years I ordered 2 Dell PowerEdge T300 servers with 24 gb of RAM
for $1500 each.  I had no interest in upgrading with Dell's overly expensive
hard drives, so I ordered them both with the minimum of 2x160gb drives, leaving
two slots bare.

I then went to newegg and ordered 4x1.5 tb hard drives, and a week or two
later got an additional 5x2 tb hard drives.

This left with me with too many hard drives for the slots, so into the
bargain I added an Addonics MST5X1PM Mini Storage tower, a standalone
box capable of holding four hard drives and connecting to a host via an eSATA
5x1 port multiplier.  I also had to get an Addonics ADS3GX4R5-E PCI card and a
3 ft eSATA cable from Newegg (OK3EAR) -- tip, get the 6 foot cable.

I then stuffed the four 160gb hard drives that Dell shipped in their
servers into it, hooked it up to one of my Debian-installed T300 servers, and
voila!  Four extra hard drives!  JBOD FTW!

(I'm not used to stuff like this Just Working on Linux, and so far I really
like the Addonics tower, so I thought I'd post about both.)

The PCI card has 4 open ports, too, so I could in theory add three more storage
towers.  But then the I/O would suck even more.

Pointers to equally good or better JBOD SATA 3.5" enclosure options
are very welcome.

--titus

p.s. On the other hand, I have a failure rate of over 50% on the hard drives
from newegg.  WTF?
