<h1 id="RoadmapDK2022/2023-Roadmap">
    Concept Roadmap 2022/2023
</h1>
<ul>
    <li>
        &gt; Toevoegen RESTful API profiel aan Digikoppeling
    </li>
    <li>
        &gt; Signing &amp; Encryptie toevoegen aan RESTful API profiel
    </li>
    <li>
        &gt; Aanvulling Digikoppeling governance
    </li>
    <li>
        &gt; Verbeteren Informatievoorziening / Nieuwe wijze van Publiceren
    </li>
    <li>
        &gt; Best Practice Identificatie van Organisaties,
        Organisatieonderdelen en voorzieningen
    </li>
    <li>
        &gt; Analyse knelpunten Routering en Intermediairs in gegevensverkeer
    </li>
    <li>
        &gt; Verkennen mogelijk gebruik ebMS3/AS4
    </li>
    <li>
        &gt; Interoperabiliteit platformen WUS bij gebruik MTOM in combinatie
        met WS-Security (signing)
    </li>
    <li>
        &gt; Doorontwikkeling RESPEC/Digikoppeling template voor publicatie van
        specificaties
    </li>
    <li>
        &gt; Update Beheermodel / aansluiting op Logius Standaarden BOMOS
        generiek beheer model &amp; governance
    </li>
</ul>
<h2 id="RoadmapDK2022/2023-Achtergrond">
    Achtergrond
</h2>
<p>
    Digikoppeling bevordert interoperabiliteit door digitale
    berichtuitwisseling te standaardiseren. Hierbij maakt Digikoppeling gebruik
    van internationale open standaarden. Daarmee is Digikoppeling een
    belangrijke pijler voor de Generieke Digitale Infrastructuur (GDI) die
    publieke dienstverlening en uitvoering mogelijk maakt.
</p>
<p>
    Digikoppeling bestaat uit een set standaarden die het mogelijk maakt om
    berichten tussen overheidsinstellingen en organisaties die met of binnen de
    overheid digitaal informatie willen uitwisselen, op gestandaardiseerde
    wijze veilig uit te wisselen. Gebruik van deze standaarden wordt
    ondersteund door de Digikoppeling voorzieningen; de Centrale OIN
    Raadpleegvoorziening, de Compliance voorzieningen en het CPA Register. Dit
    ten behoeve van ontwikkeling en implementatie van systemen die
    Digikoppeling toepassen. Daarmee is Digikoppeling de invulling van de
    servicegerichte architectuur die de Nederlandse Overheid Referentie
    Architectuur (NORA) voorschrijft.
</p>
<p>
    Door middel van deze roadmap wil de productgroep Digikoppeling richting
    geven aan het product voor de komende jaren en duidelijkheid geven over de
    toekomst van Digikoppeling.
</p>
<h3 id="RoadmapDK2022/2023-Doelroadmap">
    Doel roadmap
</h3>
<p>
    Dit document is gericht op het voorbereiden van de tactische keuzes voor
    doorontwikkeling van de Digikoppeling standaard én voorzieningen in de
    komende jaren. Hierbij is rekening gehouden met de vele ontwikkelingen die
    spelen rond Digikoppeling zoals
</p>
<ul>
    <li>
        het toenemende gebruik van op REST gebaseerde webservices
    </li>
    <li>
        het vernieuwde OIN beleid
    </li>
    <li>
        de behoefte met betrekking tot het anders aanbieden van de informatie
        over Digikoppeling.
    </li>
</ul>
<p>
    De Roadmap Digikoppeling heeft als doel te beschrijven hoe de Digikoppeling
    standaard en de voorzieningen in de periode van 2022 t/m 2023 meegroeien
    met de behoeften van haar gebruikers. Daarnaast wordt er in dit document
    een terugblik gegeven op de vorige roadmap die liep van 2020 t/m2021.
</p>
<h3 id="RoadmapDK2022/2023-TotstandkomingRoadmap">
    Totstandkoming Roadmap
</h3>
<p>
    De samenstelling van deze Roadmap is opgesteld door de productgroep
    Digikoppeling van Logius. Hierbij is gekeken naar de (toekomstige)
    ontwikkelingen rond de Digikoppeling standaard, vragen van het Technisch
    Overleg Digikoppeling en lopende vragen en wensen vanuit de markt over de
    voorzieningen. Vervolgens is een aantal onderwerpen benoemd die als project
    opgepakt zullen worden en is er gerangschikt op prioriteit.
