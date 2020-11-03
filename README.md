# Générateur de certificat de déplacement

## Ce qui a été rajouté

- Bouton sauvegarde pour pouvoir générer le formulaire plus rapidement
- Heure de sortie aléatoire entre 15 et 40 minutes avant l'heure de création 
- PDF & QR Code correspondent à l'heure de sortie, pas de création

🤯 Attention ! A ne pas utiliser autour de minuit, la date pourrait être fausse 🤯

## Développer

### Installer le projet

```console
git clone https://github.com/victorazevedo-me/attestation-deplacement-automatique
cd attestation-deplacement-automatique
npm i
npm start
```

### Générer le code de production pour tester que le build fonctionne en entier

```console
npm run build:dev
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
-   [Font Awesome](https://fontawesome.com/license)
