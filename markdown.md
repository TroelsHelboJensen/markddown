# Grænsefladebeskrivelser
Der udstilles en række services hvis primære beskrivelse vil være dækket af den dokumentation der er tilgængelig på [SwaggerHub](https://app.swaggerhub.com/apis-docs/PensionsInfo.dk/PensionsInfo-Web-API-V1/v1).

Bemærk at API'erne til PensionsInfo.dk er private og der skal derfor gives adgang til SwaggerHub for at se dokumentationen.

Herunder er en generel introduktion til hvorledes der kan interageres med systemet og hvad de overordnede krav for en sådan interaktion er. De fleste pensionsudbydere benytter en dataleverandør som hub eller gateway til al kommunikation til og fra PensionsInfo.dk. I det efterfølgende vil begge omtales under ét og benævnes dataleverandør.

Generelt udstilles services af enten dataleverandør eller af PensionsInfo.dk. De efterfølgende afsnit specificerer hvilke services der udstilles af dataleverandører, og hvilke der udstilles af PensionsInfo.dk.


# Transaktioner udstillet af dataleverandør

En dataleverandør leverer overordnet set to typer af data til PensionsInfo:
- Oplysninger om kundebestand (i form af en liste af CPR-numre)
- Pensionsoplysninger om en kunde (detaljerede oplysninger om kundens aftaler hos pensionsudbyderen)

## Tabeloversigt
|Transaktionsnr.|Dansk beskrivelse|Engelsk beskrivelse|Svartransaktionsnr.
|-|-|-|-
|60|Anmod om pensionsoplysninger|Get pension plans|65/66|
|110|Send til rådgiver|Send to advisor|115|
|210|Send til rådgiver med samlever|Send to advisor with spouse|215|

## Sekvensdiagrammer
