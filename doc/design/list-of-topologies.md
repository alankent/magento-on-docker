# List of Docker Container Topologies

The docker images also need to be assembled into deployment topologies. Some
images will be used multiple times (e.g. multiple web server images in one
tolopolgy for horizontal scaling). Some topologies will be the same with one
image replaced (e.g. using Nginx instead of Varnish for cache).
The list of topologies is to document topologies that should be supported.

* Super Simple - MySQL + Apache web server
* Scaled web server - MySQL + 3 Apache web servers
* Database scaled - MySQL master + MySQL read-only replica + 10 Apache web servers
