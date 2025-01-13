# Gérer-les-interfaces-réseaux-en-CLI-Win/Lin  


## Linux  
**Adresse IP**  
`ip a` = `ip addr show` Vérification adresse IP  
`ip addr add 192.168.0.100 dev enp0s3` **ajoute** l'adresse ip indiquée sur la carte enp0s3.  
`ip addr del 192.168.0.100 dev enp0s3` **supprime** l'adresse ip indiquée sur la carte enp0s3.  


**Table de routage**  
``ip route`` : Vérifier les routes  
``route add default gw 192.168.10.1 eth0`` Ajoutera la route par défaut du réseau de l'interface eth0 à 192.168.1.1 dans la table de routage.  
``route del default`` supprimera la route par défaut de la table de routage.  



**Fichier de conf des interface Debian**  
``/etc/network/interfaces``  

Supprimer une adresse réseau en CLI :  
`ip addr del 192.168.1.5/24 dev eth0`  

## Windows  
