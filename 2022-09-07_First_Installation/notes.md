# 2022-09-07 First Installation

## Report

* Successful first installation
* Guides:
  * [Matrix Synapse auf Ubuntu Server 20.04 LTS mit nginx, PostgreSQL und Let’s Encrypt by Jan](https://decatec.de/home-server/matrix-synapse-auf-ubuntu-server-20-04-lts-mit-nginx-postgresql-und-lets-encrypt/)
  * [Install Matrix Synapse by Stefan](https://www.natrius.eu/dokuwiki/doku.php?id=digital:server:matrixsynapse)
  * [Synapse Documentation](https://matrix-org.github.io/synapse/latest/)
* Software:
  * Ubuntu 22.04 
  * Postgres 14.5
  * Synapse 1.66
* Problems:
  * postgres corruption after using [PGTune](https://pgtune.leopard.in.ua/#/)
  * `@user:matrix.kgnet88.de` instead of `@user:kgnet88.de`
* To Investigate:
  * [Homeserver configuration](https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html)
  * [Delegation](https://matrix-org.github.io/synapse/latest/delegate.htm)
  * logs (server, db, services,...)
  * tooling: [lsof](https://en.wikipedia.org/wiki/Lsof), [ss](https://www.linux.com/topic/networking/introduction-ss-command/), [nmcli](https://opensource.com/article/20/7/nmcli)
* Links:
  * [SSL test](https://www.ssllabs.com/ssltest/)
  * [Federation tester](https://federationtester.matrix.org/)
