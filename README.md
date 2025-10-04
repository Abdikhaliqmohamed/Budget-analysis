#  Budget og omkostningsstyring


![alt text](Assets/images/budget.png)

## Litteraturliste

- [Oversigt](#Oversigt)
- [Forretningsproblemet](#Forretningsproblemet)
- [Løsningen](#Løsningen)
- [Dashboard Eksempel](#Dashboard-Eksempel)
- [Teknisk Implementering](#Teknisk-Implementering)
- [Anbefalet Handlingsplan](#Anbefalet-Handlingsplan)


# Budget & Omkostningsstyring: Automatiseret Analyse og Scenarieplanlægning

## Oversigt

En simuleret budgetanalyse for Vestas, der omdanner komplekse finansielle data til klare, handlekraftige indsigter. Projektet leverer et Excel-baseret værktøj med automatisk afvigelsesdetektion, visualisering og scenarieanalyse designet til at støtte ledelsens beslutningstagning under en omstruktureringsproces.

##  **Forretningsproblemet**

Under en større omstrukturering stod Vestas over for:
*   Uforudsigelighed i omkostningsstyring på tværs af afdelinger.
*   Mangel på et samlet, realtids overblik over den finansielle status.
*   Behov for at træffe hurtige, datadrevne beslutninger baseret på en rullende prognose.

## **Løsningen**

Jeg udviklede en dynamisk budgetanalysemodel i Excel, der automatiserer rapporteringen og giver et klart overblik. Modellen inkluderer:

*   **Automatisk Afvigelsesdetektion:** Betinget formatering og `HVIS`-funktioner markerer proaktivt områder med overforbrug.
*   **Interaktiv Visualisering:** Diagrammer der sammenligner forecast vs. faktiske omkostninger på tværs af afdelinger.
*   **Scenarieanalyse:** "Best case", "Worst case" og "Mest sandsynlige" scenarier for at teste budgettets robusthed.

### **Dashboard Eksempel:**
![Budget Dashboard](Assets/images/Tabel.png)
*Det visuelle overblik giver ledelsen øjeblikkelig indsigt i afvigelser mellem budgetterede og faktiske omkostninger.*

## **Teknisk Implementering**

*   **Værktøj:** Microsoft Excel
*   **Nøglefunktioner:** Avancerede formler (`HVIS`, `SUM.HVIS`), Pivottabeller, Betinget formatering, Scenariostyring
*   **Datahåndtering:** Simuleret virksomhedsdata for omkostningsfordeling

## **Resultater & Værdi**

*   **Effektivitetsforbedring:** **Reducerer manuel analyse- og rapporteringstid med ca. 70%** gennem automatisering af dataindsamling og afvigelsesmarkering.
*   **Forbedret Nøjagtighed:** **Eliminerede manuelle beregningsfejl** i afvigelsesrapporteringen ved brug avancerede Excel-funktioner.
*   **Proaktiv Beslutningstagning:** Model muliggør **identifikation af budgetoverskridelser på dag 1 i den nye periode**, hvilket giver ledelsen mulighed for at handle før afvigelser eskalerer.
*   **Risikostyring:** Scenarieanalysen **kvantificerede den potentielle finansielle påvirkning (+/- 10%)** og gav et grundlag for oprettelse af en finansiel buffer.

## 📊 **Analyse og Fund**

Analysen afslørede specifikke områder med betydeligt overforbrug, samt en enkelt afdeling (Driftsstøtte) der genererede en besparelse. Dette understregede behovet for en mere granular, månedlig opfølgning frem for kvartalsvis.

![alt text](Assets/images/Afvigelse.png)
*Oversigten over afvigelser viser præcist, hvor budgetkontrol skal prioriteres.*

##  **Anbefalet Handlingsplan**

Baseret på analysen anbefales følgende til Vestas:

1.  **Hyppigere Overvågning:** Implementer **månedlige budgetopfølgninger** under omstruktureringen for at muliggøre hurtigere korrektioner.
2.  Opret en **Budgetbuffer:** Afsæt **10% af det samlede budget** som en sikkerhedsnet for uforudsete overskridelser.
3.  **Institutionalisér Scenarieanalyser:** Integrer scenarieplanlægning som en fast del af den finansielle proces for at forberede ledelsen på forskellige udfald.

---

*[← Tilbage til Portfolio](https://github.com/Abdikhaliqmohamed?tab=repositories)*
