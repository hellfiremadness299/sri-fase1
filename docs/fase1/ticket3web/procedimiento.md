# Ticket 3 - Web
## Paquetes instalados
- apache2

## Ficheros modificados
- /etc/apache2/sites-available/intranet.clinicanova.local.conf
- /etc/apache2/sites-available/www.clinicanova.local.conf

## Comandos clave
- sudo a2ensite intranet.clinicanova.local.conf
- sudo a2ensite www.clinicanova.local.conf
- sudo apache2ctl configtest
- sudo systemctl reload apache2

