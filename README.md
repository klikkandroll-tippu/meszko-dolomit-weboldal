# Mészkő és Dolomit Kft. – bemutató weboldal
Statikus, függőség nélküli HTML/CSS/JS oldal. GitHub repository gyökerébe tölthető a mappa tartalma. Vercel: Other preset, build command nincs, output directory `.`.

Helyi előnézet: python3 -m http.server 8000

Képcsere: az images.js fájlban állíthatók a nyitóképek, képfeliratok, képkivágások és bányakártyák képei. Az assets/ könyvtárban az azonos nevű fájl is cserélhető. A content.json a szövegek és képek áttekintő adatfájlja; módosítása önmagában nem frissíti az oldalt.

A bemutató noindex állapotban van. Élesítés előtt az index.html robots meta, robots.txt és vercel.json X-Robots-Tag feloldandó, saját domain alapján canonical URL és sitemap.xml készítendő. A hivatalos jogi cégadatok, a bányák aktuális státusza és a Díszkő Trend webcíme megerősítendő.

Valós képek: Polgárdi, Kőszárhegy, Mány, Székesfehérvár, Felsőcsatár ügyfél Drive mappáiból. A többi bánya kártyája színes anyagpanellel jelenik meg; más bánya képe nem helyettesíti a sajátját.

Mini PRD: cél imázs és tájékoztatás; input ügyfél Google Dokumentum és saját képek; output mobilbarát egyoldalas oldal; architektúra statikus frontend, nincs backend vagy személyesadat-gyűjtés; UX teljes képernyős szüneteltethető slideshow és független details kártyák; fallback JS nélkül teljes tartalom és nyitható kártyák; képoptimalizálás WebP; elfogadás mobilon nincs túlcsordulás, működő menü és kártyák, tel/mailto linkek, csökkentett mozgás támogatása.
