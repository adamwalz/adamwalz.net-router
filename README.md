# adamwalz.net Nginx Proxy

Reverse proxy to handle ssl termination and redirects for backend app servers.
Uses docker links which modify /etc/hosts to network between containers.

SSL certificates should be included through a data volume at /etc/nginx/certs
* SSL chained certificate `adamwalz.net.chained.crt`
* SSL private key `adamwalz.net.key`
