# Šablona nového šanonu Vydřina archivu

Výchozí struktura vychází z [šanonu Red Face](../P%C5%99%C3%ADpad%20Red%20Face/README.md):
**O co jde / Co jsme zjistili / Co ještě nevíme / Podívejte se sami**.
Red Face byl při vytvoření šablony prázdný; šablona nepřebírá žádné jeho zjištění.
Výchozí commit: `90d3962b921afe971033fee4ce76eb06fa05e6a8` (28. 11. 2026).

## Použití

1. Zkopírujte obsah složky `sanon` do nové složky případu. Existující případy
   ani jejich URL tímto postupem neměňte.
2. Vyplňte název, římské číslo šanonu a stav v `index.html`; text v `README.md`.
   Přidělené číslo ověřte proti aktuálnímu přehledu. Číslo Red Face nepřebírejte.
3. Nahraďte všechny značky `DOPLNIT`. Používejte jen skutečné zdroje.
   Nezpracovanou část označte „Podklady se připravují“; nevytvářejte zjištění
   pouze pro zaplnění šablony. Předběžné posouzení nenahrazuje ověření zdrojů.
4. Nejprve připravte soukromý návrh. Před veřejným PR zkontrolujte údaje,
   přílohy, historii změn i Git identitu; veřejný PR je už zveřejnění obsahu.
5. Ověřte pravidla níže, sestavení webu a místní odkazy. Přidání do hlavního
   přehledu a publikace jsou samostatné redakční rozhodnutí.

Složka `templates` je vyloučena z webu. Vzor obsahuje relativní odkazy určené
pro novou složku případu v kořeni repozitáře. Při práci uvnitř šablony mohou
GitHub náhledy těchto cílových odkazů působit jako neexistující.

## Redakční pravidla

- Dodržujte [pravidla projektu](../o-archivu.md) a [vizuální pravidla](../docs/vizual-vydry.md).
  Používejte plný název Oddělení klidu a římské číslování šanonů.
- Rozlišujte doložené zjištění, interpretaci a otevřenou otázku. Podezření,
  anonymní tvrzení nebo výrok účastníka není prokázaná skutečnost.
- Rozlišujte skutkové tvrzení a názor. Satiru, ironii, citace a možnou chybu
  přepisu posuzujte s kontextem. Citující nemusí být původcem ani podporovatelem výroku.
- Každé zjištění opatřete přesným zdrojem, datem zachycení a lokátorem.
  Uveďte původ dodaných podkladů a hranice nezávislého ověření.
- Popište alternativní interpretaci a omezení výběru. Výběrový soubor není
  automaticky reprezentativní. Nevyvozujte koordinaci pouze z časové shody.
- Nevytvářejte občanskou totožnost anonymního účtu z podobného jména či stylu.
  Uveřejněte pouze údaje přiměřené doložení konkrétního veřejně relevantního tématu.
- Zvlášť prověřte soukromé kontakty, adresy, děti, zdravotní a jiné citlivé
  údaje. Redigujte je i v přílohách, náhledech, metadatech a názvech souborů.
- Nezveřejňujte klíče, přihlašovací údaje, jméno ani místní cesty autora podkladů.
- Nezveřejňujte interní osobní skóre, automatická obvinění, seznamy žalovaných
  ani závěry o vině. Veřejný text musí vycházet z individuálně ověřených podkladů.
- Veřejné opravy zaznamenejte datem a důvodem; citlivé podněty směrujte na
  kontakt uvedený na stránce O Vydřině archivu, nikoli do veřejného issue.

## Kontrola návrhu

- Každý podstatný závěr má dohledatelný zdroj a zachovaný kontext.
- Text uvádí, co data dokazují a co nedokazují; nevyplněná pole jsou odstraněna.
- Citace je ověřena proti originálu; automatické titulky nejsou vydávány za jistý přepis.
- Byla posouzena přiměřenost publikace a soukromí, včetně všech příloh.
- Je zaznamenáno, kdo návrh přezkoumal, kdy a podle jaké verze pravidel
  (v soukromé redakční evidenci, bez povinného zveřejnění identity).
- Veřejná verze byla samostatně schválena po kontrole textu a všech příloh.

Volitelné přílohy `ZDROJE.md`, `METODIKA.md`, `CASOVA-OSA.md` a `OPRAVY.md`
přidejte podle rozsahu případu po vzoru existujících šanonů. Pokud mají vlastní
HTML obálky, přidejte jejich Markdown zdroje do `exclude` v `_config.yml`,
jak je v repozitáři obvyklé. Nepřidávejte odkazy na neexistující přílohy.
