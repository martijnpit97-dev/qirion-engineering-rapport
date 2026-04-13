# Onderzoeksdocument: AI en de toekomst van de Engineer in de energie-infrastructuur
*Sessie 2 output — wordt gebruikt als basis voor rapportbouw in sessie 3-4*

---

## Beperkingen vooraf

- **Bias naar Angelsaksische bronnen**: het merendeel van de casuïstiek, cijfers en prognoses is afkomstig uit de VS en het VK. De Nederlandse energiesector (gereguleerde netbeheerders, publieke aandeelhouders, CAO-structuur) wijkt hier structureel van af. Bevindingen zijn vertaald naar de Nederlandse context waar mogelijk, maar die vertaling is interpretatief.
- **Geen primair onderzoek**: alle data is afkomstig uit secundaire bronnen (analisten, leveranciers, vakbladen, wetenschappelijke publicaties). Er zijn geen interviews of enquêtes afgenomen bij engineers binnen de organisatie.
- **Snelheid van het veld**: AI-ontwikkelingen in de energiesector bewegen snel. Cijfers en productaankondigingen van 2024-2025 kunnen bij publicatie van het rapport al achterhaald zijn.
- **Leveranciersbias**: een deel van de bronnen (Siemens, ABB, Schneider, Hitachi Energy) zijn leveranciers met commercieel belang bij digitalisering. Hun claims over productiviteitswinst zijn niet onafhankelijk geverifieerd.
- **Geen specifieke case studies voor HV-engineers en GenAI**: de beschikbare productiviteitsstudies betreffen softwareontwikkelaars en klantenservice, niet engineers in de hoogspanning. Extrapolatie naar het engineeringsdomein is plausibel maar niet empirisch bewezen.

---

## 1. Macrotrends: AI en het energienet

### 1.1 Groeiende druk op het net
De wereldwijde energievraag groeit met 5,7% per jaar in de VS (t.o.v. 0,2% in het voorgaande decennium), mede gedreven door datacenters en AI zelf. [¹] In Europa schat Eurelectric een noodzakelijke grid-investering van €21,4 biljoen tot 2050, waarbij de sector haar asset-deployment moet verdubbelen in een krappe arbeidsmarkt. [²]

### 1.2 AI als versneller en efficiëntietool
De IEA schat dat AI-gebaseerde foutdetectie de duur van storingen met 30-50% kan verkorten, en remote sensoren met AI-gebaseerd beheer tot 175 GW aan transmissiecapaciteit kunnen ontsluiten op bestaande lijnen. [³] De Europese Commissie publiceert in 2026 een Strategische Routekaart voor digitalisering en AI in de energiesector. [⁴]

### 1.3 De arbeidsmarkt
- De wereldwijde energiesector heeft tussen 2025 en 2030 450.000 tot 1,5 miljoen extra engineers nodig (IEEE Spectrum). [⁵]
- 56% van het huidige personeel heeft minder dan 10 jaar ervaring; bij engineering-rollen loopt dit op tot boven de 60%. [⁵]
- 40% van de leidinggevenden in de energiesector rapporteert problemen bij het werven van gekwalificeerd personeel. [⁵]

---

## 2. AI-technologieën relevant voor de engineering-functiegroep

### 2.1 Predictive maintenance en asset management
AI-systemen combineren realtime sensordata (temperatuur, trillingen, belastingcycli, elektrische prestaties) met historische patronen om storingen te voorspellen vóór ze optreden.
- **Resultaten**: tot 30% minder downtime, 40% lagere onderhoudskosten (diverse bronnen). [⁶]
- **Casestudie NextEra Energy**: AI-algoritmen sturen automatisch zonnepanelen en windturbinebladen bij. Resultaat: 25-30% lagere onderhoudskosten, 70-75% minder storingen. [⁷]
- **Relevantie voor de organisatie**: engineers ontwerpen installaties die steeds meer sensoriek bevatten; ontwerpkeuzes beïnvloeden de mogelijkheden voor predictive maintenance downstream.

