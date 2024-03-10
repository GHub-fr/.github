cours sur Windows

# Raccourcis
## Menus
- `Win + R` Recherche ou commande
- `Win + V` Historique des copier / coller
- `Win + E` Explorateur de fichiers

- `Control + Alt + Suppr` Menu de secours pour la gestion Windows

### TaskManager
- Raccourcis `Ctrl Alt Suppr`, `TAB, TAB` `Entrée`
- `Ctrl + Shift + Escape` Raccourcis direct

## Fenêtres
- `Win + ➡` Déplacer la fenêtre sélectionnée dans la direction de la flèche
- `Win + ↑` Vers le haut ou le bas : Cache ou maximise la taille de fenêtre

- `Windows + ↹` Changer de fenêtre (suivante)
- `Windows + ↹` Changer de fenêtre (précédente)

- `Control + Descendre/Monter la molette de souris` Gestion du zoom

- `↑ Shift + Descendre/Monter la molette de souris` Se déplacer à l'horizontale
- `Descendre/Monter la molette de souris` Se déplacer à la verticale

## Autres raccourcis
- `Windows + ↑ Shift` Changer de langue
- `Windows + Espace` Changer de langue

## Déplacement au clavier
- `Control + Z` Annuler / Retour en arrière

- `↹ TAB` Se déplacer dans un champ de saisie/bouton suivant
- `↑ Shift + ↹` Se déplacer dans un champ de saisie/bouton précédent

- `Enter` / `Touche Entrée` Appuis sur le bouton ou ajoute une ligne vide sur un champ de text

# Console
- `Echo` Affiche du text
- `:Text` Crée le début d'une boucle nommé 'Text'
- `goto :Text` Le code va exécuter la boucle 'Text'
`%random%` Chiffres aléatoires
- `color [couleurs]` Couleur du text ou de l'arrière plan  
Pour modifier la couleur d’arrière-plan de la fenêtre d’invite de commandes en gris et la couleur de premier plan en rouge, tapez : `color 84`
- `exit` ferme la console
- `whoami` affiche le nom d'utilisateur

## Dossiers
- `dir` Dossiers et fichiers
- `copy [path\file.ext] [path\newfile.ext]` Copier & Coller
- `del [path\file.ext]` Supprimer
- `cd [chemin]` permet de se déplacer dans la structure de dossier
- `cd ..` retour en arrière d'un dossier

## Disques
- `sfc /scannow` scan le système Windows
- `chkdsk /f` vérifie l’intégrité des fichiers système
- `chkdsk /f C:` vérifie l’intégrité des fichiers système du disque C:
- `format [drive letter]: /fs:[file system] /q` Formatter un disque, ex : `format h: /fs:ntfs /q`
- `diskpart` disques et outils de formatage

## Réseau
- `ipconfig` configuration IP
- `ping [IP/DNS]` Envoie un paquet IP
- `tracert` Trace la route des rebonds d'un paquet IP

## Système
- `systemInfo` Information système
- `shutdown /s` Arrête le système
- `logoff` Déconnecte le compte Windows
- `ver` Version du système
- `tasklist` Liste des processus
- `taskkill /f /im [process name]` Tuer un processus par le nom
- `taskkill /f /pid [process ID]` Tuer un processus par son ID

# Installation via ISO
## Télécharger l'ISO
- [microsoft.com/fr-fr/software-download/windows10ISO](https://www.microsoft.com/fr-fr/software-download/windows10ISO)
- Liens ISO autre bientôt...

## Déplacer l'ISO sur un support
- Clef USB / réseau (server de mastering) / CD, ...

## BIOS
- Booter d'ISO vs auto setup

### Touches du BIOS
- touche `F1` à `F12`
- peut-être la touche `Suppr`

### Boot order
- Le boot order signifie l'ordre de démarrage des supports de stockage
- Dès qu'un système compatible est chargé il est lancé (Système, comme outil)
- Vous pouvez le changer en déplacent vers le haut le support requis

![Boot order image](https://www.intel.com/content/dam/support/us/en/images/server-products/59753_image1.png)

## Setup
![Setup image](https://user.oc-static.com/upload/2021/05/18/1621371554096_image21.png)

### Astuces
- Hors réseau = pas de demande de compte Microsoft.  Connectez vous après au réseau

### Configuration IP
![Setup IP](https://github.com/GHub-fr/.github/assets/84735589/6bc12b12-09f0-4842-833e-3162fb8fb3fe)

- `Panneau de configuration\Réseau et Internet\Connexions réseau` Chemin d'explorateur
- `Windows` + `connexions réseau` Menu de recherche Windows

### Sous-réseau

### Box / Routeurs / Switch

### Local

### Network storage

# ActiveDirectory
Soon ...
