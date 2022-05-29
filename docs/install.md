---
layout: page
title: Install
description: >
  There are multiple ways of installing Nyctalopia and this document lays them out for you.
---

There are multiple ways of installing Nyctalopia.
The easiest and cleanest way is [via Steam](#via-steam).
Alternatively, you can use the [a provided installation media](#via-the-provided-installation-media-/-via-le-support-d'installation-fourni).

Il existe plusieurs façons d'installer Nyctalopia.
Le moyen le plus simple est [via Steam](#via-steam).
Vous pouvez également utiliser le [support d'installation fourni](#via-the-provided-installation-media-/-via-le-support-d'installation-fourni).

## Table of Contents
{:.no_toc}
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

## Minimal and recommended configuration / Configuration minimale et recommandée

To play Nyctalopia you will need a PC (bruh logic :)), but some PCs may struggle with this unoptimized game xd, so we have made a list of components compatible with our game :


Pour jouer à Nyctalopia, vous aurez besoin d'un PC (bruh logique :)), mais certains PC peuvent avoir du mal avec ce jeu non optimisé xd, nous avons donc fait une liste de composants compatibles avec notre jeu :

|                                     | Minimal configuration                  | Recommended configuration                    |
|:------------------------------------|:--------------------------------------:|:--------------------------------------------:|
| OS                                  | 64-bits Windows 10 Build >= 1909 or an APT-based Linux distribution | 64-bits Windows 11 or a Linux distribution supporting Steam |
| CPU                                 | Intel Core i7-4770K or AMD Ryzen 5 2600 | Intel Core i7-6700 or AMD Ryzen 5 2700X     |
| GPU                                 | Nvidia GTX 1060 or AMD RX5500 XT (VRAM >= 6 GB) | Nvidia GTX 1080 OR AMD RX5600 XT (VRAM > 6 GB) |
| RAM                                 | 8 GB DDR3                              | 16 GB DDR4                                   |
| DirectX                             | v11 &#x2714; (only Windows)            | v12 &#x2714; (only Windows)                  |
| Disk                                | 15 GB of free space                    | 20 GB of free space                          |
{:.stretch-table}


## Via Steam

### English

Do you really need to know how to install a game via Steam ?
Well, fine...

[CLICK ON ME TO SUMMON STEAM](steam://install/1937920)

**NOTE** : This button should also work for Linux users :).
{:.message}

### Français

Avez-vous vraiment besoin de savoir comment installer un jeu via Steam ?
Bon...

[CLIQUEZ SUR MOI POUR INVOQUER STEAM](steam://install/1937920)

**REMARQUE** : Ce bouton devrait également fonctionner pour les utilisateurs Linux :).
{:.message}

## Via the provided installation media / Via le support d'installation fourni

### Windows edition (x64 processors)

#### English

Follow the instructions given by the installer. 
To do a classic installation, simply click on "Install" after accepting the license terms and conditions. 
You will be prompted for admin rights during installation, just click "Yes" when prompted. 
After installation, you will be asked if you want to launch the game. 
To launch the game later, a shortcut was created on your desktop. 
Simply double-click this shortcut to start playing.

#### Français

Suivez les instructions données par l'installateur. 
Pour faire une installation classique, cliquez simplement sur "Installer" après avoir accepté les termes et conditions de la licence. 
Vous serez être invité à fournir des droits d'administrateur lors de l'installation, cliquez simplement sur "Oui" lorsque vous y êtes invité. 
Après l'installation, vous serez demandé si vous voulez lancer le jeu. 
Pour lancer le jeu plus tard, un raccourci a été créé sur votre bureau. 
Simplement double-cliquez sur ce raccourci pour commencer à jouer.

### Linux edition (still x64-based processors :))

#### English

Yes, Linux users are not forgotten! To install Nyctalopia on your Linux computer, open a terminal and type these commands

~~~bash
$ # Navigate to the directory where the script was downloaded :
$ chmod u+x InstallNyctalopia.sh
$ ./InstallNyctalopia.sh
~~~

**NOTE**: The InstallNyctalopia.sh script is only provided if you purchase the game! Don't expect anything if you don't have the file on your computer!
{:.message}

Follow the instructions given by the installer. If something went wrong during the installation, you can try again by retyping the command just above!
Your directory should look like this :

~~~
├── Downloads 
│   └── InstallNyctalopia.sh
└── *Your favourite game directory*
    └── Nyctalopia
        └── Nyctalopia.x86_64
        └── libsteam_api.so
        └── steam_api64.dll
        └── steam_api64.lib
        └── steam_appid.txt
        └── UnityPlayer.so
        └── Nyctalopia_Data
            └── Some important files
~~~

**NOTE**: If a file is missing, please delete the directory and reinstall. If the problem persists, please contact us here: [support@nyctalopia.games](mailto://support@nyctalopia.games).
!
{:.message}

#### Français

Oui, les utilisateurs de Linux ne sont pas oubliés ! Pour installer Nyctalopia sur votre ordinateur Linux, ouvrez un terminal et tapez ces commandes :

~~~bash
$ # Accédez au répertoire où le script a été téléchargé :
$ chmod u+x InstallNyctalopia.sh
$ ./InstallNyctalopia.sh
~~~

**REMARQUE** : Le script InstallNyctalopia.sh n'est fourni que si vous achetez le jeu ! N'attendez rien si vous n'avez pas le fichier sur votre ordinateur !
{:.message}

Suivez les instructions données par l'installateur. Si quelque chose s'est mal passé lors de l'installation, vous pouvez réessayer en retapant la commande juste au-dessus !
Votre répertoire devrait ressembler à ceci :

~~~
├── Téléchargements 
│   └── InstallNyctalopia.sh
└── *Votre dossier contenant vos jeux préférés*
    └── Nyctalopia
        └── Nyctalopia.x86_64
        └── libsteam_api.so
        └── steam_api64.dll
        └── steam_api64.lib
        └── steam_appid.txt
        └── UnityPlayer.so
        └── Nyctalopia_Data
            └── Quelques fichiers importants
~~~

**REMARQUE** : Si un fichier est manquant, veuillez supprimer le répertoire et refaire l'installation. Si le problème persiste, veuillez nous contacter ici : [support@nyctalopia.games](mailto://support@nyctalopia.games).
!
{:.message}

Continue with [Update](update.md){:.heading.flip-title}
{:.read-more}