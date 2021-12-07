# Riktlinjer för hanteringen av öppen källkod

Dessa riktlinjer är framtagna för att gälla öppen källkod hos Sundsvalls kommun.

## Bakgrund

I takt med att Sveriges kommuner ökar digitaliseringstakten och sitt användande av öppen källkod, så har vi ett behov av att sammanställa en riktlinje för hur exempelvis anskaffning, utveckling och publicering av tjänster baserade på just öppen källkod skall gå till.

## Skapande och publicering av öppen källkod

### Syftet med publicering

* Underlätta utveckling 
* Främja samverkan i ett ekosystem
* Uppmuntra till återanvändning kommuner emellan

### Checklista inför första publicering

Följande lista är en anpassning av de punkter som Försäkringskassan tar upp i sin riktlinje. Vi anser att de utgör en bra utgångspunkt även för vår verksamhet.

* Innehållet ska utifrån gällande informationsklassningsmodell och säkerhetsskydd vara lämpligt för publicering.
* Källkod skall vara parametriserad och får inte innehålla hårdkodade konfigurationsparametrar.
* Källkoden får inte omfattas av en licensmodell som omöjliggör publicering.
* Källkodens härkomst skall vara känd
* Om tredjepartsprogramvara används i källkodsform måste licensformerna vara kompatibla och ingå till fullo eller i enlighet med tredje parts krav.
* Kvaliteten på publicerat innehåll ska vara hög och inte innehålla irrelevant information.
* Publicerat material får inte utsätta kommunen för ökad risk eller på annat sätt påverka kommunens anseende negativt.
* Licensformen ska vara bestämd och vara godkänd av Open Source Initiative.
* Säkerhetsbedömning av källkod ska göras och åtgärder ska vidtas för att säkra kvalitet.

### Hur publicerar vi

Vi har valt GitHub som den plats där vi publicerar öppen källkod. För de tjänster som kan anses lämpliga för publicering, enligt checklistan ovan, gäller att den huvudsakliga utvecklingen skall ske mot ett publikt kodarkiv (repository) under vår organisation på [https://github.com/OpenSundsvall]. Anledningen till denna strategi är att öka möjligheten till samverkan och stimulerande av livskraftiga ekosystem. Genom att inte låsa in utvecklingen utom räckhåll för externa parter, ökar vi möjligheten för dessa att bidra till och dra nytta av det arbete vi gör.

För publicering har två huvudsakliga licensformer valts ut för vårt arbete.

De tjänster som levereras skall i första hand publiceras under licensformen MIT för att tillåta ett fritt återanvändande och möjliggöra för delaktighet från en större andel potentiella aktörer.

Tjänster som å andra sidan kan anses utgöra en del av en större sammanhängande plattform, skall däremot i första hand publiceras under licensformen AGPL-3 som verkar mer skyddande för kommunens investeringar i öppen programvara.

### Checklista inför löpande uppdatering

För att säkerställa bibehållen kvalitet gäller följande:
* Kod är byggd enligt gällande standard med en kvalitet som tål öppenhet
* Kod och tester är granskade av annan teammedlem
* Feature-brancher stängda och allt mergat till main
* Att koden levererar önskad funktion skall vara avstämd med beställare
* Sandbox skall vara uppdaterad
* Design- och API-dokumentation skall vara uppdaterad

### Hantering av återkoppling från andra

Rapporterade buggar och initierade pull requests prioriteras i respektive utvecklingsteams löpande arbete.

## Vidmakthållande av riktlinjen

Hur löpande förbättringar samt kvalitetskontroll av denna riktlinje skötas måste utredas.

Copyright (c) 2021 Sundsvalls kommun
