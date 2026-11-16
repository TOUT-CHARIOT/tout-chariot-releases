# FLEET CHARIOT — Android

[Installer FLEET CHARIOT 1.3.5](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.5/FLEET-CHARIOT-1.3.5.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.5)

# FLEET CHARIOT 1.3.5

Le nom affiché de l’application devient **FLEET CHARIOT**. L’identifiant Android et la signature de distribution restent identiques à ceux de la 1.3.4 pour permettre sa mise à jour.

L’accueil conserve ses composants visuels et le panneau jaune dépliable. Seul l’en-tête du chariot ouvre ou ferme le panneau : la saisie à l’intérieur ne le replie plus. Le prix estimé et le barème existant sont conservés.

Un menu déroulant sépare Transport et Location. Les types d’engins sont classés côté serveur et modifiables dans l’administration. Cargo et semi-remorque sont classés en transport ; plateau, grue et pelleteuse en location. La location utilise une période et les disponibilités du véhicule, sans destination ni aller-retour de transport. Le serveur refuse les nouveaux devis dont le type d’engin ne correspond pas au service.

Les trois bannières reçues par courriel restent servies par le backend. Les illustrations et logos intégrés à ces fichiers validés ne sont pas retouchés.

## Installation et raccordements

APK ARM64 d’environ 42 Mo. Même signature que les versions 1.3.1 à 1.3.4. La compatibilité avec une ancienne installation signée par le certificat historique nécessite toujours sa clé privée originale.

Backend hébergé : https://tout-chariot-staging.fly.dev. PI-SPI reste sur le simulateur TGD999 ; les accès bancaires de production restent à fournir. Le fournisseur SMS reste à raccorder ; les numéros autorisés utilisent actuellement 1234. Les véhicules disponibles et les paramètres commerciaux sont administrables.

La livraison publique contient l’APK et ses documents, sans code source.