</p>
<p>
De onderwerpen voor het standaardendeel van de roadmap zijn in    <strong>DATUM</strong> besproken door het Technisch Overleg (TO) en de
    concept roadmap is in <strong>DATUM</strong> ter vaststelling ingediend. De
    leden van het TO konden hier zowel mondeling als schriftelijk op reageren
    en deze reacties zijn meegenomen in voorliggende definitieve versie.
</p>
<h3 id="RoadmapDK2022/2023-PositioneringDigikoppeling">
    Positionering Digikoppeling
</h3>
<p>
    De scope van Digikoppeling zal niet veranderen:
    <br/>
    Digikoppeling maakt het mogelijk dat organisaties die, met of binnen de
    overheid, digitaal informatie willen uitwisselen dit op een
    gestandaardiseerde wijze veilig kunnen doen. Het is in beginsel geen
    infrastructuur maar een set aan afspraken over het gebruik van
    internationale open standaarden. Digikoppeling kent wel ondersteunende
    voorzieningen maar deze zijn gericht op ondersteuning van het
    ontwikkelproces bij implementatie van Digikoppeling en niet op directe
    ondersteuning van productie-situaties zelf.
</p>
<p>
    Interoperabiliteit is gewaarborgd omdat Digikoppeling bestaat uit
    standaarden die breed in de markt worden ondersteund en omdat voor
    Digikoppeling specifieke opties zijn gekozen.
    <br/>
    Digikoppeling is daarmee een essentiële bouwsteen van de elektronische
    overheid en vult de door NORA voorgeschreven servicegerichte architectuur
    in.
</p>
<p>
    De Digikoppeling Standaard is op dit moment afgebakend op basis van
    berichtenuitwisseling, op basis van ebMS of WUS. Binnen de Nederlandse
    Overheid vinden steeds meer ontwikkelingen plaats op het gebied van
    informatie-uitwisseling op basis van RESTful Api’s. Dit roept mogelijk
    vragen op wanneer welk protocol gebruikt moet of mag worden. In de roadmap
    2022-2023 is aandacht voor de wijze waarop Digikoppeling omgaat met deze
    ontwikkeling.
</p>
<h2 id="RoadmapDK2022/2023-OnderwerpenDigikoppelingStandaarden">
    Onderwerpen Digikoppeling Standaarden
</h2>
<p>
    In eerdere edities van de Digikoppeling roadmap liepen de onderwerpen met
    betrekking tot de Digikoppeling standaarden en aanverwante voorzieningen
    door elkaar heen. In deze editie heeft de productgroep Digikoppeling ervoor
    gekozen deze onderdelen afzonderlijk weer te geven. De onderwerpen van de
    roadmap Digikoppeling voorzieningen staan
    <a
        href="https://logius.nl/diensten/digikoppeling/documentatie/digikoppeling-roadmap-2020-2021#onderwerpen-digikoppeling-voorzieningen"
        rel="nofollow"
    >
        hier
    </a>
    .
</p>
<h3 id="RoadmapDK2022/2023-&gt;ToevoegenRESTfulAPIprofielaanDigikoppeling">
    &gt; Toevoegen RESTful API profiel aan Digikoppeling
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Digikoppeling maakt gebruik van EBMS, WUs en GB om informatie uit te
    wisselen tussen overheden. Al enige jaren is het echter gangbaar om
    informatie uit te wisselen door bronnen direct te raadplegen/wijzigen door
    gebruik te maken van een alternatief architectuurpatroon REST
    (REpresentational State Transfer). REST maakt opgang binnen de Nederlandse
    overheid.
    <br/>
    Wanneer het best welk architectuurpatroon kan worden toegepast en hoe dat
    zich verhoudt tot de ‘pas toe of leg uit’ –verplichting om Digikoppeling
    toe te passen, is voor veel partijen nog onduidelijk. Logius ziet het als
    haar taak om de situatie rondom het gebruik van Digikoppeling en REST voor
    iedereen inzichtelijk te maken.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Digikoppeling heeft in 2020 een Digikoppeling REST API profiel opgesteld
    dat is gebaseerd op de ‘Pas toe of leg uit ‘-standaard: API design Rules.
    Deze laatste komt van het Kennisplatform API’s en is sinds september 2020
    bij Logius in beheer genomen. De uitbreiding van Digikoppeling met een REST
    API profiel is voorgelegd aan het forum Standaardisatie voor opname op de
    pas-toe-of-leg-uit lijst. Bij een positief doorlopen procedure (en na
    goedkeuring door OBDO) zal Digikoppeling begin 2022 het REST API profiel
    bevatten.
    <br/>
    De Digikoppeling achitectuurdocumentatie wordt dan ook aangepast zodat
    inzichtelijk wordt wanneer het best welk koppelvlak kan worden toegepast.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een Digikoppeling standaard waar, naast ebMS, WUS en GB, ook een profiel
    voor Digikoppeling RESTFul API’s is opgenomen.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q1 2022
