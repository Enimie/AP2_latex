![LaTeX](LaTeX_logo.svg.png)

# Humanités numériques : outils numériques pour la thèse (LATEX et Zotero) (ENC 2456)

Vous trouverez sur ce dépôt le contenu pédagogique du cours *Outils numériques pour la thèse (LATEX et Zotero)*  (AP2, École nationale des Chartes)  


## Planning

| Date | Horaires | Programme |
| ---- | -------- | --------- |
| 10 novembre 2023  | 13h30-15h30 | Notions de base| 
| 17 novembre 2023 | 13h30-15h30 | Mettre en forme, mettre en sens |
| 24 novembre 2023 | 13h30-15h30 | Citations bibliographiques: Zotero et Biblatex -- Images tableaux et graphiques  |
| 8 décembre 2023     | 9h30-11h30  | Édition scientifique en LaTeX|
| 15 décembre 2023     | 9h30-11h30  | LaTeX et la thèse |



## Installation de LaTeX sur linux


### 1/ Pré-requis

Avoir le package `perltk` installé. Si ce n'est pas le cas:
- Ouvrez un terminal
- Tapez la commande suivante: `sudo apt install perl-tk` 


### 2/ Télécharger le programme d'installation

Deux possibilités: 

1. Téléchargez le fichier *via* le lien suivant: [install-tl-unx.tar.gz](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz)
2. Dans le terminal, placez-vous dans le dossier Téléchargement par la commande `cd ~/Téléchargements` puis tapez `wget https://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz`

Une fois le fichier téléchargé, décompressez-le. Pour cela,  tapez dans le terminal la commande `tar -xf install-tl-unx.tar.gz`


### 3/ Installer la texlive

1. Placez-vous dans le dossier que vous avez décompressé par la commande `cd` suivie du nom du dossier (`install-tl-20230926`; le nombre peut être différent). Vous pouvez utiliser la touche Tab pour activer l'autocomplétion du nom du dossier.
2. Tapez `sudo perl install-tl`
3. Si vous avez de la place sur votre ordinateur et une bonne connexion internet: répondez `i` ("start installation to hard disk"). **Cette option est à privilégier**
4. Si votre connexion est mauvaise, ou que vous avez trop peu de place, vous pouvez au choix:
	- tapez`c` pour sélectionner quelques collections de packages à décocher. Vous pouvez enlever sans problème les collections désignées par les lettres suivantes: `iklmnowxyzABCPS`. Attention, certaines collections seront utiles si vous comptez utiliser les langues concernées (par exemple arabe ou persan dans la collection `arabit`. Dans ce cas, ne les indiquez pas).
	- Si même ainsi cela prend trop de place/de temps, tapez `j` pour sélectionner un schéma et choisissez "teTex"   

	-> Tapez ensuite `r` pour retourner au menu principal, et `i` pour lancer l'installation.  
Il sera de toute façon possible d'installer plus tard ces collections si vous en avez besoin. 

### 4/ Configurer

Il ne reste plus qu'à configurer votre installation:

1. Tapez`sudo nano ~/.profile`
2. Dans le fichier qui s'ouvre, ajoutez à la fin les lignes suivantes: 

```
PATH=/usr/local/texlive/2023/bin/x86_64-linux:$PATH; export PATH
MANPATH=/usr/local/texlive/2023/texmf/doc/man:$MANPATH; export MANPATH
INFOPATH=/usr/local/texlive/2023/texmf/doc/info:$INFOPATH; export INFOPATH
```

3. Enregistrez le fichier, et tapez dans le terminal `source ~/.profile` pour que le changement soit pris en compte.
4. Vérifiez que tout fonctionne en tapant `which xelatex` dans le terminal: vous devez avoir le chemin de la texlive 2023 qui s'affiche.


### 5/ Installer un éditeur de texte (TexStudio)

Tapez dans un terminal la commande suivante: `sudo apt install texstudio` 

## Installer LaTeX sur les autres systèmes d'exploitation:


- Suivre les indications ici: [texlive](https://tug.org/texlive/).
- Installez [Texstudio](https://www.texstudio.org/)



