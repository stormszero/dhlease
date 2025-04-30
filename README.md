# dhlease
DHCP lease viewer.

# Hiatus
After a hiatus of almost 7 years I came back around to this as I ultimately forgot I put this here.
The version initially pushed here wasn't complete and had a few bugs along with it.

As per April 30th 2025 I pushed the version that I am currently using myself.
I'm not saying this is bug-free but the worst culprits should have been flushed.

# Requirements
Requires DHCP lease files in the format as specified and used by The Internet Consortium's DHCP server, dhcpd.

# Introduction
Displays your DHCP leases in a user-friendly manner.
dhlease allows you to search for client hostnames, ip address assignments, MAC addresses and supports filtering out old leases if there are > 1 lease present for a MAC address. It is also possible for you to only want to see active or expired leases.

This software was conceived as a small hobby project because I had need of it and while some somewhat similar utilities do exist, I decided to roll my own. If you find it useful, I'd be happy.

# Installation
Put the files in /usr/src/bin/dhlease and run make followed by make install.
Type man dhlease for usage and assistance.
(Yes, this step will be improved in the future).

# Limitations
Written on and for FreeBSD 11.2.
Will port if there's general interest.

# Special thanks
To my good friend, Soren Schmidt <sos@freebsd.org>.
