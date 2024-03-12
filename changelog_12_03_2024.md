## Changelog: 12.3 - 2024 - Novinky / DevLog

### Seznam změn:

<div align="center">
<img src="https://github.com/NeverLandServer/Changelogs/assets/9441083/30d13519-8a9f-4167-bea7-01c97538fffc" height="400">
</div>

#### Novinky
- Přidán stránkovací hologram pro ekonomiku, zobrazuje nyní žebříček normální ekonomiky a kreditů.
  - Tento hologram momentálně zobrazuje také váš aktuální stav částky vašeho účtu.
- Přidán hologram se sociálními sítěmi.
- Přidán animovaný hologram se statistiky o otevřených crates/magic boxech.
- Přidán příkaz /r, /reply <zpráva>
  - Hráč nyní může rychle odpovídat na příchozí zprávy od hráčů.

#### Aktualizace
- Aktualizace pluginů, Aukce a mise prodělali další aktualizace a opravy.
- Aktualizace hlavního pluginu a dalších drobností.
  - Hlavní plugin Magenta byl optimalizován a proběhli rozsáhlé opravy a vylepšení.
  - Proběhlo vylepšení kódu při výpisu novinek v action baru.
- Aktualizace StatsCollectoru, stats collector byl aktualizován a vylepšen.
  - Byla vylepšená aktuální optimalizace a teď by měl collector pracovat ještě více spolehlivě.
- Aktualizace pluginu DiscordBota byli aktualizovány knihovny a další drobnosti.
- Aktualizace pluginu pro Ekonomiku a Kreditní měny.
  - Formátování částky byla chybná proto byla potřeba aktualizace.

#### Opravy
- Byli opravena speciální mise 59, a další, chybou formátování mise nepřipisovala odměnu.
- Proběhla oprava části kódu v Ekonomickém pluginu a Kreditním pluginu.
  - Část formátování byla chybná a zobrazovala špatné formátování, zůstatku účtu.
  - Byli opravené také další menší drobnosti, které není potřeba zmiňovat.
- V Hlavním pluginu, proběhla rozsáhlá oprava v částech kódu kde by mohlo docházet k memory leaku a poklesu TPS.
  - Byla opravena chyba při příkazu /msg kdy nepřišla zpráva cílovému hráči.
    - Chyba byla způsobena chybnou cestou ke konfiguraci zvuku při zprávě.
  - Proběhla optimalizace správy paměťi a vše by mělo fungovat dobře.
