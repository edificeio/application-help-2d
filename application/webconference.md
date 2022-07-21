# Web-conférence
Utilisez l'outil **web-conférence** pour créer et gérer facilement vos salles virtuelles.

## Présentation
L’application **Web-conférence** permet de créer et de partager des salles de web-conférences aux utilisateurs de la plateforme. Il permet aussi de diffuser des contenus en direct sur Peertube.La liste de vos salles créées est affichée et vous pouvez les gérer directement depuis cet écran.

![](<.gitbook/assets/001_liste_salle.png>)

## Créer, gérer et partager une salle
Sur la page de web-conférence, cliquez sur le bouton **« Créer une salle »** pour créer une nouvelle salle.

Saisissez le nom de votre salle, puis cliquez sur **« Créer »**. Si vous souhaitez activer la salle d'attente pour valider l'entrée des participants dans la salle, cochez la case **« Activer la salle d'attente »**.
Si vous souhaitez activer le streaming de la salle pour pouvoir partager votre contenu en direct sur Peertube et/ou enregistrer votre visioconférence, cochez la case **« Activer le streaming de la salle »**.

![](<.gitbook/assets/002_nom_salle.png>)

La salle créée apparaît dans la liste de vos salles. Elle est fermée par défaut.

Si la liste d'attente est activée, une icône est affichée :
![](<.gitbook/assets/003_Icone_attente.png>)

Si le streaming est activé, une icône est affichée et devient verte quand le streaming est effectif :
![](<.gitbook/assets/003.2_Icone_streaming.png>)

Pour ouvrir une salle, sélectionnez la salle en cliquant dessus (1) et cliquez sur **« Ouvrir la salle » **(2).

![](<.gitbook/assets/004_Ouvrir_salle.png>)

Une fois la salle ouverte, vous pouvez la **rejoindre** (1), la **fermer** (2), copier le lien à partager pour **inviter des participants** à rejoindre votre salle (3) et **gérer le streaming** en l'arrêtant ou le relançant tout en gardant la salle de visioconférence ouverte (4). Il y a un temps de décalage entre le clic sur le bouton et l'arrêt ou la reprise du streaming effective sur Peertube qui est similaire au temps de décalage à l'ouverture du streaming.

![](<.gitbook/assets/005_gerer_salle.png>)

**Inviter des utilisateurs de la plateforme**

Pour inviter des utilisateurs à rejoindre votre salle de web-conférence, deux solutions sont possibles :

* Copier le lien et le transmettre aux utilisateurs par le moyen de votre choix.
* Sélectionner la salle et cliquer sur "Envoyer une invitation".

    ![](<.gitbook/assets/006_envoyer_invitation.png>)

Une pop-up s'ouvre pour vous permettre d'envoyer un message d'invitation aux participants. Après avoir sélectionné les destinataires (1), vous pouvez modifier l'objet (2) et le corps du message (3). Une fois l'invitation envoyée (4), les participants la recevront dans leur messagerie et pourront utiliser le lien pour se connecter à la web-conférence.
![](<.gitbook/assets/007_envoyer_invitation_pop_up.png>)

Après connexion, les utilisateurs seront redirigés directement sur la page de la conférence.

**Partager la gestion de la salle**

Vous pouvez partager votre salle en gestion et en modération en utilisant l'option de partage de la salle.

![](<.gitbook/assets/008_partager.png>)


* Les modérateurs pourront ouvrir et fermer la salle. Lors de leur connexion à la salle, ils y auront le rôle de modérateurs.
* Les gestionnaires pourront ouvrir et fermer la salle, envoyer des invitation, repartager la salle à d'autres utilisateurs et modifier les paramètres de la salle. Lors de leur connexion à la salle, ils y auront le rôle de modérateurs.
  ![](<.gitbook/assets/009_pop-up_partage.png>)

Lorsque la salle a été partagée, une icône ![](<.gitbook/assets/010_icone_partage.png>) s'affiche.

## Gérer ma webconférence

