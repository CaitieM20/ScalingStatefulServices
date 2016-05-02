# Scaling Stateful Services
The accompanying repository for The ScalingStatefulServices talk
* V1 StrangeLoop 2015: [Video](https://www.youtube.com/watch?v=H0i_bXKwujQ), [Slides](https://speakerdeck.com/caitiem20/building-scalable-stateful-services), [High Scalability Article](http://highscalability.com/blog/2015/10/12/making-the-case-for-building-scalable-stateful-services-in-t.html), [InfoQ Article](http://www.infoq.com/news/2015/11/scaling-stateful-services)
* V2 Craft Conf 2016: [Slides](https://speakerdeck.com/caitiem20/craftconf-2016-building-scalable-stateful-services#)

## Abstract
The Stateless Service design principle has become ubiquitous in the tech industry 
for creating horizontally scalable services.  However our applications do have state, 
we just have moved all of it to caches and databases.  Today as applications are 
becoming more data intensive and request latencies are expected to be incredibly 
low, we’d like the benefits of stateful services, like data locality and sticky 
consistency.  In this talk I will address the benefits of stateful services,
how to build them so that they scale, and discuss  distributed and scalable
services in the real world that implement these techniques successfully.

## Resources
* [Strong Consistency Models](https://aphyr.com/posts/313-strong-consistency-models) by Kyle Kingsbury
* [Consistency Diagram](http://www.vldb.org/pvldb/vol7/p181-bailis.pdf) by Peter Bailis et al
* [Eventual Consistency Revisited](http://www.allthingsdistributed.com/2008/12/eventually_consistent.html) by Werner Vogels
* [Gossip Protocol](https://en.wikipedia.org/wiki/Gossip_protocol)
* [Epidemeic Algorithms for Replicated Database Maintenance](https://pdfs.semanticscholar.org/49ed/15db181c74c7067ec01800fb5392411c868c.pdf)
* [Consistent hashing and random trees: Distributed caching protocols for relieving hot spots on the World Wide Web](https://www.akamai.com/es/es/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf)
* [Dynamo: Amazon's Highly Available Key Value Store](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) uses Consistent Hashing
* [Distributed Hash Table](https://en.wikipedia.org/wiki/Distributed_hash_table)
* [Scuba: Diving into Data at Facebook](https://research.facebook.com/publications/scuba-diving-into-data-at-facebook/)
* [Twitter Nuthatch Service](https://blog.twitter.com/2016/observability-at-twitter-technical-overview-part-i) from Observability at Twitter: Technical Overview, part 1
* [Uber Ringpop](http://uber.github.io/ringpop/)
* [Uber's Ringpop and the Fight for Flap Dampening](http://www.infoq.com/presentations/halo-4-orleans)
* [SWIM:Scalable Weakly-consistnet Infection-style Process Group Membership Protocol](https://www.cs.cornell.edu/~asdas/research/dsn02-swim.pdf)
* [Microsoft Orleans](http://dotnet.github.io/orleans/)
* [Orleans: Distributed Virtual Actors for Programmability and Scalability](http://research.microsoft.com/apps/pubs/default.aspx?id=210931)
* [Builiding the Halo 4 Services with Orleans](http://www.infoq.com/presentations/halo-4-orleans)
* [Artificial Intelligence A Universal Modular ACTOR Formalism for Artificial Intelligence](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.77.7898)
* [Fast Database Restarts at Facebook](https://research.facebook.com/publications/fast-database-restarts-at-facebook/)

## Bio
Caitie McCaffrey is a Backend Brat and Distributed Systems Diva at Twitter.  Prior to that she spent the majority of her career building large scale services and systems that power the entertainment industry at 343 Industries, Microsoft Game Studios, and HBO.  Caitie has a degree in Computer Science from Cornell University, and has worked on several video games including Gears of War 2, Gears of War 3, Halo 4, and Halo 5 She maintains a blog at  CaitieM.com  and frequently discusses technology on Twitter @Caitie
