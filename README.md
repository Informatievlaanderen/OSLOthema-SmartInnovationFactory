# OSLO Verkeersmeldingen

## Inleiding
<p>
        Dit document beschrijft het implementatiemodel Verkeersmeldingen (vroeger: Smart Innovation Factory).
        Dit model beantwoordt de vraag over hoe het corresponderende domeinmodel in de praktijk kan toegepast worden.
        Daarbij worden de beperkingen (kardinaliteiten en codelijsten) toegelicht en de overeenkomstige (RDF) termen opgelijst.
    </p>
    <p>
        De kern van dit model is de klasse Observatie, die fungeert als centrale verbinding tussen een verkeersmelding en-meting.
        Observatie is ontworpen om informatie te verzamelen over een geobserveerd object dat door een (verkeers)melding als doelwit wordt beschouwd.
        Voor meer details, zie het <a href="https://data.vlaanderen.be/doc/applicatieprofiel/observaties-en-metingen/">OSLO-applicatieprofiel Observaties en Metingen</a>.
        In geval van OSLO-Verkeersmeldingen kan het geobserveerde object  verschillende vormen aannemen: een verkeersobject zoals een voertuig of verkeersborden,
        een verkeerssituatie zoals filevorming of sluipverkeer, en mobiliteitshinder, zoals een afgesloten straat.
    </p>
    <p>
        Daarnaast kan de observatie betrekking hebben op verkeersmetingen, waarbij gegevens worden verzameld door sensoren volgens een vastgelegde observatieprocedure.
        Deze procedure zorgt voor consistentie en nauwkeurigheid in het verzamelen van data. Elke observatie maakt deel uit van een observatieverzameling,
        die een groter beeld van de verkeerssituatie biedt.
        Zie ook het <a href="https://data.vlaanderen.be/doc/applicatieprofiel/verkeersmetingen/">OSLO-applicatieprofiel Verkeersmetingen</a> voor aanvullende informatie.
        Het model biedt flexibiliteit om diverse verkeerssituaties te accommoderen en heeft de potentie om geïntegreerd te worden met contextuele data zoals camerabeelden,
        luchtvervuilingsmetingen en ongevallendata (dit kan een relevant vervolgtraject zijn).
    </p>
    <p>
        Bovendien kunnen observaties, meldingen en verkeersmetingen behandeld worden als een Zaak via <a href="https://data.vlaanderen.be/doc/applicatieprofiel/dossier/">OSLO-Dossier</a>,
        waardoor elke casus afzonderlijk opgevolgd kan worden.
        Tot slot ondersteunt dit implementatiemodel niet alleen het beheer van verkeersinformatie en het verbeteren van de besluitvorming,
        maar biedt het ook de mogelijkheid om beter geïnformeerde beslissingen te nemen en een efficiënter verkeersmanagement te realiseren,
        in lijn met <a href="https://data.vlaanderen.be/doc/applicatieprofiel/besluit-mobiliteit/">OSLO-Besluit Mobiliteit</a>.
    </p>

## Verslagen en presentaties

De verslagen en presentaties van dit traject kan je terugvinden op het [Standaardenregister](https://data.vlaanderen.be/standaarden).

## In deze repository

EAP-files met de UML-diagrammen.\
Configuratie en bestanden voor het publiceren van de specs in de folders config, site-skeleton en templates.\
Een [changelog](./CHANGELOG) met wijzigingen tov vorige versies.\
Diverse resources:
- Een overzicht van gebruikte [bronnen]() (standaarden, implementaties, regelgeving).
- Het [modelleringsrapport](https://github.com/Informatievlaanderen/OSLOthema-SmartInnovationFactory/blob/main/resources/20250717-Modelleerrapport-SIF.pdf).
- Een map met [datavoorbeelden](https://github.com/Informatievlaanderen/OSLOthema-SmartInnovationFactory/tree/main/resources/datavoorbeelden).

## Issues

Via de tab [issues](https://github.com/Informatievlaanderen/OSLOthema-SmartInnovationFactory/issues) kan je opmerkingen en feedback over het model geven.

## Publicaties

Volgende specificaties worden met de volgende status voorgelegd op WG datastandaarden van januari 2026.

<table> <thead><tr> <td>Verkeersmeldingen (voormalig: SmartInnovationFactory)</td> <td>KandidaatStandaard</td> <td>20250801</td> <td><a href="https://data.vlaanderen.be/standaarden/implementatiemodel-verkeersmeldingen">Link</a></td> </tr> </tbody> </table>