</p>
<h3
    id="RoadmapDK2022/2023-&gt;Signing&amp;EncryptietoevoegenaanRESTfulAPIprofiel"
>
    &gt; Signing &amp; Encryptie toevoegen aan RESTful API profiel
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Digikoppeling EBMS &amp; WUS kennen specifieke profielen voor signing &amp;
    encryptie, het huidige Digikoppeling RESTful API profiel kent dit nog niet
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Wanneer het REST API profiel door het OBDO wordt goedgekeurd voor opname op
    de pas-toe-of-leg-uit lijst van het Forum Standaardisatie zal het onderdeel
    signing en encryptie worden ingevuld, hierbij zal worden aangesloten op de
    ontwikkelingen binnen het kennisplatform API's.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een Digikoppeling standaard waarin voor het Digikoppeling REST API profiel
    ondersteuning is voor signing &amp; encryptie.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q2 2022-Q4 2022
</p>
<h3 id="RoadmapDK2022/2023-&gt;AanvullingDigikoppelinggovernance">
    &gt; Aanvulling Digikoppeling governance
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Traditioneel bestond de governance van Digikoppeling uit drie lagen:
    Operationeel (het Technisch Overleg), tactisch en strategisch. Door een
    reorganisatie bij Logius en het verdwijnen van de Digicommissaris zijn die
    laatste twee lagen weggevallen. Om effectief beheer te kunnen voeren is een
    complete governancestructuur noodzakelijk.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Digikoppeling zal een nieuwe tactische en strategische laag inrichten om de
    huidige governance aan te vullen. Het kan dat deze taken belegd worden bij
    reeds bestaande gremia, maar als dit geen optie is, kan Digikoppeling ook
    zelf nieuwe gremia optuigen en faciliteren. Voor invulling van de tactische
    en strategische governance lagen zal gekeken worden of deze gebruik kan
    maken van de MIDO governance voor het GDI. Het heeft de voorkeur om nieuwe
    gremia binnen bestaande structuren te zoeken.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een optimale governancestructuur die weer bestaat uit drie lagen.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q1 2022 – Q4 2022
</p>
<h3
    id="RoadmapDK2022/2023-&gt;VerbeterenInformatievoorziening/NieuwewijzevanPubliceren"
>
    &gt; Verbeteren Informatievoorziening / Nieuwe wijze van Publiceren
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    De digikoppeling documentatie moet eenvoudig toegankelijk zijn. Gebruikers
    moeten gemakkelijk de voor hen relevante onderdelen kunnen vinden en
    benaderen. Informatie staat nu verspreid over een aantal verschillende
    websites waarbij onderliggende relaties niet altijd gelegd worden;
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Digikoppeling onderhoudt de beheerdocumentatie en standaardspecificaties op
    Github; Algemene informatie en vergaderstukken wordt via logius.nl en
    digistandaarden.pleio.nl verstrekt. OIN specficatie en interface worden via
    portaal.digikoppeling.nl gepubliceerd. Tevens publiceert Logius nu een
    source en documentatie voor een aantal producten via gitlab, waaronder ook
    aan digikoppeling gerelateerde diensten.<em> </em>Onderzocht zal worden hoe
    de informatie meer geordend en meer geïntegreerd kan worden aangeboden;
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een omgeving waar alle documentatie m.b.t. de Digikoppeling standaard
    online (in HTML) beschikbaar is. Ook diensten en aanvullende informatie
    worden waar mogelijk via één website gepubliceerd. Wanneer verschillende
    sites gebruikt worden wordt de onderlinge samenhang duidelijk gemaakt zodat
    gebruikers alle informatie rondom de Digikoppeling standaard kunnen vinden.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q1 2022 – Q2 2022
</p>
<h3
    id="RoadmapDK2022/2023-&gt;BestPracticeIdentificatievanOrganisaties,Organisatieonderdelenenvoorzieningen"
>
    &gt; Best Practice Identificatie van Organisaties, Organisatieonderdelen en
    voorzieningen
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Het OIN-beleid is sinds 2016 op het punt van het gebruik van SubOIns voor
    organisatieonderdelen en –voorzieningen verduidelijkt en uitgebreid. Het
    lijkt erop dat het steeds belangrijker wordt om entiteiten in een
    uitwisselketen te kunnen identificeren. Er bestaat tussen organisaties
    verschil in inzicht in de toepassing van identificatie.
