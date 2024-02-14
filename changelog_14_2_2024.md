**Changelog: 14.2 - 2024 - Novinky / DevLog**
Další novinky z vývoje serveru.
V tomto seznamu změn se vám pokusím napsat změny které jsem provedl během týdne.

**Mise:**
- Jelikož questy / mise potřebovali nějaké postavy aby to zapadalo do RPG světa tak jsem vytvořil custom armor stand postavy.
- Které nyní mají vlastní obydlí a zázamí všechny postavy obsahující questy jsem zařadil na warp příroda.

- Opravoval jsem některé mise které nebyli zcela validní a správně vytvořené týkalo se to hlavně speciálních misí.
- Speciálních misí je v tuto dobu vytvořeno kolem 58 úkolů mezi nimi se nachází i denní úlohy který mají cooldown na 1 den.
- V plánu jsou i výzvy třebaz splň quest / misi do určitého času.

- Speciální mise obsahují převážně mise odvícející se od cestování, hlasování / získání VIP a nebo výher v loterii či nákupech v shopu atd.
- Prostě mise týkající se nějakých zvláštních událostí, jako třebaz vyhraj voteparty nebo hlasuj jako poslední ve vote party dosáhni určitého počtu kreditů premiové měny.

**Shop a GUI:**
- Proběhla i oprava shopu v GUI / menu, nešlo nakupovat z nějakého důvodu jsem udělal někde během vývoje chybu a nešli kupovat itemy ale odečítali se jen peníze a předměty se hráči nedostali do inventáře.
- Zásadní chyba v tomto ohledu byla opravena, dále jsem musel udělat menší migraci / konfigurace jelikož se snažím udělat jednotný nástroj který by mi do jisté míry ulehčil tvorbu menu shopů nebo custom menu.

**Bossové a známé chyby**
Bossové někdy se setkávám s menšími artefakty / chybmi které spawnují hlavního bosee až po 22 hodině a je stále naživu, to ale přisuzuji stálému restartování během vývoje.
Kdy scheduler nemůže mobku smazat když už event skončil.

**Novinky:**
- Přidal jsem WarpSigns, tyto cedulky slouží pro teleportování po kliknutí.
- Přidal jsem HomeGUI / seznam domovů se již ukazuje jenom v menu alias gui, tedy je to přehlednější než třebaz pomocí chat výpisu.
- V homegui si můžete najít na který váš warp se chcete portnout, chybí ještě interaktivní nastavení ikony, ikona se momentálně nastavuje pomocí příkazu /sethomeicon <domov> <icon>.
- Ikony jsou materiály z minecraftu však ale jsou brány z povoleného seznamu.
- Na domovy se stále dá teleportovat i pomocí příkazu /home <domov> nebo pomocí již zmíněného GUI.
- Domovy ještě obdrží nastavení defaultního domova.

- Tento výpis by mohl být i pro Warpy / Chtěl bych menu s warpy udělat více interaktivní kde by se zobrazovali globální warpy ale také i vaše warpy v odděleném menu.

**Další Idea a Návrhy**
- Prohlížel jsem custom mapy od authorů kteří tvoří krásné mapy v MCEditu a některé z nich jsou free volně ke stažení, 
- našel jsem zde i krásné mapy vhodné pro lokace, napadlo mě třebaz jednu mapu využít jako hlavní mapu něco jako typhon nebo lokaci kde by byli bossové a mobky:
- idea pro mobky je asi taková že by mohlo kolem cesta a mimo cesty se spawnovat mobové s levely až 5 až 15 a měli by nastavení lehké obtížnosti s cílem hlavně hráče nalákat na to hrát.
- samozřejmě bylo by třeba aby taková mapa měla i své vlastní itemy, pro custom mobky z mythicmobs, a samozřejmě itemy pro bossy.
- Přístup do lokace / typhonu nazveme to zatím tak by mohl být buď garantován tak že by se do světa dalo dostat buď od nějakého levelu nebo přes vstupenku do světa čímž by se snížil rychlý postup ve hře.

- Návrh týkající se vstupenek, jelikož momentálně hráči mohou získat vstupenky prakticky buď vytočením z magického boxu / crate a nebo zabitím bosse. 
- Aktuálně mi příjde po úvaze zda by nebylo vhodné to udělat tak že by se vstupenky do různých lokací / dimenzí.
- se dal získat jedině tak že by hráč musel získat potřebné itemy jako tomu bylo na Dubcatu.
- Že by hráč musel potřebné předměty nejdříve nahrát / získat. 
- Čímž by se hráč musel více snažit si nasbírat dostatek předmětů pro výměnu za vstupenku do lokace.
