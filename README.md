Test de résolution DNS directe : Validation de la communication réseau et de la résolution correcte du nom d'hôte srv-dns.wilders.lan vers l'adresse IP 172.16.10.5 depuis la machine cliente.

Test de résolution de l'alias (CNAME) : Vérification depuis le client que l'alias ns1.wilders.lan redirige bien vers le serveur principal et répond correctement sur son adresse IP.

Requête DNS avancée via nslookup : Confirmation que c'est bien notre serveur DNS local qui est interrogé et qu'il retourne avec succès l'enregistrement associé à l'alias ns1.

Configuration du serveur DNS (Zone de recherche directe) : Affichage de la zone confirmant la bonne création de l'enregistrement de type A (hôte) et de l'enregistrement CNAME (alias).

Configuration du serveur DNS (Zone de recherche inversée) : Vérification de la présence de l'enregistrement de pointeur (PTR), garantissant le bon fonctionnement de la résolution inverse (de l'adresse IP vers le nom d'hôte).
