# OpenDataAPI2.0
De nieuwe versie van de Open Data API is live gegaan op 1 april 2019. De problemen van de productie omgeving worden hier geregistreerd.

Deze GitHub pagina is om met externe afnemers van het Open Data Portaal (opendata.tweedekamer.nl) een centrale issue tracker te faciliteren. Documentatie van de API's en het informatiemodel is te vinden op:
https://opendata.tweedekamer.nl/documentatie/api-documentatie-20

Bevindingen m.b.t. de volgende onderwerpen kunnen op deze issue tracker ingediend worden:
-	Datakwaliteit
-	Duidelijkheid documentatie
-	Performance
-	API technische bevindingen:
  - OData V4
  - SyncFeed (Atom 1.0)

Toekomstige ontwikkelingen in nieuwe versies zullen aparte repositories worden.

Let op:
-	Data per entiteit is near-time:
1. Personen (incl geschenken, reizen, nevenfuncties en CV), Commissies en Fracties. (Entiteiten: commissie, commissieContactinformatie, commissieZetel, commissieZetelVastPersoon, commissieZetelVastVacature, commissieZetelVervangerPersoon, commissieZetelVervangerVacature, fractie, fractieAanvullendGegeven, fractieZetel, fractieZetelPersoon, fractieZetelVacature, persoon, persoonContactinformatie, persoonGeschenk, persoonLoopbaan, persoonNevenfunctie, persoonNevenfunctieInkomsten, persoonOnderwijs en persoonReis)
2. UITGESTELD: Data ondersteunend aan het werkproces van de Griffie. (Entiteiten: activiteit, activiteitActor, agendapunt, besluit, document, documentActor, documentVersie, kamerstukdossier, reservering, stemming, zaak, zaakActor en zaal.)
3. Verslag & Vergadering (Entiteiten: verslag en vergadering)

-	Redactie: Dit blijft een Proof Of Concept. Afnemers zullen steeds minder Personen, Fracties en Commissies zelf hoeven te koppelen.
-	Standaard disclaimer: 
“Het is gebruikers toegestaan de informatie en gegevens van deze internetsite met bronvermelding over te nemen voor eigen gebruik door deze te kopiëren, uit te printen of op te slaan. Het is niet toegestaan de verstrekte informatie en gegevens evenals de ontwerpen en symbolen van de Tweede Kamer der Staten-Generaal te gebruiken voor doeleinden waarvoor het ongepast is, of in gevallen waarin de kans bestaat dat er misverstanden over de oorsprong kunnen ontstaan, dan wel in gevallen waarin men doet voorkomen dat het door de Tweede Kamer der Staten-Generaal is geautoriseerd.”
