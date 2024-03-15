# Exegol Ressources


## Introduction
Exegol [Exegol GitHub Repository](https://github.com/ThePorgs/Exegol) est un outil puissant qui facilite le déploiement et la gestion de conteneurs. 

#### Ce dépôt est un simple regroupement de mes ressources pour Exegol, me permettant de lancer des conteneurs personnalisés selon mon flux de travail.

## Fonctionnalités

- **Utilisation de tmux avec la souris :** Plus besoin de connaître une multitude de raccourcis clavier.
- **Division du terminal tmux :** Divisez le terminal tmux en quatre en utilisant simplement `Ctrl+b+'`.
- **Lancement d'un serveur web Python en upload :** Utilisez la commande `runwww 80`.
- **Activation directe du SSH sur votre machine :** Utilisez la commande `sshon`.
- **Réinitialisation de l'interface réseau :** Utilisez la commande `runeth`.
- **Affichage et copie de l'adresse IP TUN0 :** Utilisez la commande `tun0`.
- **Copie de la commande pour obtenir un shell dynamique sous Linux :** Utilisez la commande `pty`.
- **Copie de la commande pour passer en AZERTY (PowerShell) :** Utilisez la commande `getfr`.
- **Lancement d'un serveur FTP accessible en mode anonyme :** Utilisez la commande `runftp`.
- **Lancement d'un serveur WebDAV sur le port 80 :** Partage du dossier "runwebdav".
- **Copie de la commande pour activer les couleurs dans PowerShell :** Utilisez la commande `getcolor`.
- Quelques Binaires utiles (Potentiel doublons avec les ressources dans /op/ressources)
  
 Astuce :
 `tun0 && runwww 80` Permet de lancer un serveur web et d'avoir l'ip tun0 directement dans le pressepapier 
  
## Config Tmux :
- Configuration de la barre de statut : La largeur de la partie gauche de la barre de statut est définie à 150. Le contenu de la barre de statut est également défini pour afficher la date, l’adresse IP de ‘eth0’ et ‘tun0’, l’IP publique, le nombre de connexions établies, l’utilisation du CPU et de la RAM.
- Configuration de l’historique : La limite de l’historique est définie à 50000.
- Configuration de la souris : La souris est activée et une action est définie pour le bouton droit de la souris pour coller le contenu du presse-papiers.
- Configuration de la fenêtre : Un raccourci clavier est défini pour diviser la fenêtre en plusieurs panneaux.

## Installation /!\ il doit deja y avoir eu un lancement d'exegol genre : "start exegol teste" avant installation /!\
   ```bash
   git clone https://github.com/Frozenka/Exegol-Ressources.git
   cd Exegol-Ressources
   bash install.sh
   ```

## Contribuer
N'hésitez pas à contribuer en ouvrant des problèmes, en proposant des améliorations, ou en soumettant des demandes de fusion. Votre contribution est appréciée !
