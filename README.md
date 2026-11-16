# Tout Chariot — Android

[Installer Tout Chariot 1.3.4](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.4/Tout-Chariot-1.3.4.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.4)

# Tout Chariot 1.3.4

Les trois visuels d’accueil transmis par courriel sont désormais servis par le backend. Ils remplacent uniquement les trois images génériques des annonces initiales ; les campagnes réelles et les annonces modifiées par l’administration sont préservées. Les visuels de secours de l’application utilisent également le backend.

Le chariot reste dépliable sur l’accueil, le national reste sélectionné par défaut et le prix estimé reste affiché automatiquement à son emplacement habituel. Le barème existant est conservé et modifiable dans l’administration, avec possibilité de règle spécifique.

## Installation

APK ARM64 d’environ 42 Mo pour les téléphones Android récents. Même signature de distribution que les versions 1.3.1 à 1.3.3, avec un numéro de version supérieur. La mise à jour d’une ancienne installation utilisant la signature historique nécessite toujours sa clé privée originale.

## Raccordements connus

Backend : https://tout-chariot-staging.fly.dev. PI-SPI utilise encore le simulateur TGD999 dans l’attente des accès de production. Le fournisseur SMS reste à raccorder ; les numéros autorisés utilisent actuellement 1234. Les paramètres commerciaux se règlent depuis l’administration.

La livraison publique contient uniquement l’APK et ses documents, sans code source.

