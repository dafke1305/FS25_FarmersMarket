# Farmers' Market — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.0.1** uit [deze release](https://github.com/dafke1305/FS25_FarmersMarket/releases/tag/v1.0.0.1). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_FarmersMarket.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Goederen verkopen

1. Open **ESC > Farmers' Market > Nieuw aanbod / New offer**.
2. Kies een herkende bron van je eigen boerderij, het beschikbare product, de hoeveelheid en de looptijd. Ondersteunde voorraad kan bestaan uit bulk, pallets/bigbags en balen; de markt moet de opslag herkennen.
3. Controleer referentie en prijs. De **server kiest het beste geldige verkooppunt en zet de goederenprijs vast bij publiceren**. De prijsweergave is geen vrij invulbaar verkoopprijsveld.
4. Publiceer eenmaal en wacht op bevestiging. De goederen verdwijnen uit de bruikbare voorraad en gaan naar het beschermde virtuele marktdepot. Maak pallets/balen eerst los van voertuigen of werktuigen.
5. Beheer je aanbiedingen via **Mijn aanbod / My offers**. Intrekken van een onverkocht aanbod geeft de onverkochte depotgoederen terug. Verkoop of gebruik gereserveerde goederen niet ondertussen via een andere route.

## Kopen en bezorgen

1. Selecteer onder **Markt / Market** een aanbod, lees hoeveelheid/prijs en kies een geschikte bestemming met voldoende ruimte.
2. Kies de beschikbare afleverwijze: **Zelf ophalen / Collect yourself**, **Transport regelen / Arrange transport** of **Expresslevering / Express delivery**. Controleer de bevestiging voordat je geld vastlegt.
3. Bij zelf ophalen gebruik je eigen materieel en betaal je je eigen bedrijfskosten. Er is geen vervoerdersloon, transportbijdrage of subsidie.
4. Spelerstransport verschijnt in het gewone **Contracten**-menu. De vervoerder accepteert de opdracht en volgt de laad-/ophaalinstructies met passend materieel. Gebruik de toegewezen vervoerdersboerderij en de gekozen bestemming.
5. Expresslevering plaatst goederen rechtstreeks in een geschikte gekozen opslag, zonder transportopdracht. Een geschikte, nog niet geladen bestaande aankoop kan ook worden omgezet: dan betaal je alleen de expresskosten en niet nogmaals de goederen. Geladen goederen of een opdracht die een andere vervoerder al claimde kunnen dit blokkeren.

Volg voor fysieke levering de laadinstructies en breng de vracht naar de gekozen bestemmingszone. Deze versie controleert de levering automatisch. Blijf als vervoerder nabij en wacht op afronding. Een deellevering rondt de volledige opdracht pas af wanneer alle vereiste goederen zijn aangekomen.

## Beheer en problemen oplossen

- **Voorraad vernieuwen / Refresh inventory** vernieuwt de bronnen. Een bezette oorspronkelijke laadplek, niet-ondersteunde opslag, te weinig capaciteit of een lopende overdracht kan de volgende stap blokkeren.
- Aanbod hoort bij een boerderij; voorraad van een andere boerderij is niet jouw eigen voorraad. Looptijden en deadlines gebruiken speltijd.
- Depot, vracht en geld moeten samen kloppen in de savegame. Maak vóór beheerdersherstel een volledige saveback-up.
- **Verify and resume**, **Restore goods** en **Recover depot** zijn gerichte herstelacties, geen gewone verkoopknoppen. Lees de bevestiging en controleer eerst de oorspronkelijke goederen- en betalingsstatus.
- **Admin: force remove** stopt verwerking en verwijdert lijst-/contractregels. Het geeft of verwijdert **geen** goederen, betaalt niemand en stort gereserveerd geld niet terug. Gebruik dit niet als gewone annulering of voorraadreset.
- Is veilig herstel niet aantoonbaar, meld dan logs en aanbod-ID in plaats van herhaald vracht aan te maken of betalingen opnieuw uit te voeren.

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_FarmersMarket/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
