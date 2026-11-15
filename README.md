# Tout Chariot — Android

[Installer Tout Chariot 1.3.1](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/download/v1.3.1/Tout-Chariot-1.3.1.apk)

[Guide et notes de livraison](https://github.com/TOUT-CHARIOT/tout-chariot-releases/releases/tag/v1.3.1)

# Tout Chariot 1.3.1 — Livraison Android

Application connectée au backend hébergé : https://tout-chariot-staging.fly.dev.

Les services nationaux comprennent Transport, Main-d’œuvre et Location. Les services internationaux comprennent Déménagement international et Transport international. Le catalogue, les véhicules et la tarification sont administrables depuis le tableau de bord.

Les parcours de réservation, proposition du délai d’arrivée, confirmation du client, réalisation de la prestation, discussion et notifications sont raccordés au backend. Les comptes prestataires et l’assistance disposent de leurs espaces respectifs.

## Installation

Téléchargez `Tout-Chariot-1.3.1.apk` et autorisez son installation sur Android. Cette APK cible les téléphones **ARM64**, dont le Pixel 6 Pro. Elle exclut les bibliothèques destinées aux anciens appareils ARM 32 bits et aux émulateurs Intel. Le nom affiché est **Tout Chariot**, avec l’identifiant `com.hsi.toutchariot`.

Cette livraison utilise la clé disponible sur le poste de compilation, différente de la clé historique encore attendue. Android peut donc refuser la mise à jour de l’ancienne installation. Ne désinstallez pas l’application existante avant d’avoir vérifié la conservation de vos données avec l’équipe technique. Un appareil sans l’ancienne installation peut recevoir cette livraison directement.

## Raccordements et mise en service

- Les notifications Firebase sont raccordées et ont été vérifiées sur Android.
- PI-SPI utilise actuellement le simulateur TGD999. Les encaissements réels nécessitent les accès et autorisations de production du participant bancaire.
- L’envoi de codes par SMS nécessite un fournisseur de production. Les numéros expressément autorisés disposent actuellement du code 1234 ; leurs utilisateurs définissent leur propre mot de passe.
- L’administration doit valider les tarifs commerciaux, les véhicules et les disponibilités réelles. Le catalogue hébergé contient encore des valeurs de configuration utilisées lors des vérifications.
- La clé de signature historique et la continuité des données de l’ancien environnement restent à finaliser.

Ces points ne doivent pas être interprétés comme des encaissements réels déjà activés ou comme une migration de l’ancien environnement déjà effectuée.

Consultez le guide joint pour les instructions d’utilisation et le document de vérification pour le périmètre des contrôles réalisés.

