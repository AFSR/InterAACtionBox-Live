# InterAACtionBox-Live

## Etape 1: Téléchargement de l'ISO

Le fichier est disponible ici :
- https://www.swisstransfer.com/d/8ac46617-37b5-4895-9ae6-111359731d38

## Etape 2: Graver l'ISO téléchargé sur la clé USB

Conseil : utiliser balenaEtcher (suite à refaire)

## Etape 3: inséré la clé USB dans l'ordinateur

cf https://github.com/InteraactionGroup/InterAACtionBox pour voir l'ordinateur que nous avons sélectionné.

## Etape 4: boot sur la clé USB

presser F2 dès que le logo dell apparaît

Une fois dans le menu BIOS.

![menuBIOS](assets/tutorial/bootMenu.png)

Il faudra aller dans la rubrique "Boot configuration".

![boot config](assets/tutorial/bootConfiguration.png)

Puis il faudra réorganiser les lignes en mettant les ports USB en premier.

![boot Organiser](assets/tutorial/bootOrganisation.png)

Pour finir, appliquer les modifications et redémarrer l'ordinateur.

![boot accept](assets/tutorial/bootAcceptChanges.png)

## Etape 5: installation de l'OS

Avant d'arriver au menu, cet écran de chargement s'affichera, veuillez patienter..

![chargement](assets/tutorial/chargementUbuntu.png)

Vous allez arriver sur le premier écran.

![installation premier ecran](assets/tutorial/InstallationInteraaaction.png)

Sélectionner "installer interaaaction". <br>

Choisir la langue de votre clavier.

![langue du clavier](assets/tutorial/langueClavier.png)

Choisir votre réseau Wi-Fi (Attention, pour installer les logiciels ou faire les mises à jour une connexion internet est obligatoire !).

![connexion](assets/tutorial/connexion.png)

Choisir l'installation minimale et laisser le reste par défaut.

![minimal](assets/tutorial/choisirMinimal.png)

Le type d'installation va être demandé, ici 2 choix s'offrent à vous :

- Soit vous décidez de créer un dual boot et vous sélectionnez le premier choix (mais vous aurez assurément des complications si vous avez un window au parallèle).
- Soit vous décidez d'écraser votre ancien système d'exploitation et mettre celui-ci à la place, dans ce cas prendre le second choix.

![dualboot choix](assets/tutorial/dualbootOrFormat.png)

Si vous prenez le second choix vous aurez une fenêtre qui vous demandera si vous êtes sûr d'écraser le système d'exploitation précédent.

![confirmation](assets/tutorial/Overwrite.png)

Cliquer sur continuer. <br>

Sélectionner votre ville puis continuer.

![fuseau horaire](assets/tutorial/fuseauHoraire.png)

Créer votre utilisateur avec un nom et un mot de passe puis continuer.

![user](assets/tutorial/createUser.png)

Ubuntu va s'installer veuillez attendre.

![chargementUbuntu](assets/tutorial/chargementApresInstall.png)

Une fois l'installation terminée, une fenêtre va apparaître et vous demandera de redémarrer, appuyez sur "redémarrer maintenant".

![redemarrer](assets/tutorial/redemarrer.jpg)

Au redémarrage, l'interAACtion box se lance automatiquement, il vous faudra aller dans "Mise à jour disponible !" en haut à gauche de l'écran.

![interaaaction](assets/tutorial/interaactionBox.png)

Sur cette page, vous devez appuyer sur "installer tous" pour avoir accès à toutes les applications.
![mise à jour](assets/tutorial/miseajour.png)

## Bug connu

Si l'interAACtion box vous bloque dans les menus et que vous devez sortir, allumez l'ordinateur, sortez du mode veille et allez dans le menu utilisateur, puis redémarrez l'ordinateur.