### 2.2 Digital twins
Digital twins zijn virtuele replica's van fysieke assets (verdeelstations, kabelverbindingen, transformatoren) die in real-time worden gevoed met operationele data.
- **Marktomvang**: de digital substation-markt groeit van $8,9 miljard (2025) naar $17,3 miljard (2035), CAGR 6,8%. [⁸]
- **Siemens**: Digital Twin Composer aangekondigd (beschikbaar medio 2026), in samenwerking met NVIDIA voor volledig AI-gedreven adaptieve productieomgevingen. [⁹]
- **ABB**: Ability Smart Grid platform met AI-gestuurde analytics voor vraagvoorspelling, foutdetectie en coördinatie van decentrale energiebronnen. [⁸]
- **Schneider Electric**: One Digital Grid Platform (maart 2025) als technisch fundament voor onafhankelijke softwareoplossingen. [⁸]
- **Relevantie voor de organisatie**: engineers kunnen in de nabije toekomst ontwerpen valideren in digitale tweelingen vóór fysieke bouw, wat fouten en revisies reduceert.

### 2.3 IEC 61850 en substation-automatisering
IEC 61850 blijft de hoeksteen voor communicatie in moderne substations. Recente ontwikkelingen:
- **Ed2.1-updates** en IEC 61869 versterken interoperabiliteit en beveiliging. [¹⁰]
- **Hitachi Energy** PCM600 en IET600 behalen IEC 61850 Ed. 2.1-certificering. [¹⁰]
- **Trend**: glasvezel-procesbus vervangt koperen bekabeling; AI-edge-analytics voor predictive maintenance op IED-niveau. [¹⁰]
- **Relevantie voor secundair engineers**: de standaard vermindert engineering-complexiteit door een object-georiënteerde benadering, maar vereist nieuwe kennis van digitale protocollen en cybersecurity.

### 2.4 Generatieve AI voor kenniswerk
Er zijn geen gepubliceerde case studies specifiek voor HV-engineers en generatieve AI. Wel zijn er robuuste studies uit aangrenzende domeinen:
- **Softwareontwikkelaars** (Microsoft/Accenture/Fortune 100, n=4.867): 26% meer afgeronde taken met AI-codeertool. Minder ervaren ontwikkelaars profiteerden het meest. Adoptiegraad na één jaar: ~60%. [¹¹]
- **Klantenservice**: 15% productiviteitsstijging, met disproportioneel voordeel voor minder ervaren medewerkers. [¹²]
- **Extrapolatie naar engineering**: GenAI kan helpen bij specificatie-opstelling, normenonderzoek, offerte-analyse, rapportage en kennisdeling. De kern van het engineeringswerk (ontwerp, dimensionering, veiligheidsberekeningen) vereist domeinexpertise die GenAI niet kan vervangen, maar wél kan versnellen door context en referenties aan te reiken.

### 2.5 Netautomatisering en IoT
- **Enexis**: inzet van DALI-box (IoT) voor monitoring, besturing en meting van het energienet. Afdeling Netautomatisering beheert communicatie met gevoelige veldapparatuur. [¹³]
- **Enexis GenAI**: actief wervend voor Senior GenAI Engineers om het energienet slimmer en toekomstbestendiger te maken. [¹³]
- **AI for Energy Grids Lab** (samenwerking Alliander en academische partners): ontwikkelt methoden en tools op basis van netwerkdata voor efficiëntie, duurzaamheid en betrouwbaarheid van midden- en laagspanningsnetten. [¹³]

---

## 3. Impact op de engineering-rol

### 3.1 Wat verdwijnt (of sterk vermindert)
- **Handmatige tekeningen en 2D-ontwerpen**: worden vervangen door 3D-modellering en parametrische ontwerpsystemen
- **Repetitieve specificatie-arbeid**: standaardbeschrijvingen, materiaallijsten en montagebestekken kunnen grotendeels geautomatiseerd worden
- **Reactief onderhoud**: verschuift naar predictief; engineers ontwerpen steeds meer voor monitorability
- **Lineair projectverloop**: waterval-achtige aanpak maakt plaats voor iteratief ontwerp met digital twins

