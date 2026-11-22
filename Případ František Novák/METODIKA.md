# Metodika a hranice zjištění

**Šanon I · Verze 1.0 · 21. listopadu 2026**

## Význam označení

- **Doložený údaj stránky:** například uvedené jméno. Nezaručuje skutečné autorství ani pravdivost článku.
- **Vyjádření osoby:** co dotyčný uvedl; není automaticky nezávisle ověřeným popisem události.
- **Interpretace:** odvozený závěr s možnými alternativami.
- **Hypotéza:** možnost bez rozhodujícího důkazu.
- **Nezjištěno:** podklady otázku nerozhodly. Nenalezení důkazu není důkaz neexistence.

## Rozsah a historický stav

Šanon vychází ze srpnového sběru a pozdějších rešerší do listopadu 2026. Datum sestavení veřejného balíčku není datem pořízení všech zdrojů. Živé odkazy se mohou měnit nebo být nedostupné.

Původní tematický průchod veřejné sitemap Top-Fight hledal témata spojená s Adélou Pulcovou, Terezou Šulganovou, Cute4You, Vladěnou, Majzlíkem a insolvencí. Zaznamenal 111 odpovídajících URL. Dochovaná tabulka má 41 článků s vybranými autorskými kombinacemi. Vedle Nováka a Niky Glosy zahrnuje kombinaci Daniel Koliba, Nika Glosa.

Nejde o úplný export webu, reprezentativní vzorek redakce ani seznam všech Novákových textů. Náhodné výskyty hledaných slov mohou zasáhnout i jiné téma. Čísla se vztahují výhradně k tomuto souboru.

`clanky.csv` přebírá URL, titulky, autorské údaje, data a ID videí. Titulky identifikují zdroje; nepřebíráme jejich obvinění jako vlastní zjištění. `video-clanek.csv` má 20 vazeb a 19 unikátních videí. Jedenáct videí VLADĚNAplus se objevuje ve dvanácti řádcích.

Širší párování Trending MMA z původního chatu zde nepoužíváme jako hlavní kvantitativní důkaz. Pochází z odlišného souboru a jeho počty se s tímto exportem nesmějí zaměňovat.

## Časy a úpravy

CSV zachovává původní hodnoty a přidává UTC a Europe/Prague. Odstup je čas článku minus čas videa. Záporná hodnota neprokazuje přístup k videu před zveřejněním.

Například `2026-06-14T23:28:00Z` znamená **15. června 2026 v 01:28 SELČ**, nikoli 14. června českého času. Čas článku uvedený jen na celé minuty není přesný na sekundy, i když technický zápis končí `:00`.

Metadata může redakce změnit a video může být vloženo dodatečně. U dubnové dvojice počítáme 172 sekund z uložených hodnot, veřejně ale píšeme „přibližně tři minuty“. První verzi článku nemáme. Výpočet rychlosti psaní proto nedokazuje skutečný pracovní postup.

## Původ a integrita výpisů

`zmena-autorstvi.json` je nově vytvořený výpis vybraných údajů ze dvou uložených HTML. **Není původním HTML ani dobovým screenshotem.** Obsahuje původ zdroje, krátký výpis autorství a SHA-256 zdrojového souboru. Archivní WARC/HTTP záznam a samostatné HTML jsou jiné soubory a mají jiné hashe. Také různá stažení živé stránky mohou mít odlišné bajty kvůli dynamickým prvkům.

`puvod-dat.json` eviduje hashe tabulek použitých k sestavení veřejných exportů. Původní soubory mohou obsahovat lokální cesty, proto je nepřebíráme celé. Hash nepublikovaného zdroje umožňuje kontrolu proti tomuto zdroji, pokud je později dostupný; sám neumožňuje jeho nezávislou rekonstrukci.

`SHA256SUMS.txt` pokrývá veřejné textové a datové přílohy včetně hlavního textu. Manifest nehashuje sám sebe. Hash dokládá shodu bajtů této edice, nikoli pravdivost tvrzení nebo nezávislé časové razítko.

Kontrolní součty se vztahují ke zdrojovým souborům v repozitáři GitHub. GitHub Pages z HTML šablon sestavuje výsledné stránky; jejich bajty se od zdrojových šablon liší. Pro kontrolu šablon a Markdownu použijte soubory stažené z repozitáře, nikoli HTML uložené z prohlížeče. Datové přílohy se při sestavení nepřevádějí.

## Vyjádření, soukromí a licence

Video pasáže shrnujeme vlastními slovy a odkazujeme s časem. Pracovní přepisy a automatické titulky jsou lokátorem; pro doslovnou citaci je rozhodující původní zvuk. Balíček neobsahuje kopii videa.

Nezveřejňujeme screenshoty neveřejné facebookové skupiny, soukromé komentáře, kontakty, adresy, místní cesty ani celé cizí články. Závěry založené jen na neveřejných přílohách zde nevydáváme za samostatně veřejně ověřené důkazy. Vynecháváme profesní dohady o jmenovkyních a subjektivní číselné odhady pravděpodobnosti z chatu.

Vlastní shrnutí a sestavené tabulky jsou součástí archivu. Licence repozitáře se nevztahuje na cizí články, fotografie či videa dostupné přes odkazy. Názvy zdrojů, krátké výpisy a metadata nepředstavují licenci k původním dílům.

[Zpět na šanon](README.md)
