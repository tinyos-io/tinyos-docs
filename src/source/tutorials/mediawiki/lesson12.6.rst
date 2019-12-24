.. figure:: blip.png
   :alt:  frameless | right | upright=1

   frameless \| right \| upright=1

BLIP 2.0 is a reimplementation of IPv6 in TinyOS, and includes the
building blocks which other projects like `TinyRPL <TinyRPL>`__ and
`CoAP <CoAP>`__ have built on top of. blip-2.0 includes support for a
stack built on top of:

-  `draft-6lowpan-hc-06 <http://tools.ietf.org/html/draft-ietf-6lowpan-hc-06>`__
   for IPv6 header compression
-  `draft-roll-rpl-17 <http://tools.ietf.org/html/draft-ietf-roll-rpl-17>`__
   for IPv6 routing
-  RFC 1661-complient ppp daemon for communicating with external
   networks

   -  from Peter Bigot and the peoplepower osian stack
   -  merged in from the osian-squashed-ppp branch

-  dhcpv6 for address assignment
-  several other utilities for building networked applications

It represents a significant advance in many ways as it supports emerging
standards and has been shown to interoperate with the corresponding
Contiki implementations. Combined with an application protocol like the
one provided by `CoAP <CoAP>`__, TinyOS now contains the building blocks
for building applications using standard protocols except for the link
layer.

.. _getting_started:

Getting Started
===============

The first step towards running a network using blip-2.0 is to follow the
`Blip 2.0 Tutorial <Blip_2.0_Tutorial>`__ to compile and install sample
applications. Once you have done this, you'll be able to ping6 a network
of motes running TinyOS/blip.

.. _further_reading:

Further Reading
===============

-  `BLIP 2.0 Tutorial <BLIP_2.0_Tutorial>`__
-  `BLIP 2.0 Internals <BLIP_2.0_Internals>`__
-  `BLIP 2.0 Porting Guide <BLIP_2.0_Porting_Guide>`__
-  `TinyRPL <TinyRPL>`__
-  `CoAP <CoAP>`__

.. raw:: mediawiki

   {{Cc-by-sa-3.0}}
