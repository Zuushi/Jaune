# Jaune
## Avec FileZilla
# Lien pour télécharger : https://filezilla-project.org/
- Fichier > Gestionnaire de sites...
- Cliquer sur "nouveau site"
- Choisir le protocole SFTP
- Saisir ses identifiants (laisser le port vide)

## Déposer les fichiers
- Remonter l'arborescence d'un dossier puis naviguer dans /home/nodejs-app/jaune
- Déposer les nouveaux fichiers

# Le serveur ne répond plus
## Avec Putty
# Lien pour télécharger : https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
- Ouvrir une session avec ses identifiants
- naviguer dans /home/nodejs-app/jaune
- Lancer ces commandes : 
```
screen // une bulle d'information s'ouvre, appuez sur la touche entrée pour passer
node init-server.js // le serveur se lance
ctrl + a + p // ferme la fenêtre actuelle sans détruire le processus
```
- Le serveur se lance à l'adresse du server:port
