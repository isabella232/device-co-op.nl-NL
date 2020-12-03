---
description: De mensen metrisch is de telling van mensen (of groepen apparaten) die op de Grafiek van het Apparaat wordt gebaseerd Adobe. U kunt de personenmeting toepassen om bezoekers op hun apparaten in Analysis Workspace te identificeren.
seo-description: De mensen metrisch is de telling van mensen (of groepen apparaten) die op de Grafiek van het Apparaat wordt gebaseerd Adobe. U kunt de personenmeting toepassen om bezoekers op hun apparaten in Analysis Workspace te identificeren.
seo-title: Personmetrisch
title: Personmetrisch
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '1408'
ht-degree: 1%

---


# Personmetrisch{#people-metric}

De mensen metrisch is de telling van mensen (of groepen apparaten) die op de Grafiek van het Apparaat wordt gebaseerd Adobe. U kunt de personenmeting toepassen om bezoekers op hun apparaten in Analysis Workspace te identificeren.

## Metrische vereisten en overwegingen voor mensen {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Vereiste of Overweging </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Apparaatcoop </p> </td> 
   <td colname="col2"> <p> Als u de personenmetrische informatie wilt gebruiken, maakt u deel uit van de <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. Het co-op identificeert de veelvoudige apparaten van een persoon (of Experience Cloud IDs). Analytics maakt gebruik van deze informatie om statistisch het aantal mensen af te leiden dat met een merk communiceert. Metrisch is nauwkeurig aan binnen 5%. </p> <p><b>Regio</b>'s: De Device Co-op is momenteel alleen beschikbaar in de VS en Canada. Daarom wanneer het evalueren van de metrisch van Mensen, zou u een segment op uw analyse moeten toepassen die uw gegevens voor de V.S. en Canada slechts filters. </p> <p>Elke week berekent de Grafiek van het Apparaat een nieuwe versie van co-op en publiceert het voor gebruik. Op dinsdag verzamelt het systeem de meest recente gegevens en publiceert het een bijgewerkte versie van de grafiek. Experience Cloud-oplossingen gebruiken vervolgens de nieuwste versie van de grafiek. Specifiek voor Analytics, worden de veranderingen gelezen binnen op woensdagen en verwerking van de veranderingen neemt typisch tussen 1 en 2 werkdagen. </p> <p> <p>Belangrijk:  Wanneer de grafiek wekelijks bijwerkt, kan het metrisch van Mensen historisch beïnvloeden. Met andere woorden: het aantal historische personen kan in de loop der tijd veranderen wanneer de grafiek leert en wordt bijgewerkt. Bijvoorbeeld, als u een rapport vandaag in werking stelt dat Mensen vorige maand telt, en dan het zelfde rapport in een week in werking stelt nadat de grafiek heeft bijgewerkt, kan de historische telling van Mensen lichtjes veranderen. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Metrische machtigingen </td> 
   <td colname="col2"> <p>U kunt metrisch van Mensen slechts gebruiken als u toegang tot het hebt verleend. Beheerders kunnen<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> de machtigingen voor</a> metriek aanpassen in de beheerprogramma's. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Toewijzing aan IMS org </td> 
   <td colname="col2"> <p>Metrisch van Mensen zal voor alle rapportsuites worden toegelaten die aan IMSORG <a href="https://docs.adobe.com/content/help/nl-NL/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"></a>in kaart worden gebracht. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Projecten/gereedschappen analyseren </p> </td> 
   <td colname="col2"> <p>Gebruik de personenmetrische informatie in <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Ad Hoc Analysis</span>, <span class="wintitle"> Report Builder</span>, en via API. U kunt het gebruiken waar u de Unieke metrische Bezoekers, met inbegrip van Berekende Metriek zou gebruiken. </p> <p>Stel bijvoorbeeld dat u een maateenheid voor de omzet per persoon maakt om een maatstaf voor de omzet per unieke bezoeker te vervangen. </p> <p>Een het projectmalplaatje <a href="https://docs.adobe.com/content/help/nl-NL/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"></a> van Mensen is beschikbaar om te beginnen metrisch van Mensen in Analysis Workspace te gebruiken. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Beide regels inschakelen </p> </td> 
   <td colname="col2"> <p>Adobe raadt u aan <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> Bodt Rules</a>in te schakelen, vooral wanneer u de personenmeting gebruikt. </p> <p>Wanneer een bot door uw website kruipt, verhoogt het kunstmatig uw Unieke Bezoeker telling. Het verwijderen van beide verkeer uit uw rapportenpakket biedt een nauwkeuriger meting van de activiteit op uw digitale eigenschappen, zowel in termen van Unieke Bezoekers als Mensen. </p> <p>Navigeer hiertoe naar <span class="uicontrol"> Analytics</span> &gt; <span class="uicontrol"> Admin</span> &gt; <span class="uicontrol"> Report Suites</span>. Selecteer de juiste rapportsuite en ga naar <span class="uicontrol"> Instellingen</span> bewerken &gt; <span class="uicontrol"> Algemeen</span> &gt; <span class="uicontrol"> Bot Rules</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Segmenteringsoverwegingen </p> </td> 
   <td colname="col2"> <p> Wanneer u segmenten met metrische personen gebruikt, kan de metrische rapportage dramatisch lager zijn dan u had verwacht. </p> <p>Zie Metrisch <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> Personen gebruiken met Segmenten</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Wat is het metrisch van de mensen? {#section-89e2b8f5e80f480391449fc8d1117a6a}

Metrisch van Mensen is Analytics die metrisch melden die u helpt apparaten aan mensen toeschrijven. Het biedt een op personen gebaseerde marketingweergave, waarmee u de activiteiten van bezoekers op al hun apparaten kunt meten. Beschouw het als een gedupliceerde versie van Unieke Bezoekers en u kunt de maatstaf Mensen gebruiken voor analyse waar u voorheen Unieke Bezoekers gebruikte.

**Apparaten zijn personen**

Voordat de People-meting beschikbaar kwam, kan een persoon (bijvoorbeeld) uw site bezoeken en een campagne of merk starten op drie verschillende apparaten en een aankoop doen, zelfs binnen enkele minuten. Afhankelijk van uw implementatie, zou Analytics elk apparaat als unieke bezoeker kunnen melden en $10 tot drie apparaten in een aankoop $30 toeschrijven.

Metrisch van Mensen laat u nauwkeurig dat $30 aanschaf aan één persoon toeschrijven:

![](assets/people-centric-results.png)

**Meer nauwkeurigheid in rapporten**

Metrisch van Mensen laat u toe om aan veelvoudige apparaten als één enkele entiteit te denken. In het volgende Analysis Workspace-project worden nauwkeurigheidsvergelijkingen getoond tussen de rapportage van Unieke bezoekers en de rapportage van Personen:

![](assets/people_report.png)

Personen en unieke bezoekers naast elkaar vergelijken:

![](assets/people-report.png)

**Definities**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Item </th> 
   <th colname="col2" class="entry"> Beschrijving </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mensen </p> </td> 
   <td colname="col2"> <p>De maatstaf Mensen is gebaseerd op het idee dat consumenten met uw merk op meerdere apparaten werken. Hoe meer u uw gegevens segmenteert of segmenteert, hoe kleiner de kans dat dezelfde persoon meerdere apparaten heeft gebruikt binnen dat gegevenssegment. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Unieke bezoekers </p> </td> 
   <td colname="col2"> <p>Hoe meer u bijvoorbeeld gegevens segmenteert op datum of tijd, hoe kleiner het verschil tussen Personen en Unieke bezoekers wordt. Als u een goed begrip van de algemene invloed van de Coop van het Apparaat wilt, adviseert Adobe gebruikend een datumwaaier van de laatste 90 dagen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compressie </p> </td> 
   <td colname="col2"> <p>Met behulp van een eenvoudige berekende metrische waarde kunt u zien hoeveel kleiner de maateenheid Mensen is als een percentage van Unieke bezoekers. Klik op het infopictogram naast "Compressie"in de lijst hierboven om te zien hoe te om deze metrisch tot stand te brengen. </p> <p>Mensen kunnen worden gebruikt in andere berekende maatstaven in plaats van Unieke bezoekers. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Hoe wordt de personenmetrisch berekend? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

De volgende afbeelding laat zien hoe de metrische waarde van Personen wordt berekend en hoe deze in de loop der tijd kan dalen voor hetzelfde bereik van rapportdatums in het verleden.

![](assets/people-calculations.png)

In dit voorbeeld, veronderstel er een vaste reeks bezoekers is. Als u een rapport voor een vast tijdkader in het verleden in werking stelt, toont het een vaste reeks bezoekers. Als de Grafiek van het Apparaat de gegevens uitvoert die op linkergrafisch in week 1 worden getoond, dat in 90 Mensen resulteert. Een week later, na de volgende looppas van de Grafiek van het Apparaat, wordt nieuwe informatie in aanmerking genomen. Als je hetzelfde rapport opstelt als je een week geleden deed, is het aantal mensen gedaald tot 84. De geschiedenis is veranderd omdat de Grafiek van het Apparaat nieuwe informatie verstrekte over welke apparaten zouden moeten worden gegroepeerd.

## Metrisch van Mensen met Segmenten gebruiken {#section-d03525420dbe48379fd95b230ef05885}

Wanneer u segmenten gebruikt met de metrische waarde Mensen, kunnen de resultaten aanzienlijk lager zijn dan u had verwacht. Dit probleem doet zich voor omdat er in de segmentatie geen *`person`* container is. De segmentatie gebruikt de container van de Bezoeker, die de container van het hoogste niveau in de definitie is en op het apparaat, niet op de persoon gebaseerd is.

Deze kwestie komt hoofdzakelijk voor wanneer het stapelen van segmenten met metrische Mensen.

![](assets/people-stacked-segments.png)

Bij het stapelen van segmenten wordt een nieuw segment gemaakt dat de combinatie van de segmenten vertegenwoordigt. Stapelende segmenten komen voor wanneer u:

* Plaats een segment boven op een ander segment in Analysis Workspace. (Deze worden automatisch aangesloten gebruikend de *`And`* exploitant.)
* Pas één segment toe dat de *`And`* operator bevat.
* Pas een segment op zowel het projectniveau als lijstniveau toe.
* Gebruik een virtuele rapportsuite met een ander segment.

Stel bijvoorbeeld dat u de volgende segmenten stapelt op de metrische modus Personen:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Alleen het aantal personen dat in beide segmenten in aanmerking komt, *`using a single device`* wordt geteld. (In de personenmeting wordt het aantal gekwalificeerde personen op verschillende apparaten niet weergegeven.)

In deze situatie wordt het gebruik van de *`Or`* operator niet aanbevolen. Dit zou een aantal mensen tellen die een of andere groep zagen, zonder dat er rekening mee wordt gehouden hoeveel mensen in aanmerking komen voor beide segmenten.

Zie Segmenten [van de](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) Bouw in de hulp van de Segmentatie voor meer informatie.

## Apparaattypen {#section-8ab378c84ff34574b9c20fecb3848a86}

De metrische functie Apparaatcoop en Personen werkt het beste in Adobe Analytics wanneer uw rapportsuite gegevens van meerdere apparaattypen bevat. Als u bijvoorbeeld web- en toepassingsgegevens combineert in dezelfde rapportsuite, wordt de maatstaf Mensen krachtiger en effectiever. Hoe meer apparaatcrossover in uw gegevens, des te groter de kans dat meerdere unieke bezoekers als één persoon worden gegroepeerd.

![](assets/people-device-types.png)

## Dekking van service Experience Cloud ID {#section-bbf0098cac2e467289e7a644a1dea05c}

De interface van het Apparaat vereist dat uw digitale eigenschappen worden voorzien van instrumenten gebruikend de dienst van Experience Cloud ID (MCID). Als de gegevens in uw rapportreeks een significant aantal bezoekers zonder MCID bevatten, wordt de doeltreffendheid van Co-op van het Apparaat en metrisch van Mensen verminderd.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, creeer een [project](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html)**[!UICONTROL People]** , dan sleep metrisch aan de projectlijst:

![](assets/people-metric.png)

