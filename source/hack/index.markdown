---
layout: page
title: "Hacking Fedora 4"
#date: 2013-01-21 23:09
comments: true
sharing: true
footer: true
---

> We can rebuild it. We have the technology. Better...stronger...faster.

Where is Fedora 4 today?
------------------------

1. Rapid prototypes of RESTful services

	a. [fcrepo 3.x “legacy” API](https://github.com/futures/fcrepo4/tree/master/fcrepo-legacy-api)
	
	b. CDL Storage Services API (i.e. Merritt)
	
	c. [An “experimental” pluggable Dublin Core derivation service](https://github.com/futures/fcrepo4/tree/master/fcrepo-dc)
	
	d. Content-negotiation
	
2. A commitment to asynchronous infrastructure

	a. Message queues to index content into external services (e.g.
[4store](https://github.com/futures/ff-indexer-fourstore), 
[Solr](https://github.com/futures/ff-jms-solr-indexing), etc)

	b. Asynchronous storage (e.g. [Amazon Glacier](https://github.com/futures/fcrepo4/tree/glacier))
	
	c. Consuming API requests via message queues
	
3. 	Support for Ruby, Python & Scala

	a. [JRuby](https://github.com/futures/fcrepo4/tree/jruby-sequencer-example) and Scala examples for processing object events and manipulating content
	
4. Modern approaches to scaling

	a. replicating and distributing digital objects across multiple nodes for throughput and high-availability
	

Where is Fedora 4 going? 
------------------------

We very much believe that “The coolest thing to do with your data will be thought of by someone else”, and we know you've got ideas you couldn't realize on Fedora 3.

What do you want your repository backend to do? Can you hack it into the Fedora 4 prototype by Thursday? 

The best code submission for indexers, web APIs, message listeners or improvements to the prototype will win a $500 cash prize, and the second place entry will win $250. Pull requests welcome!

For more information, visit us at [Fedora House]({{ root_url }}/programme) on Monday and Tuesday nights!