# Modifier l'emplacement de la racine du serveur Apache

Une méthode simple est
d'ajouter un montage loop par une ligne dans le fichier /etc/fstab :

/home/USER/www	/opt/lampp/htdocs	none	bind	0	0
Désormais, toute référence à /opt/lampp/htdocs sera redirigée vers le répertoire voulu (à créer au besoin)

par Davis Maghulu Kabuyaya



ref: https://doc.ubuntu-fr.org/xampp#modifier_l_emplacement_de_la_racine_du_serveur_apache

## pour plus d'informations sur /etc/fstab
https://www.linuxtricks.fr/wiki/fstab-explications-sur-le-fichier-et-sa-structure
https://doc.ubuntu-fr.org/mount_fstab
