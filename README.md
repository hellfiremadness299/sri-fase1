# SRI Fase 1 - Servicios base

## Cómo verificar en 5 minutos
1. DNS: `dig srv.clinicanova.local @192.168.56.10`
2. DHCP: renovar IP en CN-MON-LAB con `sudo netplan apply`
3. Web: `curl -I http://intranet.clinicanova.local`
