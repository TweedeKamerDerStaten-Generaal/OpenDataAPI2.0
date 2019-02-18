# OpenDataAPI2.0
De nieuwe versie van de Open Data API, gepland voor livegang in april 2019. Deze nieuwe versie gaat de datakwaliteit problemen oplossen van de huidige productie omgeving. Daarnaast krijgen de API's een nieuwe versie en wordt het informatiemodel aangepast. De problemen van de productie omgeving worden hier niet geregistreerd.

Deze GitHub pagina is een Proof Of Concept (PoC) die gedaan wordt om met externe afnemers van het Open Data Portaal (opendata.tweedekamer.nl) een centrale issue tracker te faciliteren. Deze PoC wordt in april 2019, na live-gang, geëvalueerd. 

Externe afnemers kunnen na registratie toegang krijgen tot de acceptatieomgeving, dit betreft 2 API's:
- OData V4
- SyncFeed (Atom 1.0)

Documentatie van de nieuwe API's en het informatiemodel is te vinden op:
https://opendata.tweedekamer.nl/documentatie/api-en-informatiemodel-veranderingen-april-2019-release

Bevindingen m.b.t. de volgende onderwerpen kunnen op deze issue tracker ingediend worden:
-	Datakwaliteit
-	Duidelijkheid documentatie
-	Performance
-	API technische bevindingen:
  - OData
  - SyncFeed

Let op:
-	Wij gaan nog releases doen op Acceptatie zodra dit opportuun is. Hiervan houden we de deelnemers zo goed mogelijk van op de hoogte via e-mail.
-	Bron-systemen kunnen tevens nog releases doen, hoewel wij niet verwachten dat dit effect heeft op de afnemers kunnen we dit nog niet uitsluiten.
-	Data volledigheid op acceptatie per entiteit:
1. Personen (incl geschenken, reizen, nevenfuncties en CV), Commissies en Fracties betreft een momentopname (snap-shot), dit wordt niet near-time bijgewerkt. (Entiteiten: commissie, commissieContactinformatie, commissieZetel, commissieZetelVastPersoon, commissieZetelVastVacature, commissieZetelVervangerPersoon, commissieZetelVervangerVacature, fractie, fractieAanvullendGegeven, fractieZetel, fractieZetelPersoon, fractieZetelVacature, persoon, persoonContactinformatie, persoonGeschenk, persoonLoopbaan, persoonNevenfunctie, persoonNevenfunctieInkomsten, persoonOnderwijs en persoonReis)
2. Verslag & Vergadering: Dit betreft een momentopname (snap-shot), dit wordt niet near-time bijgewerkt. (Entiteiten: verslag en vergadering)
3. De overige entiteiten zullen near-time synchroon gehouden worden met het bronsysteem. (Entiteiten: activiteit, activiteitActor, agendapunt, besluit, document, documentActor, documentVersie, kamerstukdossier, reservering, stemming, zaak, zaakActor en zaal.)
-	Redactie: Dit blijft een Proof Of Concept. Afnemers zullen steeds minder Personen, Fracties en Commissies zelf hoeven te koppelen. Tijdens de acceptatiefase gaan we dit verder testen.
-	Standaard disclaimer: 
“Het is gebruikers toegestaan de informatie en gegevens van deze internetsite met bronvermelding over te nemen voor eigen gebruik door deze te kopiëren, uit te printen of op te slaan. Het is niet toegestaan de verstrekte informatie en gegevens evenals de ontwerpen en symbolen van de Tweede Kamer der Staten-Generaal te gebruiken voor doeleinden waarvoor het ongepast is, of in gevallen waarin de kans bestaat dat er misverstanden over de oorsprong kunnen ontstaan, dan wel in gevallen waarin men doet voorkomen dat het door de Tweede Kamer der Staten-Generaal is geautoriseerd.”
