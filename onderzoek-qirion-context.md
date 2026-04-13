# Contextdocument: De organisatie en de Engineering-rol
*Sessie 1 output — wordt gebruikt als basis voor sessie 2 (sector/AI-onderzoek) en sessie 3-4 (rapportbouw)*

---

## Beperkingen vooraf

- Vacatureteksten zijn summier en beschrijven taken globaal; concrete werkervaringen van engineers zijn niet beschikbaar via primair onderzoek.
- Informatie over de organisatie is gebaseerd op publieke bronnen (website, LinkedIn, nieuwsberichten) en aangeleverde vacatureteksten.
- De organisatie telt ~477 FTE in de engineering-club; de verdeling primair/secundair/overig is niet exact bekend.
- De engineering-rol is breed: primair (installaties) en secundair (besturing/beveiliging) zijn wezenlijk verschillende disciplines, ook al vallen ze onder dezelfde engineering-paraplu. Dit rapport behandelt de engineering-functiegroep als geheel, met waar relevant onderscheid tussen beide.

---

## Over de organisatie

**Naam in rapport**: "de organisatie" (niet bij naam noemen)

**Wat de organisatie doet**: life cycle service provider voor energie-infrastructuur. Ontwerpt, bouwt en beheert het hoogspannings- en middenspanningsnet van vandaag en morgen. Werkt voor regionale netbeheerder Liander en nationaal netbeheerder TenneT, zowel in een gereguleerde rol als op de vrije markt.

**Omvang**: circa 950 medewerkers totaal; engineering-cluster circa 477 FTE.

**Positie in het energiesysteem**:
- Uitvoeringsorganisatie voor DSO (Liander) en TSO (TenneT)
- Verantwoordelijk voor ontwerp, bouw, onderhoud én 24/7 storingsdienst
- Werkt aan netinfrastructuur van 10 kV tot 150 kV (middenspanning tot hoogspanning)
- Concrete projecten: nieuw verdeelstation Rozenburg-Zuid (Haarlemmermeer, gereed 2025), transformatorvervanging Leiden (2025), inbedrijfstelling Zuilichem (Bommelerwaard)

**Marktcontext**:
- Deels gereguleerde markt (Liander/TenneT als vaste opdrachtgevers)
- Deels vrije markt (klanten in het "vrije domein")
- Sterk groeiende orderportefeuille vanwege energietransitie: netuitbreidingen, nieuwe stations, kabels en lijnen

---

## De engineering-functiegroep

### Twee hoofddisciplines

**Primair engineering** — het "krachtige deel"
- Ontwerpt fysieke elektrische installaties: schakelaars, transformatoren, busbars, kabelverbindingen
- Werkt aan hoogspanningstransportnetten 50 kV–150 kV
- Levert: montagebestekken, begrotingen, uitbestedingstrajecten, engineeringspakketten
- Stakeholders: projectmanager, sitemanager, 3D-modelleurs, tekenaars, collega-engineers, opdrachtgever (Liander/TenneT)
- Tooling: ontwerpsoftware (impliciet), CAD-omgeving
- Seniority: junior/medior (schaal 8-9, ≥5 jaar) en senior (schaal 9-10, ≥7 jaar)

**Secundair engineering** — het "slimme deel"
- Ontwerpt besturing, signalering en beveiliging (relaisbeveiliging, SCADA, meten & beveiligen)
- Werkt volgens systems engineering-methodiek
- Levert: specificaties, basisontwerpen, materiaalspecificaties, begrotingen, uitbestedingstrajecten
- Extra verantwoordelijkheid senior: begeleiding en ontwikkeling van junior/medior engineers, ontwerpleider bij complexe vraagstukken
- Tooling: ELCAD (teken- en ontwerpsysteem), kennis van IEC-normen voor beveiliging en meting
- Seniority: senior (schaal 9-10, ≥10 jaar, HBO/WO)

### Gedeelde kenmerken engineering-functiegroep
- Projectmatig werken in multidisciplinaire teams
- Coördinatie tussen disciplines (primair, secundair, civiel, projectmanagement)
- Uitbestedingsbeheer: offertes beoordelen, gunnen, bewaken
- Kwaliteitscontrole op collega's (reviewen van engineeringspakketten)
- Klantgerichtheid als expliciete competentie: alles heeft impact op eindklanten van Liander/TenneT
- Opleidingsniveau: MBO/HBO werktuigbouwkunde of elektrotechniek (primair), HBO/WO elektrotechniek of industriële automatisering (secundair)

---

## Huisstijl (voor sessie 3-4)

- Primaire kleur: `#525ddc` (paars-blauw)
- Accentkleur: `#e52329` (rood)
- Achtergrond: wit (`#ffffff`) met donkere achtergrond voor hero-sectie te bepalen (donkere variant van primair, bijv. `#2a3080`)
- Fonts: **Inter** (body) + **Barlow Condensed Bold/ExtraBold** (headings) — per skill-regels, niet afwijken naar Museo Sans ook al is dat het huismerk-font
- CSS-variabelen in rapport: hernoem `--green-700` → `#525ddc`, `--green-500` → `#e52329`, `--green-800` → `#2a3080`, `--green-900` → `#1a1f60`

---

## Intake-samenvatting voor volgende sessies

| Parameter | Waarde |
|-----------|--------|
| Doelrol | Engineering (primair + secundair) |
| Omvang | ~477 FTE |
| Diepte | Hoofdrapport (tab 01) eerst; verdieping-tab later |
| Huisstijl | Qirion (paars-blauw/rood), zie boven |
| Output | `C:\Users\marti\Documents\qirion-engineering-rapport\index.html` |
| Naam in rapport | "de organisatie" |
| Sectornuance | Hoog gewicht: DSO/TSO-context, energietransitie, Nederlandse netbeheerregulering |
| Hosting | GitHub repo + Netlify (sessie 5) |
| Naam in rapport | Niet "Qirion" gebruiken |

---

## Zoekvragen voor sessie 2

Gebruik deze queries letterlijk in sessie 2:

1. `"electrical engineer AI automation DSO energy grid 2025 2026"`
2. `"high voltage engineer generative AI productivity case study"`
3. `"energy infrastructure engineering AI tools predictive design 2025"`
4. `"engineer energienet automatisering AI Nederland energietransitie"`
5. `"IEC 61850 AI automation secondary engineering substation"`
6. `"digital twin substations engineering AI Siemens ABB Schneider 2025"`
7. `"grid expansion engineering workforce skills AI future"`
8. `"Eurelectric digital utility engineer skills transformation 2025"`

Ankerbronnen voor sessie 2: Gartner, Deloitte Insights, McKinsey, Eurelectric, DNV, ABB/Siemens/Schneider whitepapers, SER, EU AI Act art. 4 en 26.