</p>
<p>
    Er is behoefte aan inzicht in hoe nu wordt en moet worden omgaan met
    identificatie in uitwisselketens tussen en met overheden.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Inventarisatie hoe organisaties omgaan met identificatie van onderdelen in
    de uitwisselketen. Bepalen welke practices kunnen worden aangeduid als best
    practices voor het omgaan met identificatie.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Best practice beschrijving van Identificatie van Organisaties,
    Organisatieonderdelen en voorzieningen.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q1-Q2 2022
</p>
<h3
    id="RoadmapDK2022/2023-&gt;AnalyseknelpuntenRouteringenIntermediairsingegevensverkeer"
>
    &gt; Analyse knelpunten Routering en Intermediairs in gegevensverkeer
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Het is binnen overheidsketens steeds gebruikelijker om gebruik te maken van
    dienstverlening vanuit de Cloud, en diensten af te nemen van SAAS
    leveranciers. Dit heeft impact op vragen als wat is het endpoint in een
    keten, wie is de oorspronkelijker aanbieder of uiteindelijke ontvanger, hoe
    herken ik die en hoe weet ik dit zeker. Digikoppeling biedt met signing en
    encryptie tools aan, sommige sectoren hebben voorzieningen ontwikkeld, die
    bovenstaande vragen deels beantwoorden, andere partijen zijn zoekende hoe
    om te gaan met de nieuwe situatie.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    In kaart brengen wat de knelpunten zijn bij uitwisselketens met
    transparante en niet-transparante intermediairs. Inventariseren welke
    oplossingen in de praktijk toegepast worden. Onderzoeken welke oplossingen
    uitgewerkt dienen te worden en vervolgens kunnen worden toegepast in
    Digikoppeling.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een analyse van de knelpunten en oplossingsrichtingen, met de impact ervan
    op Digikoppeling.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q1-Q2 2022
</p>
<h3 id="RoadmapDK2022/2023-&gt;VerkennenmogelijkgebruikebMS3/AS4">
    &gt; Verkennen mogelijk gebruik ebMS3/AS4
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    De ebMS2 standaard wordt niet verder doorontwikkeld. Het ligt daarom voor
    de hand om te kijken of ebMS2 vervangen kan worden ebMS3. En dan met name
    het AS4 profiel hierop. Dit is ook onderdeel van de EU eDelivery standaard
    voor gegevensuitwisseling over landsgrenzen heen.
</p>
<p>
    In 2018 heeft Digikoppeling laten onderzoeken of en wanneer het zinnig is
    om ebMS2 vervangen door de nieuwe versie. Naar aanleiding van dat onderzoek
    besloot het TO dat er voorlopig geen directe aanleiding is om ebMS2 actief
    te vervangen.
</p>
<p>
    Begin 2020 is in het TO besloten om ebMS2 weliswaar nog niet actief te
    vervangen, maar dat het wel zinnig is om als Digikoppeling bij te houden
    hoe de ondersteuning van ebMS2, vanuit leveranciers, zich ontwikkeld en als
    eens te verkennen welk ebMS3 profiel eventueel bruikbaar zal zijn binnen de
    Digikoppeling standaard.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Digikoppeling gaat verkennen of het eDelivery ebMS3 AS4 profiel geschikt is
    voor gebruik binnen Digikoppeling en wat daar nog eventueel aan toegevoegd
    dient te worden.
</p>
<p>
    Daarnaast zal Digikoppeling partijen, die ervaring hebben met het opstellen
    van een eigen ebMS3 profiel, uitnodigen om in het TO te komen vertellen hoe
    dit proces is verlopen.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Met bovengenoemde acties heeft Digikoppeling in de 2e helft van 2022 een
    goed beeld van moeilijkheden en mogelijkheden van het gebruik van de ebMS3
    standaard zodat eind 2022 met het TO opnieuw besproken kan worden of en op
    welke termijn het zinnig is om over te gaan op de nieuwe versie.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    Q2-Q4 2022
</p>
<h3
    id="RoadmapDK2022/2023-&gt;InteroperabiliteitplatformenWUSbijgebruikMTOMincombinatiemetWS-Security(signing)"
>
    &gt; Interoperabiliteit platformen WUS bij gebruik MTOM in combinatie met
    WS-Security (signing)
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Bij gebruik van MTOM in combinatie met signing en encryptie zijn er
    verschillen in hoe de verschillende platformen hiermee omgaan in de default
    instellingen en in de mogelijkheden om certificaat informatie wel of niet
    als reference te kunnen specificeren/verwerken;
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Er zal onderzocht worden of aanvullende afspraken in de standaard kunnen
    helpen om de interoperabiliteit op dit punt te vergroten;
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    <em>
        Resultaat is een analyse met indien mogelijk een voorstel voor
        aanvullende afspraken
    </em>
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    <em>Q1-Q2 2022</em>
</p>
<h3
    id="RoadmapDK2022/2023-&gt;DoorontwikkelingRESPEC/Digikoppelingtemplatevoorpublicatievanspecificaties"
