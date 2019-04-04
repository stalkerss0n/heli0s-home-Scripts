# heli0s-home-Scripts

Configuration for my all in one media server. Any updates and fixes are welcome.

### Configuration
* Hetzner Cloud VPS
  * Debian Stretch 9.6
  * 4 vCPU - 8 vCPU
  * 16GB - 32GB RAM
  * 120GB NVMe SSD
  * 1 Gbit/s
  
### Google Drive (Media seperated by type)
* 14 TDs
* Service-Account-Setup

### HAProxy
* Proxying all traffic from:
  * *.heli0s.xyz
  * *.andromedae.space
* To:
  * localhost
  * server_1
  * server_2
  * server_3

### Media-Server
* Emby
* Plex

### Webserver
* NGINX
  * Mirror (public)
  * Data (private-protected)
* Caddy (?)
