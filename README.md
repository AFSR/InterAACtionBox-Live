# InterAACtionBox-Live

## Etape 1: Préparation de la surface

Avant de continuer, il est nécessaire d'avoir au moins 2 port usb disponible :
* 1 pour la clé usb
* 1 pour un clavier afin de pouvoir écrire
* 1 pour la souris (mais ceci est optionnel, on peut tout faire avec un clavier)

Pour ce faire, le mieux est d'avoir un switch afin de pouvoir tous connecter.

Nous avons utilisé ce switch -> https://www.amazon.fr/Sabrent-commutateurs-dalimentation-individuels-HB-UM43/dp/B00JX1ZS5O/ref=sr_1_4?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=sabrent+switch&qid=1645442409&sr=8-4

## Etape 2: Désactiver les sécurité de la tablette

Avant de pouvoir boot sur la clé il faut désactiver 2 sécurités :
* BitLocker
* Secure Boot.

Pour le BitLocker, lancer la surface sous Windows puis accéder au Panneau de configuration et enfin aller dans Système.<br>
Ensuite cliquer sur "A propos de" dans le côté gauche.<br>
Faire défiler jusqu'à "Chiffrement de l'appareil" et cliquer sur le bouton "Desactiver" (cette action peut prendre quelques minutes).<br>
Un fois cela terminer, BitLocker sera désactivé.

Pour le Secure Boot, il faut accéder à l'UEFI de la surface.<br>
Pour acceder à l'UEFI, il faut appuyer sur le bouton d'augmentation de volume de la surface et le maintenir enfoncé, puis allumer la surface.<br>
Une fois arrivé dans l'UEFI, (arrêter d'appuyer sur le bouton d'augmentation de volume) aller dan l'onglet "Security".<br>
Cliquer sur le bouton "Change configuration"  dans la partie Secure Boot.<br>
Dans le menu déroulant, choisir "None".<br>
Enfin aller dans l'onglet "Exit" et cliquer sur "Restart Now".

## Etape 3: Boot sur la clé USB

Pour boot sur la clé usb, il faut, avant d'allumer la surface, appuyer et maintenir le bouton de "diminution du volume" jusqu'à voir le logo ubuntu.

## Etape 4: Installation de l'OS

Avant d'arriver au menu, cet écran de chargement s'affichera, veuillez patienter.

![chargement](assets/tutorial/chargementUbuntu.png)

Vous allez arriver sur le premier écran.

![installation premier ecran](assets/tutorial/InstallationInteraaaction.png)

Sélectionner "installer interaaction". <br>

Choisir la langue de votre clavier.

![langue du clavier](assets/tutorial/langueClavier.png)

Choisir votre réseau Wi-Fi (Attention, une connexion internet est nécessaire pour mettre à jour).

![connexion](assets/tutorial/connexion.png)

Choisir l'installation minimale et laisser le reste par défaut.

![minimal](assets/tutorial/choisirMinimal.png)

Le type d'installation va être demandé, ici 2 choix s'offrent à vous :

- Soit vous décidez de créer un dual boot (dans ce cas, vous pourrez démarrer avec Windows ou avec l'InterAACtionBox), sélectionnez le premier choix.
- Soit vous décidez d'écraser votre ancien système d'exploitation (dans ce cas, vous ne pourrez démarrer qu'avec l'InterAACtionBox), sélectionnez le second choix.

![dualboot choix](assets/tutorial/dualbootOrFormat.png)

Si vous prenez le second choix vous aurez une fenêtre qui vous demandera si vous êtes sûr d'écraser le système d'exploitation précédent.

![confirmation](assets/tutorial/Overwrite.png)

Cliquer sur continuer. <br>

Sélectionnez votre ville puis continuer.

![fuseau horaire](assets/tutorial/fuseauHoraire.png)

Créez votre utilisateur avec un nom et un mot de passe puis continuer.

![user](assets/tutorial/createUser.png)

Ubuntu va s'installer veuillez attendre.

![chargementUbuntu](assets/tutorial/chargementApresInstall.png)

Une fois l'installation terminée, une fenêtre va apparaître et vous demandera de redémarrer, appuyez sur "redémarrer maintenant".

![redemarrer](assets/tutorial/redemarrer.png)

Une fois connecté, aller dans "Mise à jour disponible !" en haut à gauche de l'écran si vous avez une connexion internet.

![interaaaction](assets/tutorial/interaactionBox.png)

Sur cette page, appuyer sur "installer tous" pour avoir accès à toutes les applications (nécessite une connexion internet).

![mise à jour](assets/tutorial/miseajour.png)

## Bug connu

Si l'interAACtion box vous bloque dans les menus et que vous devez sortir, allumez l'ordinateur, sortez du mode veille et allez dans le menu utilisateur, puis redémarrez l'ordinateur.
