# Trasomat V1 Launch Plan

## 1) Produktové rozhodnutí (locked scope)

### Must-have (den 1)
- CZ-only dispatcher web app
- CSV import zastávek
- Definice vozidel (kapacita), směn a depa
- Optimalizace s časovými okny, prioritou a omezeními
- Export do Google Maps + denní harmonogram

### V2 (odložené)
- Driver mobile app
- EN verze
- Pokročilý live dispatching během dne
- Integrace na externí systémy

## 2) Cenotvorba (doporučení)

Pro první prodej je nejlepší **tiered SaaS podle počtu vozidel**, protože:
- Je to snadno pochopitelné při cold outreach.
- Neodradí menší firmy variabilní cenou za stop.
- Je jednoduché predikovat MRR.

### Návrh tarifů
- **Starter**: 1-2 vozidla
- **Growth**: 3-5 vozidel
- **Scale**: 6+ vozidel

Doporučení: nabídnout 14denní trial bez karty.

## 3) Technický přístup (plain language)

- Frontend: jednoduchý web dashboard pro dispatchera.
- Backend: API pro import dat a výpočet optimálních tras.
- Optimalizační vrstva: solver nad vstupy (zastávky, okna, kapacity, směny, priority).
- Výstup: harmonogram + deep-link export do Google Maps.

## 4) Launch plán (4 týdny)

### Týden 1
- Datový model zakázek, vozidel, depa a omezení
- CSV parser + validace adres
- První verze optimalizačního jádra

### Týden 2
- Dispatcher UI workflow (import -> parametry -> optimize)
- Výsledková obrazovka a KPI
- Export Google Maps

### Týden 3
- Robustnost: edge cases, validace vstupů, chybové stavy
- Logování a monitoring
- UX polish

### Týden 4
- Pilot readiness (demo data, onboarding flow)
- Pricing page a lead capture
- Launch materiály + cold outreach balíček

## 5) GDPR minimum pro V1

- Sběr pouze nutných dat
- Jasná retention politika
- Smlouva o zpracování dat (DPA) pro B2B klienty
- Audit log pro importy a změny plánů

## 6) Cold outreach checklist

- ICP list (lokální CZ kurýři)
- 2 e-mail sekvence (pain-first + ROI-first)
- Demo video do 90 sekund
- Landing stránka s kalkulačkou úspory

