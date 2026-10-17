# ELEMENTA — Pravidla a konvence

## Pravidlo pro instalaci na plochu mobilu (PWA), ikony a zákaz duplicit (§7.11)
Při vytvoření či úpravě funkce instalace aplikace na plochu mobilu je **povinné automaticky navrhnout, vygenerovat a do projektu integrovat kompletní sadu aplikačních ikon i manifest**:
1. **Uložení výhradně ve složce `icons/`:** Všechny ikony patří do podsložky `icons/` (`icon.svg`, `favicon.svg`, `icon-512.png`, `icon-192.png`, `apple-touch-icon.png` 180×180 px pro iOS Safari, `favicon.ico`, `manifest.json` / `manifest.webmanifest`).
2. **Zákaz duplicit v kořeni:** V kořenovém adresáři se **neudržují žádné duplikáty PNG/SVG ikon**. Z grafických assetů smí být v kořeni pouze `favicon.ico` (pro kompatibilitu starých crawlerů a prohlížečů, které nečtou `<link>`) a autoritativní `manifest.webmanifest` / `manifest.json` (odkazující na `icons/...`).
3. **Propojení v HTML a Service Workeru:** V `index.html` a `sw.js` tagy a cache směřují na `icons/...`.
4. **Offline záloha:** Pro zajištění funkčnosti bez serveru se v HTML doporučuje zachovávat inline Data URI záloha pro SVG ikonu.