### 3.2 Wat ontstaat
- **AI-geletterde engineer**: kan werken met en naast AI-tools; begrijpt wat modellen wel en niet kunnen
- **Digital twin-specialist**: kan virtuele modellen opzetten, valideren en interpreteren
- **Data-bewust ontwerpen**: ontwerpen met sensorplaatsing en dataverzameling als ontwerpparameter (design for monitorability)
- **Cybersecurity-bewustzijn**: naarmate substations digitaler worden, groeit het aanvalsoppervlak; engineers moeten beveiligingsprincipes meenemen in het ontwerp
- **Systems thinking op systeemniveau**: de engineer als integrator van primair, secundair, IT/OT en data-lagen
- **Cross-disciplinaire coördinatie**: grotere rol in de afstemming met data-engineers, SCADA-specialisten en AI-teams

### 3.3 Wat blijft
- **Domeinexpertise hoogspanning**: kennis van elektrische principes, normen (IEC, NEN), veiligheidsvoorschriften, material science — dit is niet automatiseerbaar
- **Engineeringsjudgement**: het vermogen om in complexe, ambigue situaties de juiste ontwerpkeuze te maken
- **Klantrelatie en vertaling PvE → ontwerp**: het vertalen van klantbehoeften naar technische oplossingen
- **Kwaliteitscontrole en review**: het beoordelen van engineeringspakketten van collega's
- **Veldkennis**: begrijpen hoe een ontwerp zich vertaalt naar montage en operatie in de praktijk
- **Projectcoördinatie**: afstemming tussen disciplines blijft mensenwerk

---

## 4. Sector en regelgevingscontext

### 4.1 Energietransitie Nederland
- Netbeheerders (Liander, Stedin, Enexis) en TSO (TenneT) hebben te maken met sterk groeiende transportvraag door elektrificatie, datacenters en hernieuwbare opwek
- De investeringsagenda voor netuitbreidingen is ongekend groot; de capaciteit om projecten te engineeren is de bottleneck, niet het budget
- De organisatie staat als uitvoeringspartner van Liander en TenneT middenin deze druk

### 4.2 Regulering
- **EU AI Act**: art. 4 verplicht AI-geletterdheid voor organisaties die AI-systemen inzetten; art. 26 regelt verplichtingen voor hoogrisico-AI; Annex III definieert kritieke infrastructuur (waaronder energienetwerken) als potentieel hoog risico
- **FRIA-verplichting**: vanaf augustus 2026 moeten organisaties die AI inzetten in kritieke infrastructuur een Fundamental Rights Impact Assessment uitvoeren
- **SER-advies AI en Werk (mei 2025)**: benadrukt het belang van werknemersbetrokkenheid bij AI-implementatie, scholing en het voorkomen van algoritmisch management
- **WOR art. 25 en 27**: de OR heeft advies- en instemmingsrecht bij invoering van AI-tooling die werkprocessen wijzigt
- **AVG**: AI-systemen die persoonsgegevens verwerken (bijv. prestatiemonitoring) vallen onder DPIA-plicht

### 4.3 Eurelectric-context
- Digitalisering is een van drie strategische prioriteiten (naast klantgedreven elektrificatie en energiezekerheid) [²]
- Een gedigitaliseerd energiesysteem kan alleen slagen met een workforce die het kan bedienen; EU moet helpen met formalisering van onderwijs, skills-initiatieven en grensoverschrijdende certificering [²]
- Tekort aan gespecialiseerde IT- en digitale vaardigheden beperkt het vermogen om digitale oplossingen te implementeren en beheren [²]

---

## 5. Casussen en voorbeelden

### 5.1 NextEra Energy (VS) — Predictive maintenance
AI-algoritmen sturen automatisch zonnepanelen en windturbinebladen bij. Resultaat: 25-30% lagere onderhoudskosten, 70-75% minder storingen. *Relevantie*: toont de impact van AI op operationeel beheer van energieassets; de organisatie onderhoudt vergelijkbare assets. [⁷]

### 5.2 Siemens + NVIDIA — Digital Twin Composer (2026)
Partnerschap voor volledig AI-gedreven, adaptieve productie- en energieomgevingen. Digital Twin Composer maakt het mogelijk om virtuele modellen van substations te bouwen en te testen vóór fysieke realisatie. *Relevantie*: direct toepasbaar op het ontwerp van verdeelstations door de organisatie. [⁹]

