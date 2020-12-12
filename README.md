# Générateur de certificat de déplacement

## Ce qui a été rajouté

-   Bouton sauvegarde pour pouvoir générer le formulaire plus rapidement
-   Champ heure de sortie facilement accessible avec -25 minutes par défaut
-   PDF & QR Code correspondent à l'heure & date de sortie, pas de création
-   La date réduit d'un jour si l'heure automatique passe de 00h à 23h
-   Avertissement "Attention à la date de sortie !" pendant la nuit

## Ce qui a été modifié

-   Raisons de sortie raccourcis
-   Texte légal & anticovid supprimé
-   Page visuellement allégé

## Développer

### Installer le projet

```console
git clone https://github.com/victorazevedo-me/attestation-deplacement-automatique
cd attestation-deplacement-automatique
npm i
npm start
```

### Tester le code de production en local

```console
npx serve dist
```

Et visiter http://localhost:5000  
Le code à déployer sera le contenu du dossier `dist`

## Crédits

Ce projet a été réalisé à partir d'un fork du dépôt [attestation-deplacement-derogatoire-q4-2020](https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020) par LAB-MI, lui-même réalisé à partir d'un fork du dépôt [deplacement-covid-19](https://github.com/nesk/deplacement-covid-19), lui-même réalisé à partir d'un fork du dépôt [covid-19-certificate](https://github.com/nesk/covid-19-certificate) de [Johann Pardanaud](https://github.com/nesk).

Les projets open source suivants ont été utilisés pour le développement de ce
service :

-   [PDF-LIB](https://pdf-lib.js.org/)
-   [qrcode](https://github.com/soldair/node-qrcode)
-   [Bootstrap](https://getbootstrap.com/)
