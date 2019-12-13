# Utvärdera webbplatsers laddningstid och användbarhet

## Urval

För denna uppgift valde jag samma sidor som jag undersäkte för färg och känsla uppgiften. Jag tänkte att det är ett lämpligt val att fortsätta att jämföra dessa sidor.

## Metod

Verktyg som använder var Google PageSpeed Insights och Chrome devtools för att mäta laddningstid, antalet resusrser laddade samt storleken på sidan i megabyte.

## Resultat

3 sidor per plattform analyserades. Rådatan av mätningarna kan ses på <a href="https://docs.google.com/spreadsheets/d/1a2RPyYsP2yWv2Elv2vxJhG9QDeRZzMCtPKpitySEpoE/edit?usp=sharing">denna länk</a>. Sidorna som analyserades var:

1: Hemsidan
2: Inloggningssidan
3: Sidan för det först annonserade spelet på hemsidan

<u>Steam</u><br><br>'

Steams hemsida hade en laddningstid på 53.1 sekunder. Antalet resurser som sidan laddede i snitt var 236 resusrer med en total storlek på 12.2 mb. På Pagespeed Insights fick sidan 77 och 45 i desktop respektive mobil betyg.

Inloggningssidan hade en laddningstid på 1.0 sekunder. Antalet resurser som sidan laddede i snitt var 42 resusrer med en total storlek på 12.2 mb. På Pagespeed Insights fick sidan 95 och 68 i desktop respektive mobil betyg.

Spelsidan hade en laddningstid på över 3 minuter. Antalet resurser som sidan laddede i snitt var 148 resusrer med en total storlek på över 100 mb. På Pagespeed Insights krashade sidan och gav inget resultat vid flera försök.

<img src="../htdocs/img/steamkmom04.png">

<u>Epic Games Store (EGS hädanefter) </u><br><br>
EGS hemsida hade en laddningstid på 2.5 sekunder. Antalet resurser som sidan laddede i snitt 74 resusrer med en total storlek på 11.9 mb. På Pagespeed Insights fick sidan 64 och 24 i desktop respektive mobil betyg.

Inloggningssidan hade en laddningstid på 3.0 sekunder. Antalet resurser som sidan laddede i snitt var 37 resusrer med en total storlek på 1.5 mb. På Pagespeed Insights fick sidan 95 och 65 i desktop respektive mobil betyg.

Spelsidan hade en laddningstid på över 3 minuter. Antalet resurser som sidan laddede i snitt var 160 resusrer med en total storlek på 29.6 mb. På Pagespeed Insights fick sidan 26 och 30 i desktop respektive mobil betyg.
<img src="../htdocs/img/egskmom04.png">

<u>GOG</u><br><br>
GOGs hemsida hade en laddningstid på 18.3 sekunder. Antalet resurser som sidan laddede i snitt var 97 resusrer med en total storlek på 5.2 mb. På Pagespeed Insights fick sidan 88 och 29 i desktop respektive mobil betyg.

Inloggningsidan på GOG var som en popup man fyllde i. Därför är jag osäker på hur unika dessa mätningar är jämfört med hemsidan. I alla fall blev resultaten det följande:
En laddningstid på 10.6 sekunder. Antalet resurser som sidan laddede i snitt var 101 resusrer med en total storlek på 5.2 mb. På Pagespeed Insights fick sidan 88 och 29 i desktop respektive mobil betyg.

Spelsidan hade en laddningstid på 11.0 sekunder. Antalet resurser som sidan laddede i snitt var 115 resusrer med en total storlek på 7.5 mb. På Pagespeed Insights fick sidan 32 och 5 i desktop respektive mobil betyg.
<img src="../htdocs/img/gogkmom04.png">

## Analys

Det var stora skillnade i laddningstider och betyg mellan de olika plattformerna. Steam hade snitt mycket mer resurser som laddades in på sidan jämfört med de andra två sidorna. Detta speglades också i den väldigt mycket längre laddningtid hemsidan fick gentemot EGS och GOG. Däremot fick Steam ett bätte pagespeed betyg än EGS hemsida som hade en mycket snabbare laddningstid. Jag blev ganska förvånad över detta, och ännu mer så när GOG som hade "sämre" resultat i devtools än EGS också slog EGS i pagespeed betyg. När det kom till inloggning var steam vinnaren med 1 sekund laddning i snitt. Detta var följt av EGS med en 3 sekunders laddningstid. GOG å andra sida hade en ganska mycket längre laddningstid, men som nämnt i resultatdelen så var inloggningen en popup på hemsidan, så det kan vara att hela sidan ändå renderades vilket medför de förlängda laddningtiderna.<br>

Spelsidorna var en liten chock. Både steam och EGS hade laddningstider på över 3 minuter. Steam bara fprtsatte att öka på storlek och tid, men EGS stannade vid 29.6 mb. Detta att jämföras med GOGs 11 sekunders laddningstid och 7.5 mb storlek. Jag antar att detta är p.g.a att steam och EGS har vidoes som spelas upp på deras sidor, medans GOG har GIFs. Steams sida kraschade i pagespeed, EGS fick ett betyg på 26 och 30 för desktop respektive mobil, och av någon anledning fick GOG också ett lågt betyg (trots dess mycket bra devtools resultat) på 32 och 5.

Överlag så har GOG lyckats hålla nere storleken på sina sidor vilket också speglar sig i mindre laddningstider. Steam hade en överlägset mest "överbefolkad" hemsida men bäst inloggning. EGS hade OK värde för det mesta, förutom laddningstiden på sin spelsida. Det jag tänker mig skulle kunna förbättra resultaten är att ha extert länkade video som anvädaren kan hänvisas till men detta kan ju i sin tur leda till mindre trafik på sidan. En annan uppenbar förbättring är att ha mer webbvänliga bildformat om detta inte har implementerats redan, då alla dessa platformer har enorm många bilder de visar för deras spelutbud.

Jag skulle sätta en egen gräns för vad jag upplever som en snabb sida vid några sekunder max. För det mesta upplevdes alla dessa sidor som snabba, även om resultaten emotsäger detta i vissa fall.

## Övrigt

Hatem Mohi El Din. Enskild rapport.
