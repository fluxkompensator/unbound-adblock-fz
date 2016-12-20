# unbound-adblock-fz
Unbound domain blocklist in forward zone format

# INSTALL
Just clone the repository and copy the file domainoverrides.conf to your unbound configuration directory, example /etc/unbound

In your /etc/unbound/unbound.conf add the following line.
# Domain overrides
include: /var/unbound/domainoverrides.conf

Restart unbound and your done.
