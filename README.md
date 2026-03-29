Scanner de ports en C
Scanner de ports TCP basique écrit en C. Permet de vérifier si un port est ouvert ou fermé sur une machine distante.
Compilation
bashgcc scanner.c -o scanner
Utilisation
bash./scanner <ip> <port>
Exemples
bash./scanner 192.168.1.1 80
./scanner 127.0.0.1 22
Résultat
Port 80 Ouvert
Port 22 fermer
Comment ça marche
Le programme tente une connexion TCP sur le port ciblé via une socket. Si la connexion réussit, le port est ouvert. Sinon, il est fermé.
