# Docker Stack - NGINX, PHP 7.2 und MySQL 5.7

Mit diesem Repository kann ein Docker Stack mit NGINX, PHP 7.2 und MySQL 5.7 installiert werden.

### Installation:

1. PHP-Image mit den Erweiterungen `mysqli` und `PDO` erstellen:  
   `docker build -t php7.2-mysql .`
2. Stack erstellen:  
   `docker stack deploy -c docker-compose.yml example`
