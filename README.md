This is a [Docker](http://docker.com) [Compose](https://docs.docker.com/compose/) script for bringing up a [Wordpress](http://wordpress.org) site backed with [MariaDB](https://mariadb.org/). To use this, make sure you've [installed Docker)](https://www.docker.com/products/docker), [installed Compose](https://docs.docker.com/compose/install/) and then do the following:

1) Clone this repo with '''git clone https://github.com/jbfink/c4lnys-wordpress'''

2) Run '''docker-compose up''' from the cloned directory.

3) Wait a bit for the two Docker containers to come up.

4) Visit [https://localhost:8080](https://localhost:8080) in a web browser and set up Wordpress.

Note that you can '''ctrl-c''' in the terminal you ran '''docker-compuse up''' to stop. Running '''docker-compose up''' again should pick up where you left off, but if you want to start again from scratch do '''docker-compose rm''' to remove the old containers and '''docker-compose up''' to start again from scratch.





