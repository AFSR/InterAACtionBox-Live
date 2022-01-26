# InterAACtionBox-Live

Nécessite une clé usb d'au moins 8Go (Attention : le contenu sera effacé)

## Etape 1: Téléchargement de l'ISO

Le fichier est disponible ici :
- https://interaactionbox.afsr.fr/Interaactionbox-v.Beta-2.4.4.11.05.iso

## Etape 2: Graver l'ISO téléchargé sur la clé USB

Utiliser balenaEtcher (qui est multi-platerforme - mac, windows, linux - et simple à utiliser) ou un outil équivalent

Aller sur https://www.balena.io/etcher/

<img width="1372" alt="Capture d’écran 2021-10-15 à 19 15 24" src="https://user-images.githubusercontent.com/23239584/137527182-8a0568b4-1d0a-42f0-93a6-53fe2017a2e7.png">

Choisissez votre système d'exploitation 

<img width="1372" alt="Capture d’écran 2021-10-15 à 19 17 01" src="https://user-images.githubusercontent.com/23239584/137527340-87c5893b-5091-431b-b745-184c7faa7008.png">

Installer le logiciel et le lancer.

L'écran suivant s'ouvre :

<img width="868" alt="Capture d’écran 2021-10-15 à 19 11 52" src="https://user-images.githubusercontent.com/23239584/137526990-314bfd93-5f6b-4c74-a5ed-a43015f8227e.png">

Appuyez sur "+", une fenêtre s'ouvre. Choisir l'iso téléchargé.

<img width="912" alt="Capture d’écran 2021-10-15 à 19 12 23" src="https://user-images.githubusercontent.com/23239584/137527021-3b7c5dc8-99a5-4f89-9045-d5b06b99c335.png">

Appuyez sur "select", une fenêtre s'ouvre. 

<img width="912" alt="Capture d’écran 2021-10-15 à 19 12 34" src="https://user-images.githubusercontent.com/23239584/137527032-34150af6-e57d-47c8-b020-a88b22a725d2.png">

Sélectionner votre clé USB dans la liste.

<img width="912" alt="Capture d’écran 2021-10-15 à 19 12 40" src="https://user-images.githubusercontent.com/23239584/137527042-aae78a2f-6d1f-4c86-9520-a974e7dfa59b.png">

Cliquer sur "flash".

## Etape 3: inséré la clé USB dans la surface

cf https://github.com/InteraactionGroup/InterAACtionBox pour voir la surface que nous avons utilisée.

Le mieux est d'avoir un switch avec minimum 3 emplacements afin de pouvoir connecter un clavier et/ou souris si besoin.

## Etape 4: Désactiver les sécurité de la tablette

Avant de pouvoir boot sur la clé il faut désactiver 2 sécurités :
* BitLocker
* Secure Boot.

Pour le BitLocker, accéder au Panneau de configuration puis aller dans Système.<br>
Ensuite cliquer sur "A propos de" dans le côté gauche.<br>
Faire défiler jusqu'à "Chiffrement de l'appareil" et cliquer sur le bouton "Desactiver" (cette action peut prendre quelques minutes).<br>
Un fois cela terminer, BitLocker sera désactiver.

Pour le Secure Boot, il faut accéder à l'UEFI de la surface.<br>
Pour acceder à l'UEFI, il faut appuyer sur le bouton d'augmentation de volume de la surface et le maintenir enfoncé, puis allumer la surface.<br>
Une fois arrivé dans l'UEFI, (arrêter d'appuyer sur le bouton d'augmentation de volume) aller dan l'onglet "Security".<br>
Cliquer sur le bouton "Change configuration"  dans la partie Secure Boot.<br>
Dans le menu déroulant, choisir "None".<br>
Enfin aller dans l'onglet "Exit" et cliquer sur "Restart Now".

## Etape 5: boot sur la clé USB

Pour boot sur la clé usb, il faut, avant d'allumer la surface, appuyer et maintenir le bouton de "diminution du volume" jusqu'à voir le logo ubuntu.

## Etape 6: installation de l'OS

Avant d'arriver au menu, cet écran de chargement s'affichera, veuillez patienter..

![chargement](assets/tutorial/chargementUbuntu.png)

Vous allez arriver sur le premier écran.

![installation premier ecran](assets/tutorial/InstallationInteraaaction.png)

Sélectionner "installer interaaction". <br>

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

![redemarrer](assets/tutorial/redemarrer.png)

Une fois connecté, aller dans "Mise à jour disponible !" en haut à gauche de l'écran.

![interaaaction](assets/tutorial/interaactionBox.png)

Sur cette page, appuyer sur "installer tous" pour avoir accès à toutes les applications.

![mise à jour](assets/tutorial/miseajour.png)

## Bug connu

Si l'interAACtion box vous bloque dans les menus et que vous devez sortir, allumez l'ordinateur, sortez du mode veille et allez dans le menu utilisateur, puis redémarrez l'ordinateur.