### 5.3 AI for Energy Grids Lab (NL) — Alliander + academia
Ontwikkelt methoden en tools op basis van netwerkdata voor efficiëntie en betrouwbaarheid van midden- en laagspanningsnetten. Combineert expertise van data scientists, elektrotechnisch engineers en Alliander's digitaliseringsprogramma's. *Relevantie*: directe connectie met de moederorganisatie; engineers kunnen hier kennis en tools uit betrekken. [¹³]

### 5.4 Enexis — Netautomatisering en GenAI
Inzet van IoT (DALI-box) voor netmonitoring. Actieve werving van Senior GenAI Engineers. *Relevantie*: laat zien dat vergelijkbare netbeheerders in Nederland AI al organisatorisch inbedden. [¹³]

### 5.5 Hitachi Energy — IEC 61850 Ed. 2.1 tooling
PCM600 en IET600 met nieuwe certificering voor moderne digitale substations. *Relevantie*: tooling die secundair engineers direct raakt; certificering dwingt bijscholing af. [¹⁰]

---

## 6. Bronnen

### Analisten en onderzoek
- [¹] IEEE Spectrum — A Shrinking Workforce Threatens the Future of the Grid (2025)
- [²] Eurelectric — Strategic Roadmap response digitalisation and AI in energy (2025), Presidency Manifesto 2025-2027
- [³] IEA — AI-based fault detection estimates (via EU Sustainable Energy Week 2025)
- [⁴] European Commission — Strategic Roadmap digitalisation and AI energy sector (adoptie 2026)
- [⁵] IEEE Spectrum — Power Engineering Workforce Gap (2025); Green Recruitment Company — AI Energy Skills Gap (2025)
- [¹¹] MIT Sloan / SSRN — Effects of Generative AI on High-Skilled Work: Evidence from Three Field Experiments with Software Developers (2024-2025)
- [¹²] Science — Experimental evidence on the productivity effects of generative AI (Brynjolfsson, Li, Raymond, 2023)

### Leveranciers en technologie
- [⁶] Tandfonline — Leveraging AI for predictive maintenance in energy systems (2025)
- [⁷] Energy Digital — Top 10 AI Applications in Energy (2025); NextEra Energy case
- [⁸] GM Insights — Digital Substation Market Size 2026-2035
- [⁹] Siemens Press — Digital Twin Composer (CES 2026); Siemens-NVIDIA partnership
- [¹⁰] Hitachi Energy — IET600 IEC 61850 Ed. 2.1; MDPI Electronics — Review IEC 61850 protocols

### Nederlandse context
- [¹³] Enexis — GenAI Engineer vacature; Netautomatisering; AI Hub Oost — AI for Energy Grids Lab; InnovationQuarter — AI voor de energietransitie; React Online — Digitale tools en AI

### Regelgeving
- EU AI Act — art. 4 (AI-geletterdheid), art. 26 (hoog risico), Annex III (kritieke infrastructuur)
- SER — Advies AI en Werk (mei 2025)
- WOR — art. 25 (adviesrecht), art. 27 (instemmingsrecht)
- AVG — DPIA-verplichting bij persoonsgegevensverwerking door AI
- FRIA — Fundamental Rights Impact Assessment, verplicht vanaf augustus 2026

---

## 7. Samenvatting voor rapportbouw

**Kernboodschap**: De engineering-functiegroep staat niet voor vervanging door AI, maar voor een fundamentele verschuiving in hoe het werk wordt gedaan. De combinatie van energietransitie-druk, arbeidsmarktkrapte en exponentiële groei in AI-tooling maakt het onvermijdelijk dat engineers moeten transformeren van puur technisch ontwerpers naar AI-geletterde, data-bewuste integrators. De domeinexpertise (hoogspanning, normen, veiligheid, veldkennis) wordt schaars en daarmee waardevoller; de repetitieve en administratieve componenten van het werk worden geautomatiseerd.

**Drie scenario-lagen voor het rapport**:
1. **Verdwijnt**: handmatige specificaties, reactief onderhoud, lineair projectverloop
2. **Ontstaat**: AI-geletterde engineer, digital twin-specialist, design for monitorability, cybersecurity-bewustzijn
3. **Blijft**: domeinexpertise, engineeringsjudgement, klantvertaling, kwaliteitsreview, veldkennis
