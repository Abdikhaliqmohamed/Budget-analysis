#  Budget og omkostningsstyring


![alt text](Assets/images/budget.png)

## Litteraturliste

- [Formål](#Formål)
- [User story](#User-story)
- [Objektivitet](#Objektivitet)
- [Bruger detalje](#Bruger-detalje)
  - [Hvad har de svært med](#Hvad-har-de-svært-med) 
  - [Hvad ser succes ud for dem](#Hvad-ser-succes-ud-for-dem)
  - [Hvad skal der bygges](#Hvad-skal-der-bygges)
- [Analyse](#Analyse)
  - [Fund](#Fund)
- [Visualisering](#Visualisering)
- [Handlingsplan](#Handlingsplan)
- [Scenarieanalyse](#Scenarieanalyse)
- [Handlingsplan](#Handlingsplan)




# Formål 
At udarbejde et budgetanalyse for Vestas' kvatale omkostninger i Excel baseret på en rullende forecast. Analysen skal kunne give ledelsen et klart overblik over deres øknomi, og hjælpe med at tage datadrevne beslutninger. 

# User Story
Vestas er under en større omstrukturering af deres interne organisationsstruktur, og har derfor hyret en ekstern konsulent, til at udføre en budgetprognose. Prognosen skal følgende:

- Kunne opdateres løbende med afvigelser og prognoser.
- Indholde en scenarieanalyse bestående af best case, worst case og mest sandsynlige tilfælde
- Illustrerer hvordan ændringerne påvirker budgettet.

# Objektivet
Målet er at skabe en udgiftsrapport for Vestas, der gør det muligt at:

•	Spotte afdelinger med overforbrug
•	Følge økonomiske bevægelser på tværs af organisationen
•	Træffe smartere datadrevne beslutninger

# Udfordringer 
•	Organisationen står i en uforudsigelig periode med omstrukturering 
•	Savner et samlet overblik over deres finansielle status

### Succes for brugeren betyder

•	En overskuelig tabel som viser forbruget
•	Automatisering for markeringen af steder med overforbrug
•	Visualisering af udgifter fordelt på afdelingerne 
•	En scenarieanalyse til at understøtte ledelsens beslutninger

### Leverencen skal indeholde?
•	Projektområde
•	Oprindeligt budget
•	Opdateret forecast 
•	Faktiske omkostninger
•	Markering af overskridelser


# Analyse

### Fund
Vestas har under deres omstrukturering allerede igangsat opdateret forecast for afdelingerne. Tabellen viser hvorderen pengene er blevet fordelt:


![alt text](Assets/images/Vestas'-Budget.png)


Med allokeringen af pengene til andre afdelinger, som havde et større behov. Sikre Vestas at belastningen under omstruktureringen ikke var mere alvorlig. Udregningen af afvigelserne af budgettet ser ud som følgende:


![alt text](Assets/images/Afvigelse.png)



Afvigelserne i tabellen viser forskellen mellem den forecast og de aktuelle omkostninger. Projektområderne har ifølge analysen ikke holdt sig inden for budgettet. Driftsstøtte som den eneste genereret en besparelse for virksomheden på 15.000 $. 





# Visualisering
Diagrammet forneden illustreret forbruget, og giver et overblik over:

De forventede omkostinger vs. faktiske omkostninger. 
De blå søjler repræsenterer de målte omkostninger i Dollars, hvor de orange repræsenterer de faktiske omkostninger i Dollars:


![alt text](Assets/images/Tabel.png)

Betinget formatering er blevet anvendt for at tydeligere hvilke afdelinger, som holdte sig inden for budgettet, de som ikke gjorde:


![alt text](Assets/images/Vestas'-Budget.png)

Den automatiske kategorisering er opnået ved hjælp af HVIS-funktioner i Excel, hvilket reducerer manuel fejlretning og giver et mere skalerbart system


![alt text](Assets/images/HVIS-funktion.png)





# Scenarieanalyse 
Budgettet som på forhånd var blev udregnet er med udgangspunkt det mest sandsynlige scenarie. For at teste robustheden er der udviklet: 
- Best case: alle projekter holder sig 7 % under budget.
- Worst case: projekterne overskrider budgettet med 10 %.
Denne tilgang giver ledelsen et klart billede af, for at drøfte og styrke strategier ved at klarlægge, hvad der har betydning på lang sigt
 


# Handlingsplan

##### Strammere overvågning:

I stedet for udelukkende at føre kvartalsvis budgetopfølgning bør Vestas under omstruktureringen indføre månedlig overvågning. Det gør det muligt at reagere hurtigere på afvigelser og omallokere midler.
 
##### Sikkerhedsnet:

For at reducere risiko bør Vestas afsætte en buffer på eksempelvis 10 % af det samlede budget. Det kan forhindre større udfordringer, når enkeltprojekter overskrider budgettet.

##### Scenarieanalyse:

Scenarieanalyser bør integreres i den fremtidige planlægningsproces og kombineres med et dashboard, der giver et visuelt overblik. Dette sikrer, at ledelsen kan træffe mere informerede og datadrevne beslutninger.