Une fois connecté sur la **salle de web-conférence**, vous pouvez gérer différents aspects de la conférence, tels que la présentation, la diffusion de contenu, les participants …
![](<.gitbook/assets/011_BBB.png>)

Le panel de gauche vous permet de voir et gérer la **liste des utilisateurs connectés** à votre web-conférence (1), d’accéder au **notes partagées** (2) et à la **discussion (chat) de groupe** (3).
![](<.gitbook/assets/012_BBB_panneau_gauche.png>)

Sur la seconde partie de l’écran, vous pouvez choisir de partager ou non votre webcam, votre micro ou votre écran (1), d’y ajouter des **annotations en direct** pour les utilisateurs connectés (2). Il vous est aussi possible de **charger un document**, de créer un **sondage en direct** ou de **partager une vidéo externe** (3).
![](<.gitbook/assets/013_BBB_panneau_droit.png>)

**Gestion de la salle d'attente**

Si vous avez activé la salle d'attente, les utilisateurs devront patienter avant d'entrer dans la salle.

Lorsqu'il y a des utilisateurs dans la salle d'attente, une bulle de couleur le signale sur le panneau de gauche. Si la salle d'attente et le streaming sont activés, l'utilisateur "Live" sera dans les invitations et il faudra l'accepter afin de pouvoir diffuser en direct sur Peertube.

![](<.gitbook/assets/014_BBB_panneau_droit_attente.png>)

Après avoir cliqué, vous pouvez autoriser ou refuser les utilisateurs en lot (1) ou choisir pour chacun des participants (2).

![](<.gitbook/assets/015_BBB_accepter_user.png>)


## Diffusion en direct et enregistrement d'une visioconférence

**Paramètres du streaming**

Si vous choisissez d'activer le streaming : une Url RMTP et une clé de diffusion vous seront demandées.

![](<.gitbook/assets/016_coche_streaming.png>)

Vous trouverez ces informations, en vous connectant à PeerTube puis en :

1) Cliquant sur **« Publier »**

2) Choississant l'onglet **Aller au direct**

3) Cliquant sur **« Aller au direct »**

    ![](<.gitbook/assets/017_peertube_streaming.png>)

Ensuite dans l'onglet **Paramètres du direct**, il est possible de copier directement l'Url RTMP et la clé de diffusion du direct.

![](<.gitbook/assets/018_peertube_streaming.png>)


**Gestion du streaming**

Après l'ouverture de la salle dans webconférence, la diffusion en direct commence quelques instants après sur Peertube.

Depuis webconférence, à l'aide des boutons « Arrêter le stream » et « Lancer le stream », il est possible de mettre en pause la diffusion en direct tout en gardant la salle de webconférence ouverte.  Il y a un temps de décalage entre le clic sur le bouton et l'arrêt ou la reprise du streaming effective sur Peertube qui est similaire au temps de décalage à l'ouverture du streaming.

![](<.gitbook/assets/019_arreter_streaming.png>)
![](<.gitbook/assets/020_lancer_streaming.png>)


Si la salle d'attente et le streaming sont activés, il faudra accepter l'utilisateur "Live" pour que la diffusion en direct puisse commencer.

La diffusion en direct est automatiquement arrêtée :

* si on ferme la salle : grâce au bouton « Mettre fin à la réunion », "Fermer la salle" ou en fermant l'onglet,

* si on quitte la réunion et qu'un modérateur ne la rejoint pas dans les 2 minutes qui suivent,

* chaque nuit.


**Enregistrement d'une visio-conférence**

Il est possible d'enregistrer une visioconférence en activant le streaming de la salle. En paramétrant la visibilité de votre direct, vous pouvez choisir d'enregistrer seulement la visioconférence (en choississant une visibilité privé) ou de diffuser le direct à un public : dans ces deux cas l'enregistrement est automatique.

A la fermeture de la salle, la diffusion en direct est arrêtée et vous pouvez ensuite retrouver son contenu dans l'onglet, "Ma bibliothèque" puis "Vidéos".

![](<.gitbook/assets/021_enregistrement.png>)