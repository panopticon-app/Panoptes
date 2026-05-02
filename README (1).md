# Panoptes — FPN Field Reference

> *"All-seeing street works enforcement"*

NRSWA Fixed Penalty Notice field reference app for Highways Inspectors. Built as a PWA — installs on iPhone and Android home screens, works offline, feels like a native app.

---

## What's in it

- **All 28 FPN offences** — 7 NRSWA, 2 Permit, 19 NCT Conditions. Searchable, filterable, expandable.
- **FPN Calculator** — penalty amounts, 25% discount deadlines, payment dates
- **91-Day Checker** — instant yes/no: can this FPN still be issued?
- **Working Days Calculator** — 22 working days from today (England bank holidays excluded), auto-pulls from GOV.UK when online
- **Offence Checker** — describe what you see on site, AI identifies the offence and next steps
- **Quick Reference** — statutory text for s.54–s.74 with plain English translation, key time limits, issue checklist

---

## Hosting on GitHub Pages

### Step 1 — Create a repository
1. Go to github.com and sign in
2. Click New repository
3. Name it `panoptes` — set to Public — click Create repository

### Step 2 — Upload the file
1. Click Add file → Upload files
2. Rename `inspectfpn.html` to `index.html` then upload it
3. Click Commit changes

### Step 3 — Enable GitHub Pages
1. Go to Settings → Pages
2. Source: Deploy from branch / Branch: main / folder: / (root)
3. Click Save

### Step 4 — Your URL
After ~60 seconds your app is live at:
https://YOUR-USERNAME.github.io/panoptes/

Share this URL with colleagues. They open it once, add to home screen, done.

---

## Installing on iPhone
1. Open the URL in Safari
2. Tap the Share button
3. Tap Add to Home Screen → name it Panoptes → Add

## Installing on Android
1. Open the URL in Chrome
2. Tap the three-dot menu → Add to Home Screen

---

## Future Build List — Phase 2

### 1. SROH Reference Module (PRIORITY)
Specification for the Reinstatement of Openings in Highways — full in-app reference covering:
- Reinstatement categories (flexible/rigid/modular, bound/unbound) by road type
- Layer depths — surface, binder, base, subbase per category and road classification
- Material specifications — approved materials and mix types per layer
- Crowning limits — acceptable tolerances above/below carriageway level (SROH tables)
- Surface depression limits — maximum allowable deviation at each reinstatement stage
- Guarantee periods by reinstatement category (2 or 3 years)
- Interim vs permanent — acceptable standards and how long interim is permitted
- Special reinstatements — block paving, conservation areas, ironwork surrounds
- Version-stamped to current SROH edition (last major revision: 2023)

### 2. FPN Draft Sheet (PRIORITY)
Fill in undertaker name, works ref, location, offence, date — generates a formatted summary to screenshot or copy into authority system.

### 3. Site Evidence Checklist
Per-offence checklist of photographic and written evidence to capture on site.

### 4. Repeat Offender Log
Local tally of FPNs issued per undertaker — stored on device, identify patterns.

### 5. Undertaker Directory
Main statutory undertakers in England with FPN postal and email contacts.

### 6. Works Category Classifier
Describe the works, AI tells you whether it's minor/standard/major and what notice period applies.

---

## Version History

| Version | Date | Notes |
|---------|------|-------|
| v1.0 | Apr 2026 | Initial build — 28 offences |
| v2.0 | May 2026 | FPN Calculator, 91-Day Checker, PWA, Offence Checker (AI) |
| v2.1 | May 2026 | Statutory text drill-downs, plain English translations, Working Days Calculator |
| v3.0 | May 2026 | Full redesign — Panoptes brand, teal/amber/coral, blueprint background |

---

*For reference use only. Always apply professional judgement. Not legal advice.*
*NRSWA 1991 | SI 2007/1951 | TMA 2004*
