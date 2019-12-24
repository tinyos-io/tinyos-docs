.. _tinyos_2.1_tutorial:

TinyOS 2.1 tutorial
===================

| IPSN 2009
| April 16, 2009
| San Francisco, CA

--------------

TinyOS is an operating system widely used in sensor network research in
academia and industry. In this tutorial, we will explain the details of
TinyOS 2.1 architecture and learn how to start using TinyOS 2.1 for
research and sensor network application development. This tutorial
presents:

#. An overview of TinyOS 2.1 component-based architecture and design
   rationale
#. The details of nesC, the C-dialect used to write programs in TinyOS
#. Mechanisms to trap memory access errors (null pointer dereferences,
   array bound violations, etc.) using Safe TinyOS
#. An overview of TinyOS threads which enables seamless interleaving of
   long running background computations with time critical event-based
   services
#. A survey of the TinyOS network stack. The tutorial will include
   hands-on session during which the participants will learn about
   `TOSSIM <TOSSIM>`__, the TinyOS simulator, and run TinyOS programs.

Media
-----

| **Slides**: `http://enl.usc.edu/talks/cache/tinyos-ipsn2009.pdf
  PDF <http://enl.usc.edu/talks/cache/tinyos-ipsn2009.pdf_PDF>`__
  `http://enl.usc.edu/talks/cache/tinyos-ipsn2009.ppt
  PPT <http://enl.usc.edu/talks/cache/tinyos-ipsn2009.ppt_PPT>`__
  `http://www.slideshare.net/gnawali/tinyos-21-tutorial-at-ipsn-2009
  Slideshare <http://www.slideshare.net/gnawali/tinyos-21-tutorial-at-ipsn-2009_Slideshare>`__
| **Streaming Video**: `hosted on
  Vimeo <http://vimeo.com/channels/tinyos>`__

Agenda
------

::

   08:33 - Introductions and overview of the tutorial - Omprakash Gnawali (USC)
   08:35 - Basics - Philip Levis (Stanford) and David Gay (Intel Research, Berkeley)
   09:30 - TOSSIM - Răzvan Musăloiu-E. (JHU)
   09:45 - Safe TinyOS - John Regehr (Utah)
   10:00 - Threads - Kevin Klues (UCB)
   10:15 - Break/discussions
   10:20 - Protocols - Omprakash Gnawali (USC)
   10:40 - Upcoming technologies (ZigBee/15.4/IP) - Stephen Dawson-Haggerty (UCB)
   10:50 - Hands-on - Răzvan Musăloiu-E. (JHU), Omprakash Gnawali (USC)
   11:30 - End

The complete code for the two applications from hands-on is
`here <http://hinrg.cs.jhu.edu/~razvanm/ipsn09/ipsn09.tar.gz>`__.

`Category:Tutorials <Category:Tutorials>`__
