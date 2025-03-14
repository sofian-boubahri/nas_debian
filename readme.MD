Création de deux users :
- Un administrateur 
- Un édutiant

adduser admin
add étudiant

Création de deux groups :

groupadd Administrateur
groupadd LaPlateforme

pour rajouter un user dans un groupe :

usermod -aG Administrateur admin
usermod -aG LaPlateforme Etudiant

Pour voir en détail :
id admin
uid=1001(admin) gid=1001(admin) groupes=1001(admin),1003(Administrateur)

Installation de FTP :
apt install proftpd -y