# CEDA 2026 — Planning 4M / 8M / 12M

> **Project:** Centre for Educational Data Analytics — Fase 2
> **Periode:** 1 januari 2026 – 31 december 2026

---

## Gantt chart

```mermaid
%%{init: {"gantt": {"displayMode": "compact"}, "themeVariables": {"sectionBkgColor": "#dde4f0", "sectionBkgColor2": "#ffffff", "altSectionBkgColor": "#dde4f0"}}}%%
gantt
    title CEDA 2026 — Planning 4M / 8M / 12M
    dateFormat YYYY-MM-DD
    axisFormat %b '%y
    todayMarker on


    4M                                  :vert, m4, 2026-04-30, 1d
    8M                                  :vert, m8, 2026-08-31, 1d
    12M                                 :vert, m12, 2026-12-31, 1d

    section 1. Input & Draagvlak
    Use cases HBO/WO ophalen                   :active, bde1, 2026-02-01, 2026-08-31
    1                            :milestone, bde1, 2026-06-01, 0d
    2                            :milestone, bde2, 2026-06-08, 0d
    3                            :milestone, bde3, 2026-06-15, 0d
    Regiobijeenkomsten                            :milestone, bde4, 2026-06-22, 0d
    Methodiek vraagarticulatie                    :crit, bde5, 2026-09-01, 2026-12-31

    section 2. MVPs
    Voorbereiding MVP incubator         :nc1, 2026-01-01, 2026-02-28
    3-4 MVPs valideren                  :crit, nc3, after nc1, 2026-08-31
    Validatie-workshops                 :milestone, nce1, 2026-09-15, 1d
    MVPs doorontwikkelen                :nc4, 2026-11-01, 2026-12-31

    section 3. Opschalen analyse tools
    Instroomprognose HBO/WO (Studielink):active, oa3, 2026-02-01, 2026-08-30
    Instroomprognose MBO (PortalPlus)  :oa4, 2026-08-30, 2026-12-31
    Uitvalanalyse MBO (interventie)     :active, oa2, 2026-03-01, 2026-08-31
    Uitvalanalyse HBO/WO (interventie)  :oa6, 2026-08-31, 2026-12-31
    Uitvalanalyse HBO/WO (beleid)       :active, oa5, 2026-02-01, 2026-09-01
    Uitvalanalyse MBO (beleid)          :oa5, 2026-09-01, 2026-12-31
    K									:milestone, oa7, 2026-04-20, 1d
    NKO Evaluatietool Selectie MVP		:oa8, 2026-05-01, 2026-09-02
    Opschaling Evalutietool (potentieel):crit, oa9, 2026-09-02, 2026-12-31

    section 4. Adoptie
    Key User Groepen                    :ad1, 2026-05-01, 2026-12-31
    Transformatieprogramma voorbereiding:crit, ad2, 2026-06-01, 2026-12-31

    section 5. Ecosysteem
    Communicatie aanpak                 :active, ec1, 2026-01-01, 2026-04-30
    Communicatie implementatie          :ec3, 2026-05-01, 2026-12-31
    Advies Instroom ecosysteem          :ec4, 2026-09-01, 2026-12-31
    Advies Uitval ecosysteem            :ec5, 2026-09-01, 2026-12-31

    section 6. Toegankelijkheid
    Lokale installatie                  :active, to1, 2026-02-01, 2026-04-30
    Lokale installaties valideren       :crit, to2, 2026-05-01, 2026-09-30
    1                                   :crit, milestone, to3, 2026-10-27, 1d
    DAIR, SURF OWD                      :crit, milestone, to4, 2026-11-04, 1d
    Verkennen analytics platform / data space     :crit, to5, 2026-05-01, 2026-08-31
    PoC analytics platform / data space           :to6, 2026-09-01, 2026-12-31

```

#### DAIR, SURF OWD
- Bij allebei zit Corneel in programmacommissie
- **Deadlines voor aanmelden zijn begin juni**
- OWD heeft pecha kucha (presentatie van <7 minuten)
- Voor DAIR hoop ik op 2 hands-on GenAI workshops van anderhalf uur
  - Voor Analytics mensen
  - Voor IR / Beleid mensen
- Ik wil vervolgens (in 2027) naar soort 'Lab' of 'Werkplaats' waar collega's van instellingen obv CEDA standaarden en misschien op CEDA github hun eigen challenges oplossen en op elkaars oplossingen voortbouwen.

#### 3-4 MVPs valideren. Dit gaat om:
- Alan (Data-driven AI alignment with education)
- Shirley (Skillsradar - met MBO Data coalitie)
  - **Hier is misschien hulp nodig in mei & juni**
- Ed (Samenwijzer - met MBO Data coalitie)
- Hibo (Doorstroom mbo obv markov chains)

#### Opschaling Evalutietool (potentieel)
- Het NKO heeft al aangegeven graag te willen opschalen en hiervoor budget te hebben
- Dit regelen vergt echter wat organisatorisch handwerk
- Dit zal in mei of juni duidelijk worden

#### Transformatieprogramma voorbereiding
- Samen met Amir willen we een plan maken om instellingen / teams aan te sluiten.
- Dit zou dan in 20227 echt van start moeten gaan.
- Per mbo / hbo / wo 2 instellingen. Vooral hbo moet ik nog even over nadenken
- Het liefst instellingen met zowel Python/R skills als goede structuur

#### Methodiek vraagarticulatie
- We hebben vorig jaar en dit jaar use cases opgehaald.
- Tegelijkertijd zijn er ook veel andere manieren om behoeftes op te halen.
  - Bijv. via sectoraanvoerders (bestuurlijk) of project DiDeMa (contact vanuit Npuls met midden-management).

#### Lokale installaties valideren
- Dit kunnen we doen door middel van workshops op onze andere tools.
- Dit is misschien wel het meest belangrijk, omdat het nog even gaat duren voor instellingen 'op productie' analytics platform kunnen gebruiken.

#### Verkennen analytics platform / data space
- Naast SURF Developer Platform is er ook team dat experimenteert met een open source Data Lake House als dienst
- Daarbij is het naast techniek ook veel afstemming binnen SURF
  - **Deze afstemming valt buiten CEDA maar binnen het subdomein 'AI & Data Voorzieningen' en is nog niet goed ingeregeld**

## Niet op roadmap 2026

#### Learning Analytics & AI en Data in het leerproces
Nu hebben we met Alan Berg iemand die een echt vernieuwend project doet. Rondom het analytics platform ben ik ook gevraagd mee te denken met Learning Analytics use cases. Voor de langere termijn is Learning Analytics ook in scope van CEDA, maar dit was er voor 2026 nog buiten gehouden.

De contactpersonen bij instellingen voor dit soort onderwerpen zijn vaak niet IR/Analytics/BI, maar meer CTLs en ICT/Innovatie in onderwijs specialisten. Mogelijk dat we hier in tweede helft van dit jaar toch al meer mee gaan experimenteren.

#### Opgekomen ideeën
We hebben ook pitches over NSE en gebruiken open data. Dat zijn echt goede ideeën, maar geen dingen die we beloofd hebben. Laten we dus in ieder geval onze doelen halen en als we bijv. in de zomer weinig feedback van gebruikers krijgen op onze hoofddoelen, dan kunnen we tijd hiervoor maken. Ook hiervoor geldt dat als er extra budget en menskracht komt, we dit mogelijk eerder kunnen oppakken.
