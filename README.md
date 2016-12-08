# Power System Tests - CITE Architecture

An exeriment in implementing data from the [Power Systems Test Case Archive](https://www2.ee.washington.edu/research/pstca/) in the [CITE Architecture](http://cite-architecture.github.io), originally developed for the [Homer Multitext](http://www.homermultitext.org).

Collections are defined in `collections.xml`. Data resides in `/textfiles`. Those are processed using the [CITE Archive Manager](https://github.com/cite-architecture/cite-archive-manager) utility, developed by Neel Smith and Christopher Blackwell. The resulting RDF graph is in `/ttl`.

> n.b. The files `/textfiles/nodes.csv` and `/textfiles/edges.csv` are for future work implementing a CITE Canonical Graph Services Protocol. They are not currently incorporated into the RDF output.
