# InterAACtionBox-Live

# Prérequis

Avant de commencé l'installation, il faut :
* La clé USB
* Un eye tracker
* Un pc suffisamment chargé pour éviter qu'il s'éteigne durant l'installation

# BIOS

## Etape 1: Préparation

Avant d'allumer l'ordinateur, inséré la clé USB dans l'ordinateur.

## Etape 2: Accès au Bios

Allumer l'ordinateur et presser F2 dès que le logo dell apparaît.<br>

## Etape 3: Préparer le démarrage de l'ordi sur la clé USB

Une fois arrive dans le menu BIOS, comme le montre l'image ci-dessous.

![menuBIOS](assets/tutorial/bootMenu.png)

Il faudra aller dans la rubrique "Boot configuration".

![boot config](assets/tutorial/bootConfiguration.png)

Puis il faudra réorganiser les lignes en mettant la clé USB en 1er position. <br>

Pour ce faire, il suffit de cliquer sur la petite flèche bleu pointant vers le haut à côté des nom s'appellant "UEFI General UDisk" 1 et 2. <br>

Vous devrier vous retrouver comme cela :

![boot Organiser](assets/tutorial/bootOrganisation.png)

Pour finir, appliquer les modifications en cliquant sur "Apply change" tout en bas.<br>
A ce moment la, une fenêtre noir comme l'image ci-dessous va s'ouvrir vous demandant la confirmation d'appliquer ces changements.<br>

![boot accept](assets/tutorial/bootAcceptChanges.png)

Cliquez sur "Ok".<br>
Et ensuite cliquez sur le bouton "Exit" tout en bas à droite.<br>
Cela va eteindre l'ordinateur et le redemmarer

# Installation

## Etape 1: vérification de la clé USB

Si tout à bien était fait pendant la partie BIOS.<br>
Vous allez, après un petit temps de chargement, arriver sur cet écran ci-dessous.<br>
A ce moment la vous avez 2 choix :
* Passer la vérification en appuyant sur "ctrl + c"
* Attendre la vérification de la clé USB pour vérifié son intégrité

Si vous avez choisie le 2ème choix, alors il existe 2 cas de figure :
* Pas d'erreur trouvé, tout va bien vous pouvez passer a la suite
* Des erreurs sont trouvés, vous devez arrêter l'installation et nous contacter

![chargement](assets/tutorial/chargementUbuntu.png)

## Etape 2: Installation de l'InterAACtionBox

### Démarrage

Un fois les vérifications faites ou si vous avez passer ceux la. <br>
Vous allez arriver sur le premier écran.<br>
Choisissez d'abord votre langue.<br>
Puis sélectionner "installer InteraactionBox". <br>

![installation premier ecran](assets/tutorial/InstallationInteraaaction.png)

### Clavier

Choisissez ensuite la langue de votre clavier.<br>

![langue du clavier](assets/tutorial/langueClavier.png)

### WI-FI

Durant cette étape vous pouvez :
* Soit faire l'installation sans connexion internet
* Soit faire l'installation avec votre connexion iternet

![connexion](assets/tutorial/connexion.png)

### Mise à jour

Choisir l'installation minimale <br> 
Et cochez l'option "Télécharger les mise à jour pendant l'installation de InteraactionBox" si vous faite l'installation avec une connexion internet.

![minimal](assets/tutorial/choisirMinimal.png)

### Type d'installation

Le type d'installation va être demandé, ici 2 choix s'offrent à vous :

- Soit vous décidez de créer un dual boot et vous sélectionnez le premier choix (mais vous aurez assurément des complications si vous avez un window au parallèle).
- Soit vous décidez d'écraser votre ancien système d'exploitation et mettre celui-ci à la place, dans ce cas prendre le second choix.

![dualboot choix](assets/tutorial/dualbootOrFormat.png)

Si vous prenez le second choix vous aurez une fenêtre qui vous demandera si vous êtes sûr d'écraser le système d'exploitation précédent.<br>
A ce moment la, cliquer sur continuer. <br>

![confirmation](assets/tutorial/Overwrite.png)

### Fuseaux horaire

Sélectionner votre ville puis continuer.

![fuseau horaire](assets/tutorial/fuseauHoraire.png)

### Compte utilisateur

Créer votre utilisateur avec un nom et un mot de passe puis continuer.<br>
Même si vous avez un message disant que le mot de passe et trop court ou autre, pas de panique cela n'est pas bloquant.
Pour 

![user](assets/tutorial/createUser.png)

### Installation

A ce moment la, l'InterAACtionBox AFSR va s'installer ainsi que toute les applications. <br>
Pendant ce temps la, un diaporama est disponible et vous pouvez le parcourir pour voir tout ce que nous proposons.

![chargementUbuntu](assets/tutorial/chargementApresInstall.png)

Une fois l'installation terminée, une fenêtre va apparaître et vous demandera de redémarrer, appuyez sur "redémarrer maintenant". <br>
Après quelques instants, vous allez arriver sur un écran noir avec le logo de l'interAACtionBox. <br>
A ce moment la, retirer la clé USB et appuyer sur la touche "Entrer" de votre clavier. <br>
Attendez encore quelques secondes et votre ordinateur va redemmarer et lancer l'interAAction fraîchement installer.

![redemarrer](assets/tutorial/redemarrer.png)

## Finalisation

### Etape 1: L'eye tracker

Pour finir avec l'installation, il ne reste plus qu'à calibrer l'eye tracker.<br>
Pour ce faire, suivez ce qu'il y a d'indiquer sur l'écran.

### Etape 2: Le menu principal

Une fois l'eye tracker configuré, voici la page principal de notre InterAACtionBox.

![interaaaction](assets/tutorial/interaactionBox.png)
