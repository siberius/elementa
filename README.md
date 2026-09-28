# ELEMENTA · prostorová mapa prvků

Interaktivní 3D vizualizace periodické soustavy prvků v jediném HTML souboru.
118 prvků · 7 period · 3 protínající se roviny (elektronové bloky s / p / d / f).

![ELEMENTA](https://img.shields.io/badge/118%20prvk%C5%AF-7%20period-blue)
![Licence](https://img.shields.io/badge/licence-MIT-green)
![Bez buildu](https://img.shields.io/badge/build-nen%C3%AD%20t%C5%99eba-lightgrey)

## Co to umí

- **Prostorový model** — tři elipsy sdílejí střed a leží ve vzájemně kolmých
  rovinách; barva určuje periodu, rovina elektronový blok.
- **Detail každého prvku** — značka, protonové číslo, český i anglický název,
  elektronová konfigurace (základní stav), elektrony ve slupkách, fyzikální
  vlastnosti a zdroj dat.
- **Objevování souvislostí** — zvýraznění periody, skupiny / řady a srovnávací
  dvojice (např. La ↔ Ac); vodítka pro konvenci skupiny 3 (Sc–Y–Lu–Lr).
- **Vyhledávání** — podle značky, názvu nebo protonového čísla.
- **Nastavení vzhledu** — barvy podle period / bloků / kategorií, popisky,
  automatické otáčení, průsvitnost pásů, rozestup vrstev, rozložení rovin,
  pohledy zepředu / shora / perspektiva.
- **Čeština / angličtina** — přepínač jazyka v mapě a nastavení.

## Spuštění

Nic se neinstaluje, žádný build:

1. Stáhni nebo naklonuj repozitář.
2. Otevři `index.html` v moderním prohlížeči (dvojklik stačí).
3. Potřebuješ WebGL 2 a hardwarovou akceleraci.

Model i zabudovaná databáze **fungují bez internetu**. Je-li připojení
k dispozici, aplikace se pokusí aktualizovat data prvků online.

## Ovládání

| Akce | Vstup |
|---|---|
| Otočení | tažení myší / prstem |
| Zoom | kolečko / dva prsty, tlačítka + / − |
| Posun | pravé tlačítko / dva prsty |
| Detail prvku | kliknutí / klepnutí na sektor |
| Výchozí pohled | tlačítko domů vlevo dole |

## Data a licence třetích stran

- **Databáze prvků:** [Bowserinator / Periodic-Table-JSON](https://github.com/Bowserinator/Periodic-Table-JSON)
  · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
  Vložená záloha: 118 prvků (28. 9. 2026); online se data aktualizují.
- **3D knihovna:** Three.js + OrbitControls, vložené přímo v HTML · MIT
  (© 2010–2025 three.js authors).
- **Kurikulum / fakta:** [IUPAC – periodická soustava](https://iupac.org/what-we-do/periodic-table-of-elements/).

Elipsy jsou mapou soustavy, nikoli drahami elektronů. Velikosti sektorů ani
vzdálenosti mezi nimi nejsou fyzikální veličinou. U velmi těžkých prvků jsou
některé údaje předpovězené.

## Autor

**Mgr. Luděk Sušický** — biolog, středoškolský a vysokoškolský učitel informatických předmětů

- E-mail: [ludek.susicky@gmail.com](mailto:ludek.susicky@gmail.com)
- X: [@ludeksusicky](https://x.com/ludeksusicky)
- LinkedIn: [Luděk Sušický](https://www.linkedin.com/in/ludek-susicky/)

Aplikace je příkladem SPA (Single Page Application) v jediném HTML souboru.

## Licence

MIT © 2026 Luděk Sušický — viz [LICENSE](LICENSE).
Licence MIT platí pro vlastní kód aplikace. Three.js a OrbitControls mají
vlastní licenci MIT; převzatá databáze zůstává pod CC BY-SA 3.0.
