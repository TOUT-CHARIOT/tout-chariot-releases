# Tout Chariot — Android

[Installer Tout Chariot 1.3.2](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.2/Tout-Chariot-1.3.2.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.2)

# Tout Chariot 1.3.2

Cette version corrige les écarts d’interface et d’interaction de la livraison précédente.

- Le chariot se déplie directement dans l’accueil pour renseigner le trajet.
- Le menu Services affiche le national par défaut et retrouve ses cartes illustrées.
- L’international utilise les illustrations, couleurs, blocs d’adresses et boutons de l’application.
- Le profil retrouve ses lignes d’informations et son panneau d’édition.
- Les missions retrouvent la présentation avec carte et panneau coulissant.
- Le catalogue, les devis, réservations, confirmations, discussions et notifications restent connectés au backend hébergé.

## Installation

APK ARM64 pour les téléphones Android récents, dont le Pixel 6 Pro. Le nom affiché reste **Tout Chariot**. Cette version met à jour la livraison 1.3.1 avec la même signature disponible. La compatibilité avec l’ancienne application signée par la clé historique reste conditionnée à la récupération de cette clé.

## Raccordements restant à finaliser

Les limites déjà communiquées restent inchangées : PI-SPI utilise le simulateur TGD999 jusqu’à réception des accès de production ; les codes SMS nécessitent leur fournisseur ; les numéros expressément autorisés utilisent actuellement 1234. L’administration doit valider les tarifs et disponibilités commerciaux. La clé historique et la continuité des comptes de l’ancien environnement restent à finaliser.

Le backend hébergé est accessible sur https://tout-chariot-staging.fly.dev. Aucun code source n’est joint à cette livraison publique.

