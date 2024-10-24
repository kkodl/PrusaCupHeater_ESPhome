# PrusaCupHeater_ESPhome
How to set up PrusaCupHeater in ESPhome environment

Puvodní projekt je zde: https://github.com/MartinDejmal/PrusaCupHeater

Další popis pak zde: https://chiptron.cz/news.php?readmore=1546

Marty - KutilDomácí https://twitter.com/KutilDomaci, autor myšlenky a původního projektu používá k řízení Tasmotu.
Pro "team ESPhome" najdete zde jednoduchý yaml soubor pro nastavení zařízení v rámci ESPhome.

Rychlý postup, který se mi osvědčil:

- V ESPhome založím nové zařízení se správnými WiFi údaji (aby se automaticky vygenerovaly klíče)
- Nahraju poprvé do HW přes kabel
- Zařízení se musí připojit k WiFi a je vidět v ESPhome
- Zedituji v ESPhome definiční soubor zařízení podle zde přiloženého vzoru
- Nahraju ho již OTA do HW

Dále je třeba v Home Assistentu zmodifikovat soubor configuration.yaml a doplnit do něj generický termostat - viz druhý soubor zde.

V sekci obrázky, pak najdete jak to celé vypadá.
