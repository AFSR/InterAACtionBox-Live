# InterAACtionBox-Live

## Etape 1: boot sur la clé USB

Avant d'allumer l'ordinateur, inséré la clé USB dans l'ordinateur.<br>
Ensuite allumer l'ordinateur et presser F2 dès que le logo dell apparaît.<br>

Une fois dans le menu BIOS.

![menuBIOS](assets/tutorial/bootMenu.png)

Il faudra aller dans la rubrique "Boot configuration".

![boot config](assets/tutorial/bootConfiguration.png)

Puis il faudra réorganiser les lignes en mettant les ports USB en premier.

![boot Organiser](assets/tutorial/bootOrganisation.png)

Pour finir, appliquer les modifications et redémarrer l'ordinateur.

![boot accept](assets/tutorial/bootAcceptChanges.png)

## Etape 2: installation de l'OS

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

Une fois l'installation terminée, une fenêtre va apparaître et vous demandera de redémarrer, appuyez sur "redémarrer maintenant". <br>
Après quelques instants, vous allez vous rentrer sur un écran noir avec le logo de l'interAACtionBox. <br>
A ce moment la, retirer la clé USB et appuyer sur la touche "Entrer" de votre clavier. <br>
Attendez encore quelques secondes et votre ordinateur va redemmarer et lancer l'interAAction fraîchement installer.

![redemarrer](assets/tutorial/redemarrer.png)

Une fois connecté, aller dans "Mise à jour disponible !" en haut à gauche de l'écran.

![interaaaction](assets/tutorial/interaactionBox.png)

Sur cette page, appuyer sur "installer tous" pour avoir accès à toutes les applications.
![mise à jour](assets/tutorial/miseajour.png)

## Bug connu

Si l'interAACtion box vous bloque dans les menus et que vous devez sortir, allumez l'ordinateur, sortez du mode veille et allez dans le menu utilisateur, puis redémarrez l'ordinateur.
