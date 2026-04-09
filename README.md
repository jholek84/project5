# Analýza cestovního ruchu ČR (2023–2024) 

## Projekt v rámci Datové Akademie
Tento projekt je zaměřen na vizualizaci a analýzu dat cestovního ruchu v České republice v letech 2023 až 2024. Cílem bylo vytvořit interaktivní report v Power BI, který přehledně interpretuje data o počtu cest, přenocování a nákladech účastníků cestovního ruchu.

## O projektu Power BI
Projekt se skládá ze **tří interaktivních stránek**, které pokrývají různé aspekty trhu:

1. **Celkový přehled:** Hlavní ekonomické ukazatele, meziroční srovnání a struktura trhu podle pohlaví a účelu cest.
2. **Destinace a ubytování:** Podrobná analýza domácího vs. zahraničního cestovního ruchu a preferencí v ubytovacích zařízeních.
3. **Analýza nákladovosti:** Pokročilý pohled na průměrné výdaje na jednu cestu a efektivitu cestování pomocí rozptylových grafů.

## Použité technologie a techniky
* **Power BI Desktop:** Tvorba reportu a vizualizací.
* **Power Query:** Čištění dat, řešení problémů s datovými typy (převod textu na desetinná čísla pomocí národního prostředí) a ošetření duplicitních součtových řádků ("Celkem").
* **DAX (Data Analysis Expressions):** Vytvoření vlastních měr (Measures) pro dynamické výpočty (např. *Průměrná cena cesty*, *Celkové náklady*).
* **Interaktivní prvky:** Navigátor stránek, průřezy (slicery) ve stylu dlaždic, interaktivní legendy a podmíněné formátování v maticových tabulkách.

## Klíčová zjištění
* Report správně odděluje souhrnná data ("Celkem") od detailních podkategorií, což umožňuje přesnou analýzu bez zkreslení.
* Pomocí grafů byly identifikovány segmenty s nejvyššími průměrnými náklady.
* Byla zajištěna plná srozumitelnost díky nahrazení číselných kódů z původního datasetu textovými popisky.

## Soubory v repozitáři
* `CRU06AGEN.csv`: Zdrojový datový soubor.
* `Analýza_cestovního_ruchu_za_roky_2023_-_2024.pbix`: Finální soubor Power BI reportu.
* `README.md`: Průvodní dopis a podrobný popis metodiky.
