# Over Open Registers

OpenRegisters is een innovatief framework gebaseerd op Symfony, ontworpen om zowel object storage als API's op een fenomenaal snelle wijze te bieden. Dit wordt bereikt door binnenkomende objecten direct op te slaan in een object store (zoals MongoDB, CouchDB, Amazon S3, en de Google en Azure varianten daarvan), in plaats van in traditionele relationele databases. Hierdoor kunnen registers functioneren als 'adaptors' bovenop een open source object store, wat leidt tot een reeks van voordelen voor overheidsinstanties.

## Kernvoordelen

- **Efficiëntie en Snelheid:** Door gebruik te maken van object stores, biedt OpenRegisters snellere dataopslag en -toegang.
- **Onderhoud en Ontwikkeling:** API's zoals ZGW zijn compacter, waardoor ze sneller en eenvoudiger te onderhouden en te ontwikkelen zijn.
- **Federatie:** Volledige ondersteuning voor federatie via NLX/FSC, wat compatibiliteit met federale systemen waarborgt.
- **Virtuele Registers:** Mogelijkheid om meerdere losse registers te combineren tot één virtueel register, essentieel voor projecten zoals OpenWoo.app en OpenCatalogi.nl.
- **Gedeelde Functionaliteit:** Inclusief logging en verwerking, autorisatie & authenticatie, notificatie, filtering, en uitbreidbaarheid voor alle registers.
- **Federaal Doorvragen:** Ondersteunt het opvragen van gegevens uit één register via een ander, zoals de integratie van BRP-gegevens bij klantbevragingen.
- **Importeren van VNG API specificaties:** Door de ondersteuning van OAS3 kunnen door de VNG opgestelde API-specifiacties rechtreeks worden geïmporteerd en uitgeleverd 
- **Lage beheer, implementatie en hosting kosten:** Doordat OpenRegisters ieder register als adaptor ziet in plaats van een volledige applicatie kunnen er gemakkelijk meerdere registers worden geleverd vanuit één installatie.  
- **Multitenant:** Geavanceerde mogelijkheid om meerdere tenants (organisaties) vanuit één installatie te draaien maakt OpenRegisters de ideale oplossing voor (SAAS) leveranciers en samenwerkingsverbanden. 
- *Gemaakt voor GROTE data sets:** OpenRegisters is speciaal ontworpen om efficiënt om te gaan met grote hoeveelheden data. Het maakt gebruik van de schaalbaarheid en snelheid van object storage om grote datasets snel en betrouwbaar te verwerken, waardoor het ideaal is voor overheidsregisters die te maken hebben met aanzienlijke hoeveelheden informatie.
- *Snel als de bliksem:** De architectuur van OpenRegisters, in combinatie met de backend van object storage, zorgt voor ongeëvenaarde snelheden bij dataopslag en -toegang. Dit resulteert in een snellere respons voor eindgebruikers en efficiëntere datahandeling, wat cruciaal is voor de prestaties van overheidsdiensten.

## Installatie

### Lokale Installatie
#### Vereisten

- PHP 7.4 of hoger
- Symfony 5 of hoger
- Toegang tot een ondersteunde object store (MongoDB, CouchDB, Amazon S3, Google Cloud Storage, Azure Blob Storage)

#### Stap-voor-stap Installatie

1. Clone het OpenRegisters repository: `git clone https://github.com/ConductionNL/OpenRegisters.git`
2. Installeer de benodigde afhankelijkheden: `composer install`
3. Configureer uw omgevingsvariabelen (`.env`) met de nodige gegevens voor uw object store.
4. Volg de specifieke configuratie-instructies voor de gekozen object store.

## Gebruik

Na installatie en configuratie kunt u beginnen met het definiëren van uw registers binnen OpenRegisters. Dit houdt in dat u de structuur van uw data en de API-endpoints specificeert, waarna OpenRegisters de rest afhandelt.

## Bijdragen

Bijdragen aan OpenRegisters is welkom! Of het nu gaat om het rapporteren van een bug, het voorstellen van een nieuwe feature, of het indienen van code wijzigingen, bekijk onze `CONTRIBUTING.md` voor meer informatie over hoe u kunt bijdragen.

## Licentie

OpenRegisters is uitgegeven onder een EUPL 1.2 licentie. Zie het (`LICENSE.md`)[`LICENSE.md`] bestand in onze GitHub repository voor meer details.

## Contact

Voor meer informatie over OpenRegisters en hoe u het kunt inzetten binnen uw organisatie, neem contact met ons op via [info@conduction.nl](mailto:info@conduction.nl).

