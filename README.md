# CANEA Pattern Mirror

En liten innovations-prototyp som testar en idé: om konsulter snabbt kan
hitta liknande historiska transformationer och implementationer, så kan
organisatoriskt lärande skalas bättre än via Slack-frågor och
personberoende nätverk.

## Vad det är

En **thin-slice prototype** byggd som en del av en bredare
systems-thinking-analys av CANEA. Sidan är samtidigt en kort
*one-pager* (varför experimentet gjordes, vad vi observerade, vad vi
lärde oss) och en körbar prototyp (textfält → tre matchande case).

## Hypotesen

Den verkliga strategiska tillgången i ett konsultbolag är ofta inte
plattformen — det är den samlade transformations-erfarenheten över
kunder, implementationer och organisatoriska mönster. Om den
erfarenheten görs sökbar i stället för att leva i enskilda människors
huvuden, kan koordinationsfriktion minska och återanvändbart lärande
växa.

Prototypen testar arbetssättet, inte tekniken.

## Vad det inte är

- Ingen riktig AI-modell — bara enkel keyword- och taggbaserad
  matchning
- Ingen backend, inga API-anrop
- Ingen dependency, inget byggsteg
- Inga riktiga kunddata — alla sju case är fiktiva men realistiska
- Inget produktlöfte — det är ett utforskande experiment

## Öppna lokalt

Klona och öppna `index.html` i valfri modern webbläsare:

```bash
git clone https://github.com/cola500/canea-pattern-mirror.git
cd canea-pattern-mirror
open index.html
```

Allt körs i webbläsaren. Ingen server, ingen installation.

## Publicera via GitHub Pages

Repot är redan konfigurerat att deploya via GitHub Pages från `main`
branch / root folder. När Pages är aktiverat finns sidan på:

<https://cola500.github.io/canea-pattern-mirror/>

Om du forkat repot och vill publicera under din egen användare:

1. Gå till **Settings → Pages** i ditt fork
2. Källa: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. Spara — sidan blir live på
   `https://<ditt-användarnamn>.github.io/canea-pattern-mirror/`
   inom någon minut

## Struktur

```
canea-pattern-mirror/
├── README.md      ← det här dokumentet
├── index.html     ← hela prototypen (HTML + CSS + JS + data i en fil)
└── .gitignore
```

En fil. Inga dependencies. Inget byggsteg. Avsiktligt minimalt.
