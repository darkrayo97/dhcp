# dhcp
he llegado hasta crear el failover con dos servidores y un cliente que cuando uno falle le de servicio dhcp el otro


en primer lugar estamos usando virtualbox la version 7.0 en una ubuntu 22.04
procedemos a usar una debian12 bookworm
quitamos el network manager para que las configuraciones que hagamos en los archivos se apliquen
el /etc/dhcp/dhcpd.conf debe quedar asi

![image](https://github.com/darkrayo97/dhcp/assets/114906901/44b99b32-b176-4585-9036-8f7eb7d10939)
![image](https://github.com/darkrayo97/dhcp/assets/114906901/577bb630-329d-4b2c-adac-c64a41b31776)
