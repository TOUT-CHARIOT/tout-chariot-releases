# FLEET CHARIOT — Android

[Installer FLEET CHARIOT 1.3.7](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.7/FLEET-CHARIOT-1.3.7.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.7)

# FLEET CHARIOT 1.3.7

Les formules **Éco, Classic et Premium** sont désormais réservées exclusivement à la main-d’œuvre. Elles ne sont proposées ni pour le transport, ni pour la location, ni pour le déménagement international.

Un chariot et une main-d’œuvre se commandent séparément, avec deux devis et deux suivis distincts. Le bouton « Oui » dans le panneau du chariot ouvre une demande de main-d’œuvre ; il n’ajoute plus de personnel au prix du chariot. Le prix du chariot s’affiche après le choix des adresses sans imposer de réponse à cette question.

Le barème du chariot reste administrable. La migration reprend les montants de la règle auparavant sélectionnée par défaut ; les formules de personnel restent configurées séparément. Les devis déjà émis conservent leur prix.

Le panneau jaune dépliable, le choix Transport / Location et les visuels FLEET CHARIOT sont conservés.

## Installation et raccordements

APK ARM64 d’environ 43 Mo. Même identifiant Android et même signature de distribution que les versions 1.3.1 à 1.3.6. La compatibilité avec une ancienne installation signée par le certificat historique nécessite toujours sa clé privée originale.

Backend : https://tout-chariot-staging.fly.dev. PI-SPI reste sur le simulateur TGD999 ; les accès bancaires de production restent à fournir. Le fournisseur SMS reste à raccorder ; les numéros autorisés utilisent actuellement 1234.

La livraison publique contient l’APK et ses documents, sans code source.

