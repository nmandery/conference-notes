PySpark workshop
================

Shoaib Burq http://www.nomad-labs.com/

https://spark.apache.org/ Apache Spark™ is a fast and general engine for large-scale data processing. 

Jupyter notebook and slides: https://github.com/sabman/PySparkGeoAnalysis

- Provides the same API when running on one node hundreds of nodes
- Fault tolerant, takes care of rescheduling workloads should nodes fail
- Dependencies of computationd distributable in the form of docker containers. example: numpy C-extensions
- can use apache mesos as a scheduler
- not bound to a specific programming language: processing may be done in Java, Scala, Python, R

Geo-software packages (see slides for more) - may be language specific:

- spatialspark - JTS based
- geospark
- http://geotrellis.io/ - GeoTrellis is a geographic data processing engine for high performance applications. ... Currently GeoTrellis uses Akka clustering to distribute data across a cluster; in the next version of GeoTrellis, we will be running on the Spark system.
