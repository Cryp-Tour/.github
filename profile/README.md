# Cryptour 💵
Cryptour ist ein Tourenportal, welches es den Erstellern der Touren erlaubt, am Verkauf der Touren beteiligt zu werden. Hierzu wird die Ethereum Blockchain  mit einem [Automated-Marketmaker](https://academy.binance.com/en/articles/what-is-an-automated-market-maker-amm) verwendet.

## Anleitung zur lokalen Installation ⚒️
1. Clonen der Repositories [Cryp-Tour/server](https://github.com/Cryp-Tour/server) und [Cryp-Tour/website](https://github.com/Cryp-Tour/website) in einen Ordner
2. Im Website Repository in `js/config.js` die Base-URL auf `http://localhost:3030` setzen
3. Herunterladen der Docker Compose Datei von [hier](https://github.com/Cryp-Tour/.github/blob/main/docker-compose.yml)
4. Ausführen von `docker-compose up`
5. Neu erstellter `data` Ordner mit `chmod` rekursiv auf alle Dateien die Rechte 777 vergeben (`sudo chmod -R 777 data`)
6. `docker-compose up` erneut ausführen
7. Cryptour über `http://localhost:8080` aufrufen

## Wichtige Dokumente 📜
 - [SRS](https://github.com/Cryp-Tour/dokumentation/blob/main/allgemein/Software%20Requirements%20Specification.pdf)
 - [Features](https://github.com/Cryp-Tour/dokumentation/blob/main/allgemein/Features.pdf)
 - [Dokumentation](https://github.com/Cryp-Tour/dokumentation/blob/main/README.md)

## Wichtige Links 🔗
 - [Allgemeines Board](https://github.com/orgs/Cryp-Tour/projects/1)
 - [Server Board](https://github.com/Cryp-Tour/server/projects/1)
 - [Website Board](https://github.com/Cryp-Tour/website/projects/1)
 - [Dokumentations Board](https://github.com/Cryp-Tour/dokumentation/projects/1)
