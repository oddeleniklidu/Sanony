# Metodika a hranice zjištění

**Šanon VI · Verze 1.0 · 22. listopadu 2026**

## Co porovnáváme

Konkrétní archivní stránky mají různé časy zachycení. Nepředstíráme dvě úplné, stejně rozsáhlé zálohy celého katalogu. Místní statická prezentace a rekonstrukce nejsou původními archivními odpověďmi. Zářijovou rekonstrukci označenou 18. září nelze datovat jako přímý snapshot z tohoto dne.

Rozlišujeme to, co web zveřejnil, vlastní vyjádření osob, odvozenou interpretaci a nezjištěné skutečnosti. Provozní role uvedená vydavatelem není nezávislým ověřením skutečné smlouvy nebo činnosti. Nejednotné formulace nabídky samy neprokazují použití peněz ani úmysl.

## Původ a integrita

Při přípravě byly nově získány veřejné CDX indexy a osm konkrétních archivních odpovědí. SHA-1 otisky všech osmi odpovědí v podobě Base32 odpovídají digestům uvedeným v CDX pro stejné URL a časy.

Sedm odpovědí obsahovalo gzip tělo. Zachovali jsme původní odpověď a vytvořili samostatnou dekomprimovanou HTML kopii pro čtení. U těchto stránek se s CDX porovnávají původní gzip bajty; SHA-256 dekomprimovaného HTML je jiný otisk. U nekomprimované homepage se porovnává přímo HTML. Shoda s indexem ověřuje shodu uchovaných bajtů s evidovaným zachycením, nikoli pravdivost tvrzení vydavatele.

Veřejná příloha `archivni-zaznamy.json` zachovává zdrojové URL, časy UTC, CDX digest a otisky původních i dekomprimovaných odpovědí u čtyř klíčových záznamů. Je to nově sestavený výpis, nikoli původní HTML nebo nezávislé nové časové razítko. Neupravovaný zdroj zůstává v pracovním souboru a lze jej porovnat s archivem.

## Rozsah závěrů

Popis podpory na kategorické stránce vztahujeme k této kategorii. Bez úplných produktových detailů nepřisuzujeme všem výrobkům totožný příslib. Z porovnání dvou verzí podmínek neodvozujeme přesné datum změny ani začátku práce.

Videa citujeme časovanými odkazy a rešeršním shrnutím. Tato edice nezahrnuje novou úplnou zvukovou kontrolu ani audit bankovních a účetních podkladů. Výtěžek, zisk, tržby a přidané dary nepovažujeme za stejný údaj. Právní závěr o klamavé nabídce nebo porušení pravidel z podkladů nevydáváme.

## Veřejné přílohy a licence

`srovnani.csv` je vlastní přehled interpretace a omezení. Přílohy neobsahují přesnou adresu provozovatele, kontakty, údaje zákazníků, cizí skripty nebo celé články. Odkazy na původní stránky nevytvářejí licenci k cizím textům, obrázkům ani videím.

`SHA256SUMS.txt` pokrývá vlastní texty, šablony a přílohy této edice, nikoli sám sebe. Kontrolujte soubory repozitáře, ne HTML sestavené GitHub Pages. Otisky potvrzují shodu bajtů, nikoli pravdivost nebo právní závěr.

[Zpět na šanon](README.md)
