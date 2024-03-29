## Changelog: 27.2 - 2024 - Novinky / DevLog

### Seznam změn:

<div align="center">
<img src="https://github.com/NeverLandServer/Changelogs/assets/9441083/30d13519-8a9f-4167-bea7-01c97538fffc" height="400">
</div>

# Otevření serveru
Již brzy se opravdu server otevře veřejnosti beta testování proběhne po víkendu. Cca v Úterý **05.03 2024**.
Doufám že se vám server bude líbit a že se na něm budete bavit, především server stále poběží v beta verzi buď to shovívaví.
Všechny případné chyby prosím nahlaste kdyby něco nefungovalo děkuji.

#### Novinky
- Přidány nové mise
- Některé mise obsahují nově boss bar progress který se ukáže v okamžiku že provádíte nějaký progress.
- Byli přidány nové NPC, které obsahují mise.
- Přidán příkaz /whois <jméno> - Tento příkaz dokáže zjistit informace o hráči i jeho aktuální IP a Zemi.
- Přidána možnost udělat trade s kredity, podařilo se mi napojit credity na API TradeSystemu a nyní je již tato možnost aktivní.

#### Aktualizace
- Proběhla kompletní změna kódu ekonomiky v shop sekci.
  - Kód shopu a credit shopu obsahoval hodně velký nedostatek ekonomické nádstavby díky které se hodně opakoval kód.
  - Bylo proto evidentní že se ukázal vývojový dluh.
  - Více méně teď je kód již efektivní.
- Proběhla aktualizace ArcaStats, collector shromažduje statistiky hráčů.
  - V minulosti byl kód strukturován zbytečně složitě, a mohl by v následku většího náporu zbytečně vytěžovat server.
  - Proto jsem byl nucen předělat kód, pro lepší správu paměti a cache.
- Proběhla aktualizace pluginu k misím, díky této aktualizaci mohu přidávat další a další mise.
  - Kompletně se změnila část kódu díky které se zlepšila stabilita, a samozřejmostí jsou další funkce pro tvorbu misí a nové možnosti.

#### Opravy
- Byli opraveny chyby v misích, popisky překlady atd odměny.
  - Popisky úloh obsahovali zavádějící informace.
  - Odměny u pár misí neseděli.
- Proběhla oprava některých starých částí kódu a momentálně by mohla být zátěž i nižší.
  - Co se týká hlavně paměti a jejího využití v hlavním pluginu MagentaPro.
