# guaitaPreus

**Visor i editor obert de bases de preus de la construcció (BC3 / FIEBDC-3), pressupostos i amidaments, en un sol fitxer HTML.**
**Open viewer and editor for construction price databases (BC3 / FIEBDC-3), budgets and measurements, in a single HTML file.**

[Obre l'app · Open the app](pagesCAT/guaitaPreus.html) · [Ajuda (CA)](pagesCAT/HLP%20guaitaPreus-ajuda.html) · [Presentació](index.html)

Part of the **Guaita Apps** suite · © SBS BiM Consulting, Jordi Subirós · AGPL-3.0-only

---

## Català

### Què és
guaitaPreus és una eina oberta, pensada per a l'ensenyament i la consultoria, que permet **consultar, cercar i editar bases de preus en format BC3 (FIEBDC-3)**, redactar **pressupostos** i treballar amb **amidaments i certificacions**. Funciona al navegador, sense instal·lació, sense servidor i **sense enviar cap dada enlloc**: tot es queda al teu navegador (IndexedDB).

### Funcions principals
- Importació i exportació de **BC3** (ANSI, UTF-8, CP850, CP437), Excel, HTML imprimible, Markdown, LaTeX i CSV.
- Bases externes (lectura), **bases pròpies** i **pressupostos**, amb capítols, partides, descomposicions i amidaments.
- Cerca i filtres per tipus, unitat, etiqueta i classificació; preferits i etiquetes.
- Desfés / refés, plantilles de capítols, duplicat de versions.
- **Compara** pressupostos, **actualitza preus** des d'una base, **certificacions** amb comprovació d'estructura.
- Fitxes imprimibles de partides, validació de preus i referències, informe de càrrega.
- Mapejat amb la classificació **GuBIMClass** (vegeu l'avís més avall).
- Tema fosc i clar.
- Barres laterals redimensionables i plegables, pestanyes de fitxers, mode concentració, desplegar/replegar l'arbre per nivells i branques, filtres plegables i fitxa amb seccions plegables.

### Com s'utilitza
1. Obre `pagesCAT/guaitaPreus.html` al navegador (o publica el repositori amb GitHub Pages i obre `index.html`).
2. Importa un BC3 propi o crea una base o un pressupost.
3. Consulta l'ajuda: [`pagesCAT/HLP guaitaPreus-ajuda.html`](pagesCAT/HLP%20guaitaPreus-ajuda.html).

### Dades i privadesa
Aquest repositori **no inclou cap base de preus** (BC3). Les bases que carreguis són dels seus titulars i es processen només al teu navegador.

### GuBIMClass
L'app pot relacionar conceptes amb codis **GuBIMClass** (© 2017 GuBIMCat). La taula de codis és de tercers: **no s'inclou** en aquest repositori ni a l'app publicada, i no queda coberta per l'AGPL. Es pot carregar des de l'app (*Eines ▸ GuBIMClass i mapejat*). Vegeu [`NOTICE.md`](NOTICE.md).

### Llicència
GNU Affero General Public License v3.0 only. Vegeu [`LICENSE`](LICENSE). Guaita Apps es distribueix «tal com és», sense cap garantia; la verificació dels resultats i la responsabilitat derivada del seu ús recauen únicament sobre l'usuari final.

---

## English

### What it is
guaitaPreus is an open tool for teaching and consulting that lets you **browse, search and edit construction price databases in BC3 (FIEBDC-3) format**, write **budgets**, and work with **measurements and certifications**. It runs in the browser, with no installation, no server and **no data leaving your machine**: everything stays in your browser (IndexedDB).

### Main features
- **BC3** import/export (ANSI, UTF-8, CP850, CP437), plus Excel, printable HTML, Markdown, LaTeX and CSV.
- Read-only external databases, **own databases** and **budgets**, with chapters, items, breakdowns and measurements.
- Search and filters by type, unit, tag and classification; favourites and tags.
- Undo / redo, chapter templates, version duplication.
- **Compare** budgets, **update prices** from another database, **certifications** with structure checks.
- Printable item sheets, price/reference validation, load report.
- Mapping to the **GuBIMClass** classification (see the notice below).
- Dark and light themes.
- Resizable and collapsible side panels, file tabs, focus mode, expand/collapse the tree by level or branch, collapsible filters and a detail view with collapsible sections.

### How to use it
1. Open `pagesCAT/guaitaPreus.html` in your browser (or publish the repository with GitHub Pages and open `index.html`).
2. Import your own BC3, or create a database or a budget.
3. Read the help file: [`pagesCAT/HLP guaitaPreus-ajuda.html`](pagesCAT/HLP%20guaitaPreus-ajuda.html) (Catalan only for now).

> The user interface and the help are currently available **in Catalan only**; this README is bilingual.

### Data and privacy
This repository **contains no price databases** (BC3). Any database you load belongs to its owners and is processed only in your browser.

### GuBIMClass
The app can map concepts to **GuBIMClass** codes (© 2017 GuBIMCat). The code table belongs to third parties: it is **not included** in this repository or in the published app, and it is not covered by the AGPL. It can be loaded inside the app (*Eines ▸ GuBIMClass i mapejat*). See [`NOTICE.md`](NOTICE.md).

### Licence
GNU Affero General Public License v3.0 only. See [`LICENSE`](LICENSE). Guaita Apps is distributed "as is", without any warranty; verification of the results and any responsibility arising from their use rest solely with the end user.
