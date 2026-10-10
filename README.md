# Bestand i bevegelse – En interaktiv læringssti

En ren, enkeltstående nettapplikasjon utformet som en digital feltbok for undervisning i **økologi og naturforvaltning**. Læringsstien tar elevene/brukerne gjennom interaktive stasjoner der de gjetter, utforsker modeller, løser oppgaver og dokumenterer sine observasjoner med egne ord.

---

## 📋 Innholdsfortegnelse

- [Om prosjektet](#-om-prosjektet)
- [Hovedfunksjoner](#-hovedfunksjoner)
- [Teknologi](#-teknologi)
- [Bruk og installasjon](#-bruk-og-installasjon)
- [Læringssti og pedagogikk](#-læringssti-og-pedagogikk)
- [Tilgjengelighet (A11y) og utskrift](#-tilgjengelighet-a11y-og-utskrift)
- [Lisens og kreditering](#-lisens-og-kreditering)

---

## 🌲 Om prosjektet

*Bestand i bevegelse* er en digital læringsressurs utviklet for å gi god faglig dybde om bestandsdynamikk, hjortedyr (elg, hjort, rein) og naturforvaltning. Applikasjonen fungerer som en **digital feltbok** hvor fremdrift og egennotater lagres lokalt i brukerens nettleser.

---

## ✨ Hovedfunksjoner

* **14 Interaktive stasjoner:** Trinnvis fremdrift gjennom kjernekonsepter innen økologi.
* **Lagring i nettleser (`localStorage`):** Elevens svar, notater og fremdrift lagres automatisk uten behov for innlogging eller backend-database.
* **Interaktive oppgaver og interaksjoner:**
  * Flervalgsoppgaver med umiddelbar tilbakemelding.
  * Interaktive verktøy, budsjettkalkulatorer, glidebrytere og SVG-diagrammer/grafer.
  * Egennotatfelt for hypotese, forklaring og refleksjon.
* **Null eksterne avhengigheter:** Alt kjører lokalt i én enkelt HTML-fil med innebygd CSS, JavaScript og Base64-kodede bildeaktiva (elg, hjort, rein).
* **Nullstillingsfunksjon:** Mulighet til å starte læringsstien på nytt.

---

## 🛠 Teknologi

Prosjektet er bygget etter prinsippet om **Zero Dependencies** (ingen eksterne biblioteker, rammeverk eller pakkebehandlere):

* **HTML5:** Semantisk oppbygging med ARIA-tilgjengelighetstagger.
* **CSS3:** Tilpasset responsivt design ved hjelp av CSS Variables, Grid, Flexbox og Media Queries.
* **Vanilla JavaScript (ES6+):** `'use strict'`-kjøremiljø for dynamisk tilstandsbehandling, oppgavelogikk og UI-oppdateringer.

---

## 🚀 Bruk og installasjon

Siden applikasjonen er samlet i én enkelt fil (`index.html`), kreves ingen byggeprosess eller serveroppsett.

### Åpne lokalt
1. Last ned filen `index.html`.
2. Dobbelklikk på filen eller åpne den i en valgfri, moderne nettleser (f.eks. Chrome, Firefox, Safari eller Edge).
3. Sørg for at JavaScript er aktivert.

### Publisering på nett
Siden dette er en statisk HTML-fil, kan den enkelt publiseres direkte på:
* GitHub Pages
* Netlify / Vercel
* Læringsplattformer (LMS) som støtter statiske HTML-filer.

---

## 🎯 Læringssti og pedagogikk

Læringskretsløpet i stasjonene følger en tretrinnsmetodikk:
1. **Gjett/Hypotese:** Utfordre egen forkunnskap før fasit oppgis.
2. **Utforsk:** Bruk simuleringer, datatabeller og grafer til å undersøke sammenhenger.
3. **Forklar:** Dokumenter observasjonene med egne ord i feltboken.

---

## ♿ Tilgjengelighet (A11y) og utskrift

* **Tastaturnavigasjon:** Inneholder hjertelinke (*Skip to content*) samt synlige fokusmarkeringer (`:focus-visible`).
* **Bevegelseshemming:** Støtter `prefers-reduced-motion` for å slå av animasjoner ved behov.
* **Utskrift/PDF-eksport:** Egen `@media print`-styling skjuler menyknapper og fremdriftsindikatorer, slik at den utfylte feltboken kan skrives ut eller lagres som en ryddig PDF-rapport.

---

## 📄 Lisens og kreditering

* **Fagfelt:** Økologi og naturforvaltning.
* **Aktiva:** Innebygde fotomaterialer og illustrasjoner av norsk fauna.
