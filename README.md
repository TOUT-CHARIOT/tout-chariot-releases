# Tout Chariot — Android

[Installer Tout Chariot 1.3.3](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.3/Tout-Chariot-1.3.3.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.3)

# Tout Chariot 1.3.3

Le prix estimé est à nouveau affiché automatiquement dans le panneau du chariot, à son emplacement habituel. Le prix au kilomètre provient du catalogue du serveur.

Le barème existant reste la règle par défaut : base couvrant la distance incluse, kilomètres supplémentaires, durée et balayage au-delà du seuil applicable. Les montants existants sont conservés. L’administration permet de les modifier et de publier une règle spécifique lorsqu’une prestation nécessite une exception.

Une modification de trajet, formule ou option actualise l’estimation. Un ancien résultat réseau ne remplace pas le prix courant. La demande nationale peut être lancée après confirmation du prix affiché, sans passage par une page de devis supplémentaire.

Le national reste sélectionné par défaut et le chariot se déplie sur l’accueil. Les composants visuels rétablis dans la 1.3.2 sont conservés.

## Installation

APK ARM64 d’environ 42 Mo, adaptée au Pixel 6 Pro et aux téléphones Android récents. La signature de distribution est la même que celle des versions 1.3.1 et 1.3.2. La compatibilité avec l’ancienne signature historique reste conditionnée à la récupération de sa clé privée.

## Raccordements connus

Le backend est hébergé sur https://tout-chariot-staging.fly.dev. PI-SPI reste raccordé au simulateur TGD999 jusqu’à réception des accès de production. Le fournisseur SMS reste à raccorder ; les numéros autorisés utilisent actuellement 1234. Les paramètres commerciaux restent sous le contrôle de l’administration.

Aucun code source n’est joint à cette livraison publique.

