# Ticket 1 - DNS
## Paquetes instalados
- bind9, bind9utils

## Ficheros modificados
- /etc/bind/named.conf.local
- /etc/bind/db.clinicanova.local
- /etc/bind/named.conf.options

## Comandos clave
- sudo named-checkconf
- sudo named-checkzone clinicanova.local /etc/bind/db.clinicanova.local
- sudo systemctl restart named

