Bien renseigner le fichier inventaire>host adresse ip et clé ssh ou identifiants de connexion à la machine

Mettre à jour les noms et mots de passe souhaité dans le fichier de variable roles>Zabbix>vars>mains.yml

Renseigner l'adresse ip du Zabbix serveur dans le fichier >roles>zabbixt>asks>conf_ssl.yml à la ligne 65 ServerName et 66 Redirect permanent.

Lancer la commande: ansible-playbook -i invetaire/hosts principal.yml
