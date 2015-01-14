:title: Blogging via XMPP
:author: Sergey Dobrov
:description: Amazing way of federated blogging.
:keywords: XMPP, PubSub, blogging, web, internet, network, communications, social networking
:css: assets/main.css

Blogging via XMPP
=================

Amazing modern way of federated blogging
----------------------------------------

----

Internet used to be
===================
* consisting of number disjointed websites
* fault tolerant
* indexed by several search engines which were competiting by pulling info periodically from each site waiting for updates
* each publisher owned their information

----

:data-y: r800

Internet now
============
* mostly consists of big Internet services which control big part of World's information
* information is being posted several times to each of those to cover bigger audience
* users are limited with those services' policies
* the services themselves are being manipulated by governments

----

:data-x: r1400

So?
===

* equal access to information is not guaranteed
* users have to have accounts on each service to be able to use them
* the sites purposely make it impossible to check news without visiting sites
* have to share information that we probably don't want to
* actually don't own our info!
* WEIRD?!

----

Do we have a superhero?!
========================

----

:data-z: 900

YES!
====

----

:data-rotate: 30
:data-z: 1800


XMPP & PubSub/PEP
=================


* XMPP is well-known stable, many-times-implemented federated network
* which puts **security** into the main corner
* and is highly accessible from any perspective
* PubSub is a well-known design pattern which makes it not necessary to poll for changes
* *C-C-C-COMBO!*

----

:data-rotate: 60

Blogs
=====


* use PEP which turns each XMPP user into a PubSub service to store user posts
* other users can subscribe to that service to receive updates
* you also can ask the service to show you the posts
* you have wide abilities to control permissions and even allow others to post to your blog

----

:data-rotate: 90


Comments
========

* blogs are not interested without feedback from readers
* need to store comments
* can use generic PubSub node for that aim, linking each post to it's own thread
* thanks to XMPP's federation you don't need to register on all the blog services anymore, just use your JID to identify!

----

:data-rotate: 120

Aggregation
===========

* sounds good but what about search, stats? how can I know who is the biggest blogger in the world?
* don't try to resemble centralized web approaches!
* aggregators are the services that are subscribed to everyone

  * and receive updates *realtime*
  * and can provide extra feeds in the same format by specific criterias
  * and there can be *unlimited* number of such aggregators
  * diversity!

----

Federation? Too old.
=====================

Give us decentralization!
-------------------------

* look at this as the protocol, not the implementation
* the same clients will be able to work on every provider which uses the protocol
* underlaying protocol can be completely decentralized!

----

but this is the far far future.
================================

----

:data-z: 900

Which can become true only if you help!
=========================================

WE NEED HELP!
---------------

----

:data-z: 0

What can you do?
==================

* read XEP-277
* help with new XEPs

  * XEP-315: Recipient Server Filtration
  * Privileged Entity
  * Namespace Delegation
* help to solve current PubSub spec problems

----

:data-z: -900

Follow these on standards@ ML!
================================

And give us your opinion!
--------------------------

----

XEP-0277: Microblogging over PEP
===================================

* the main one
* defines a way of putting blog in your PEP
* rocks the world!

----

XEP-0351: Recipient Server-side Filtration
============================================

* with current scheme of entity capabilities negotiating:

  * one-way presence subscription doesn't work
* solution?

  * send all the events to receiving server and let it decide!
* backwards compatible
* implementations **WANTED**.

----

Privileged Entity
===================

TODO

----

Namespace Delegation
======================

TODO

----

Current PubSub problems
=========================

* http://wiki.xmpp.org/web/PubSubIssues
* Bloated XEP-0060
* Small incosistencies in XEP-0060
* What else?

----

I want to try!
================

Contacts and links here

