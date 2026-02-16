# Perimeter
Before beginning these notes, I presume that you have already studied firewalls with me, and that you can use conventional terminology. If this is not the case, please bring this to my attention.

We place a _perimeter firewall_ on the external connection, under our own control. We will normally have options to:

- Allow controlled internet access from our site.
- Allow remote users to access the site via VPNs.
- Publish services to the Internet by means of a DMZ.
- Allow connectivity to other sites by site-to-site VPNs.

Long ago, there was an argument that if you had a private leased line, you did not need to encrypt traffic over it. That argument disappeared years ago. Regardless of who you're buying services from, we work on the basis of zero trust. Before we start then, we will make the presumption that any carrier service between our business sites is just a way of carrying traffic and regardless of the vendor, we will be encrypting our traffic.

To simplify our design then, the perimeter of each site will have a firewall with two WAN connections.