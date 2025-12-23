# Kotilatauksen ajastin

Kevyt Progressive Web App (PWA) auton kotilatauksen ajastuksen arviointiin.

Sovellus laskee, kuinka pitkän ajan auton akkua tulee ladata haluttuun
varaustasoon asti käyttäen yksinkertaista sääntöä:

- **1 % = 3 minuuttia**  
- **100 % = ei ajastusta** (lataus päättyy automaattisesti)

👉 Käyttö suoraan selaimessa tai kotinäytölle asennettuna PWA:na.

## Käyttö
1. Syötä auton akun **nykyinen varaustila (%)**
2. Valitse **tavoitevaraustaso** (pikapainikkeet: 80 %, 85 %, 90 %, Täyteen)
3. Sovellus näyttää:
   - **Aseta ajastin: X h Y min**
   - tai ilmoittaa, ettei ajastusta tarvita (100 %)

## PWA-ominaisuudet
- Asennettavissa kotinäytölle (iOS / Android)
- Toimii offline-tilassa (Service Worker)
- Päivittyy automaattisesti versionumeron avulla

## Tekninen toteutus
- HTML + CSS + JavaScript
- GitHub Pages
- Web App Manifest
- Service Worker (cache + offline)

## Demo
https://petris66.github.io/homecharger_timer/

## Jatkokehitysideoita
- Valmis klo HH:MM -aika
- Viimeisimmän syötön muistaminen
- Yölataus-tila

