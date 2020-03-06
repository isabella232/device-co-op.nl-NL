---
description: Leer hoe te om de gegevens van de Co-op van het Apparaat in de activiteiten van het Doel van Adobe te gebruiken.
seo-description: Leer hoe te om de gegevens van de Co-op van het Apparaat in de activiteiten van het Doel van Adobe te gebruiken.
seo-title: Doel - A/B-tests, multivariërende tests en doelgerichte ervaring
title: Doel - A/B-tests, multivariërende tests en doelgerichte ervaring
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Doel - A/B-tests, multivariërende tests en doelgerichte ervaring{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Leer hoe te om de gegevens van de Co-op van het Apparaat in de activiteiten van het Doel van Adobe te gebruiken.

U kunt de gegevens van de Co-op van het Apparaat in tests A/B, multivariate (MVT) tests, en ervaring gebruiken richtend activiteiten. De optie van de Co-op van het Apparaat is beschikbaar tijdens activiteitsverwezenlijking op de [!DNL Goals & Settings] pagina in het [!DNL Target] driestappengeleide werkschema.

U kunt geen gegevens van de Co-op van het Apparaat in de Geautomatiseerde activiteiten van de Verpersoonlijking, de activiteiten van de Aanbeveling, of activiteiten gebruiken die [!DNL Adobe Analytics] als rapporteringsbron (de [!DNL Target] en [!DNL Analytics] integratie, die als A4T wordt bekend) gebruiken.

>[!NOTE]
>
>Zorg ervoor dat u de vereiste versie van hebt `mbox.js`. U kunt om het even welke versie van gebruiken `at.js`. Voor meer informatie, zie de Vereisten van het [Lidmaatschap](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Verstrek relevante inhoud ongeacht het apparaat {#section-bba8d41e96914c82a6d267a54f776354}

Marktdeelnemers willen elke bezoeker de meest relevante ervaring bieden, ongeacht het apparaat dat de bezoeker momenteel gebruikt om met zijn bedrijf of merk te communiceren.

De gebruikers werken met het zelfde bedrijf of merk van vele verschillende apparaten in wisselwerking: het werk laptops, huiscomputers, iPads, iPhones, diverse browsers, etc. Als u niet kunt erkennen dat elk specifiek apparaat of browser door de zelfde persoon wordt gebruikt die eerder met uw merk op een ander apparaat of browser in wisselwerking heeft gestaan, kunt u geen verenigbare en gerichte ervaring aan die persoon leveren.

Met Co-op van het Apparaat, kunnen de diverse apparaten van een gebruiker worden geïdentificeerd zoals die door de zelfde gebruiker worden gebruikt. Wanneer die gebruiker een pagina met [!DNL Target] activiteit-of activiteiten of gerichte inhoud ziet— [!DNL Target] kan ervoor zorgen dat de gebruiker de zelfde ervaring ziet die op een ander apparaat wordt gezien.

## Analyseer de activiteiten van het Doel door mensen in plaats van door bezoekers {#section-c25cf4f8483942d7836d60756235e62c}

Marktdeelnemers willen [!DNL Target] activiteiten van &quot;mensen&quot; analyseren in plaats van &quot;bezoekers&quot;.

Elke persoon wisselt waarschijnlijk met het zelfde bedrijf of merk over apparaten en browsers, maar zonder de Co-op van het Apparaat, wordt elk individueel apparaat of browser beschouwd als een afzonderlijke &quot;bezoeker&quot;in [!DNL Target] rapporten.

Het bekijken van rapporten door individuele apparaten en browsers verhoogt de telling van de &quot;bezoeker&quot;tot een hoger aantal dan het aantal verschillende mensen die met het bedrijf of het merk in wisselwerking staan. Deze mensen zetten typisch slechts één keer over deze diverse apparaten en browsers om, zodat zal de omzettingskoers lager zijn dan in werkelijkheid omdat meer &quot;bezoekers&quot;voor één enkele omzetting zullen worden geteld.

Met de Co-op van het Apparaat, wordt de inhoudslevering en de rapportering gedaan op het niveau van &quot;mensen&quot;, zodat tonen de rapporten nauwkeurig hoeveel verschillende mensen de activiteit zagen en hoeveel van de mensen bekeerde.

Zonder de gegevens van de Co-op van het Apparaat, zou u kunnen bepalen dat een bepaalde activiteit de winnaar is; omdat de rapportage echter nauwkeuriger is met de Device Co-op, kan een andere activiteit een hogere conversiekoers hebben en dus de winnaar zijn.

Voor meer informatie over dit concept, zie [Analytics: Mensen Metrisch](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Apparaat-Co-op-gegevens per activiteit gebruiken {#section-fb46fae482654023abb1a1e26564db9a}

Marktdeelnemers kunnen ervoor kiezen om de gegevens van het Apparaat te gebruiken voor co-op per activiteit. Bepaalde [!DNL Target] activiteiten zouden niet geschikt voor de gegevens van de Co-op van het Apparaat, zoals kunnen zijn:

* Specifieke inhoud geschikt voor gebruikers op een iPad.

   De gebruikers die eerst een ervaring op een iPad bekijken, zullen blijven die ervaring op hun huiscomputers zien.

* Een rentevergoeding is alleen beschikbaar voor een strikt segment bezoekers.
* Producten die alleen in een bepaalde staat mogen worden geadverteerd (bijvoorbeeld een verzekeringspolis met licentiebeperkingen).

Wanneer de marketeers publiek in creëren, worden zij gealarmeerd [!DNL Target], als het publiek niet aangewezen voor de gegevens-toegelaten activiteiten van Co-op van het Apparaat is. Het aangewezen publiek omvat alle bezoekers, nieuwe bezoekers, en terugkerende bezoekers.
