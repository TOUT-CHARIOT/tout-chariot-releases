# FLEET CHARIOT — Android

[Installer FLEET CHARIOT 1.3.8](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.8/FLEET-CHARIOT-1.3.8.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.8)

# FLEET CHARIOT 1.3.8

- Retour de la fenêtre jaune de choix main-d’œuvre interne / externe, avec chargement et déchargement.
- Interne : demande transmise au conducteur avec la course. S’il n’a pas de personnel, il le signale ; le client est notifié et peut commander une main-d’œuvre externe ou annuler le transport.
- Externe : commande séparée, avec son devis, son suivi et les formules Éco, Classic et Premium. Ces formules restent absentes du transport et de la location.
- Suppression des dates de début et de fin dans le formulaire et le récapitulatif du transport. La location conserve ses dates de réservation.
- Main-d’œuvre : début souhaité et fin estimée clairement indicatifs. La mission peut dépasser l’horaire estimé et reste active jusqu’à sa clôture par le prestataire.

Le panneau de transport dépliable, le barème administrable et les visuels FLEET CHARIOT sont conservés. Les devis déjà émis gardent leur montant.

APK ARM64, même identifiant et même signature que la distribution précédente. La clé de signature historique reste à fournir pour une compatibilité avec les installations utilisant l’ancien certificat.

Backend : https://tout-chariot-staging.fly.dev. PI-SPI reste sur le simulateur TGD999 ; les accès bancaires de production restent à fournir. Le fournisseur SMS reste à raccorder ; les numéros autorisés utilisent actuellement 1234.

La livraison publique contient l’APK et ses documents, sans code source.

