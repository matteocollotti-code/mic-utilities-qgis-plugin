# MIC - Utilities · repository QGIS

Repository di distribuzione del plugin QGIS **MIC - Utilities** (versione
**0.40.0**). Contiene solo il plugin installabile: `plugins.xml` e lo zip.

## Installazione da QGIS (una volta sola)

1. QGIS → **Plugin → Gestisci e installa plugin… → Impostazioni**.
2. Spunta **Mostra anche i plugin sperimentali**.
3. Premi **Aggiungi…**, scrivi un nome (es. `MIC`) e come URL:

   ```
   https://raw.githubusercontent.com/matteocollotti-code/mic-utilities-qgis-plugin/main/plugins.xml
   ```

   poi **OK**.
4. Nella scheda **Tutti** cerca **MIC - Utilities** e premi **Installa plugin**.
5. Apri il pannello da **Vettore → MIC - Utilities → MIC - Utilities**.

Quando esce una nuova versione QGIS la segnala nella scheda **Aggiornabili**.

## Requisiti

QGIS 3.22 o superiore; nel Python di QGIS `pandas`, `requests` e `matplotlib`
(verifica in *Plugin → Console Python*: `import pandas, requests, matplotlib`).

## Licenza

Copyright (C) 2026 Matteo Collotti. GNU GPL versione 2 o successiva (file
`LICENSE` nello zip). Il logo MIC Hub è un marchio di MIC Hub e non è coperto
dalla GPL. Le reti scaricate con *Rete da OSM* sono dati
© OpenStreetMap contributors (ODbL).
