# List of Docker Images

This page contains a list of Docker images that are useful building blocks for
a Magento based solution.

* Database
  * MySQL - a well rounded MySQL configuration with good settings for Magento.
  * Maria DB?
  * others?

* Redis Server
  * Single node Redis server
  * Cluster based Redis configuration?

* Application Server
  * Apache web server with Magento code base in it
  * Nginx web server with Magento code base in it

* Shared media directory storage
  * If a cluster, the media directory needs to be shared across web server nodes.

* HTTP Accelerators
  * Varnish as cache 
  * Nginx as cache

TODO:
* Give each configuration a more precise name.
* Define input/output ports for each image.
* Define parameters for each image. For example, database password, or host memory allocation to compute buffer sizes appropriately.
* Work out if we need to change configurations per Magento version.
* Work out how to get the per customer Magento code base merged into the web server instances.
