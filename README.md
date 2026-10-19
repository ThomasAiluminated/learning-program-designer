# Learning Program Designer

**Een Claude-skill die een opleidingsvraag omzet in een programma dat verandert wat mensen op het werk doen, niet alleen wat ze weten aan het eind van de dag.**

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

Je beschrijft de vraag ("onze teamleiders geven nauwelijks feedback, ontwerp een opleiding van max. 1 dag") en krijgt een volledig ontwerp terug: van behoefte en leerdoelen tot sessieplannen, transfer naar de werkvloer en evaluatie.

*English summary: a Claude skill that designs training programs, workshops, courses and learning journeys from need to evaluation: performance need, measurable objectives, a blended session-by-session plan, workplace transfer and Kirkpatrick-based evaluation. It works in Dutch, French and English.*

## Wat de skill doet

- **Start bij het prestatieprobleem, niet bij de inhoud.** Wie zijn de deelnemers, wat moeten ze anders doen, waarom nu, en welke randvoorwaarden zijn er?
- **Zegt het als opleiding niet (alleen) het antwoord is**, bijvoorbeeld bij onduidelijke processen, ontbrekende tools of tegenstrijdige prikkels, en stelt voor wat er daarnaast nodig is.
- **Schrijft 3 à 6 meetbare prestatiedoelen** met een observeerbaar werkwoord. Elke activiteit dient minstens één doel; de rest wordt geschrapt.
- **Ontwerpt een leertraject in drie fasen:**
  - **vooraf**: korte voorbereiding of eigen cases verzamelen
  - **tijdens**: ritme van korte input → oefenen → feedback → reflectie, met de meeste tijd voor oefenen op realistische taken
  - **achteraf**: transfer, waar de meeste programma's falen (actieplan met check-in, gespreide opdrachten, intervisie, jobaids)
- **Spreidt leren in de tijd** waar het formaat dat toelaat, en wijst aan waar AI-tools echt helpen.
- **Plant evaluatie volgens Kirkpatrick**, in verhouding tot de omvang van het programma, zonder ROI te beloven die niet geloofwaardig aan te tonen is.

## Wat je terugkrijgt

1. **Behoefte en aannames**, met een "opleiding alleen lost … niet op"-noot waar relevant
2. **Leerdoelen**
3. **Programma-overzicht**: fase, formaat, duur, doelen
4. **Sessieplannen**: tijd, activiteit, methode, doel, materiaal, met tijden die kloppen
5. **Transferplan**: wat er achteraf gebeurt en wie verantwoordelijk is
6. **Evaluatieplan** per Kirkpatrick-niveau
7. **Volgende stappen**

Voor grotere programma's kan de skill het plan omzetten naar een document, een pitchdeck voor de klant of een draaiboek voor de begeleider.

## Voor wie

Voor L&D- en HR-professionals, opleidingsverantwoordelijken, docenten en consultants die opleidingen, workshops, onboardingtrajecten, nascholingen of leertrajecten ontwerpen.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): prompts voor leerkrachten, met uitleg waarom ze werken
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessen ontwerpen van leerdoel tot exit-check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): beoordelingsrubrics met observeerbare niveaus
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specifieke, haalbare feedback op leerlingenwerk
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): lesmateriaal toegankelijk maken met UDL
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (web, desktop of mobiel):**
1. Download [`learning-program-designer.skill`](learning-program-designer.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `learning-program-designer/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"ontwerp een onboardingtraject van drie weken voor nieuwe docenten"*. De skill start vanzelf.

## Structuur

```
learning-program-designer/
└── SKILL.md                       # de volledige instructies van de skill
examples/                 # voorbeelden van input en output
learning-program-designer.skill    # installeerbaar pakket
```

## Bijdragen

Ideeën en verbeteringen zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
