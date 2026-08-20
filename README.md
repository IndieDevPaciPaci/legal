# PaciPaci — legal

Zásady ochrany soukromí a podmínky užití pro všechny hry PaciPaci. Jedno místo
pro všechny tituly — dřív měl každý projekt vlastní HTML a rozcházely se.

Hostováno na GitHub Pages, statické HTML, žádný build.

## Struktura

```
index.html            rozcestník (odkazy na všechny hry)
assets/style.css      sdílený vzhled — jedna změna = změna všude
terms/                Podmínky užití, společné pro všechny hry
ishizumi/             Zásady ochrany soukromí — Ishizumi
nagomi/               Zásady ochrany soukromí — Nagomi
waterline/            Zásady ochrany soukromí — Waterline
frogstone/            Zásady ochrany soukromí — Frogstone
tetherloom/           Zásady ochrany soukromí — Tetherloom
```

## URL do Google Play Console

Po zapnutí GitHub Pages (Settings → Pages → Deploy from a branch → `main` / `/`):

| Hra | URL do pole *Privacy policy* |
|---|---|
| Ishizumi | `https://<uživatel>.github.io/legal/ishizumi/` |
| Nagomi | `https://<uživatel>.github.io/legal/nagomi/` |
| Waterline | `https://<uživatel>.github.io/legal/waterline/` |
| Frogstone | `https://<uživatel>.github.io/legal/frogstone/` |
| Tetherloom | `https://<uživatel>.github.io/legal/tetherloom/` |

Podmínky užití: `https://<uživatel>.github.io/legal/terms/` — Play Console je
nevyžaduje, patří do App content → volitelných polí nebo do popisu.

## Přidání nové hry

1. Zkopírovat `nagomi/index.html` do `<novahra>/index.html`.
2. Přepsat název, balíček, datum a odstavec **Information stored on your device**
   (co přesně se ukládá) a **advertising** (jaké formáty reklam hra používá).
   Zbytek je pro všechny hry stejný.
3. Přidat řádek do `index.html` a do seznamu her v `terms/index.html`.

## Pozor

Text musí sedět na to, co hra opravdu dělá — a na to, co je vyplněné v
**Data safety** v Play Console. Když se změní reklamní formáty nebo se přidá
ukládání dat, musí se změnit i tahle stránka a datum *Last updated*.
