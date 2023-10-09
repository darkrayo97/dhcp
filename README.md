# dhcp
he llegado hasta crear el failover con dos servidores y un cliente que cuando uno falle le de servicio dhcp el otro


en primer lugar estamos usando virtualbox la version 7.0 en una ubuntu 22.04
procedemos a usar una debian12 bookworm
quitamos el network manager para que las configuraciones que hagamos en los archivos se apliquen
el /etc/dhcp/dhcpd.conf debe quedar asi

![image](https://github.com/darkrayo97/dhcp/assets/114906901/44b99b32-b176-4585-9036-8f7eb7d10939)
![image](https://github.com/darkrayo97/dhcp/assets/114906901/577bb630-329d-4b2c-adac-c64a41b31776)

luego /etc/network/interfaces con dos tarjetas una con salida a internet y la otra para la red interna

![image](https://github.com/darkrayo97/dhcp/assets/114906901/08373f88-55f5-44a8-af38-d6d131ec18be)

con este archivo configurado tendremos puente para que la red interna salga a internet
![image](https://github.com/darkrayo97/dhcp/assets/114906901/66ad6218-2f97-4cc6-97a4-abdb5a63985f)
