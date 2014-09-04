AisArchive
===========

# Introduction #

AisArchive is a stand-alone Java application which can archive maritime data received via the
[Automatic Identification System](http://en.wikipedia.org/wiki/Automatic_Identification_System) (AIS) in a 
Cassandra database cluster.

Using Cassandra over a traditional relational database enables excessive write performance, and the ability
to search and analyze vast amounts of AIS messages.

AisArchive can archive AIS messages read from either files or via TCP/IP network.