>
    &gt; Doorontwikkeling RESPEC/Digikoppeling template voor publicatie van
    specificaties
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Digikoppeling documentatie wordt d.m.v. RESPEC gepubliceerd. RESPEC is een
    hulpmiddel ontwikkeld door W3C voor technische specificaties (respec.org).
    <br/>
    RESPEC wordt doorontwikkeld en de Digikoppeling documentatie tooling zal
    meelopen in deze ontwikkeling om ook nieuwe functionaiteiten te
    ondersteunen;
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Het Digikoppeling RESPEC template zal de ontwikkelingen bij RESPEC volgen;
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Het resultaat is een Digikoppeling RESPEC template dat up to date is met de
    algemene/centrale RESPEC ontwikkeling en dat voldoet aan de
    Digitoegankelijkheidseisen.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    <em>Q1-Q2 2022</em>
</p>
<h3
    id="RoadmapDK2022/2023-&gt;UpdateBeheermodel/aansluitingopLogiusStandaardenBOMOSgeneriekbeheermodel&amp;governance"
>
    &gt; Update Beheermodel / aansluiting op Logius Standaarden BOMOS generiek
    beheer model &amp; governance
</h3>
<p>
    <em>Wat is het issue of de wens?</em>
</p>
<p>
    Momenteel wordt een nieuw generiek beheermodel gebaseerd op BOMOS
    ontwikkeld binnen de afdeling Standaarden;
    <br/>
    Het Digikoppeling beheermodel zal in lijn moeten blijven met het generieke
    model.
</p>
<p>
    <em>Wat gaat er gebeuren?</em>
</p>
<p>
    Het Digikoppeling beheermodel zal in lijn worden gebracht met het generieke
    model.
</p>
<p>
    <em>Wat is het resultaat?</em>
</p>
<p>
    Een Digikoppeling beheermodel in lijn met het generieke beheermodel volgens
    BOMOS van de afdeling Standaarden.
</p>
<p>
    <em>Wanneer gaat dit gebeuren?</em>
</p>
<p>
    <em>Q1-Q2 2022</em>
</p>
<h3 id="RoadmapDK2022/2023-TijdlijnRoadmapDigikoppelingStandaarden">
    Tijdlijn Roadmap Digikoppeling Standaarden
</h3>
<div>
    <table>
        <thead>
            <tr>
                <th tabindex="0" scope="col">
                    <div>
                        Activiteit
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q1 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q2 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q3 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q4 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q1 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q2 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q3 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q4 2023
                    </div>
                </th>
            </tr>
        </thead>
        <thead>
            <tr>
                <th tabindex="0" scope="col">
                    <div>
                        Activiteit
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q1 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q2 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q3 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q4 2022
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q1 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q2 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q3 2023
                    </div>
                </th>
                <th tabindex="0" scope="col">
                    <div>
                        Q4 2023
                    </div>
                </th>
            </tr>
        </thead>
        <colgroup>
            <col/>
            <col/>
            <col/>
            <col/>
            <col/>
            <col/>
            <col/>
            <col/>
            <col/>
        </colgroup>
        <tbody>
            <tr>
                <td>
                    &gt; Toevoegen RESTful API profiel aan Digikoppeling
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Signing &amp; Encryptie toevoegen aan RESTful API
                    profiel
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Aanvulling Digikoppeling governance
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Verbeteren Informatievoorziening / Nieuwe wijze van
                    Publiceren
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Best Practice Identificatie van Organisaties,
                    Organisatieonderdelen en voorzieningen
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Analyse knelpunten Routering en Intermediairs in
                    gegevensverkeer
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Verkennen mogelijk gebruik ebMS3/AS4
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Interoperabiliteit platformen WUS bij gebruik MTOM in
                    combinatie met WS-Security (signing)
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Doorontwikkeling RESPEC/Digikoppeling template voor
                    publicatie van specificaties
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
            </tr>
            <tr>
                <td>
                    &gt; Update Beheermodel / aansluiting op Logius Standaarden
                    BOMOS generiek beheer model &amp; governance
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    X
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
                <td>
                    <br/>
                </td>
            </tr>
        </tbody>
    </table>
</div>
