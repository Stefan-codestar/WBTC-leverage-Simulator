# wBTC-Leverage-Simulator (Aave v3/v4 & Fluid)

Interaktives HTML-Dashboard zum Durchspielen von wBTC-Leverage-Strategien
(Looping über USDC-Kredite) auf **Aave v3**, **Aave v4 (Hub & Spoke)** und
**Fluid** (zwei getrennte Vaults).

## Nutzung

`aave-wbtc-leverage-simulator.html` im Browser öffnen — keine Installation,
kein Server, keine externen Abhängigkeiten.

## Funktionen

- Loop-für-Loop-Simulation mit LTV-, Zins- und Laufzeit-Parametern
  (Defaults kalibriert an realen DeFi-Saver-Marktdaten)
- Liquidationspreis pro Loop, Preispfad auf Ziel-Endpreis fixierbar
- Preisziel-Rechner für Verdopplung/Verdreifachung des Einsatzes
- Depeg-Schock (wBTC/cbBTC-Basis) als zeitlicher Schock modellierbar
- Optional: erster USDC-Loop als exakter 2x-Hebel

## Herkunft

Ausgegliedert aus dem Haushaltsbuch-Repo; die Commit-Historie der
Entwicklung wurde beim Umzug erhalten.
