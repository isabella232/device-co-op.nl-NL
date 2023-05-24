---
description: Leer hoe u Device Co-op-gegevens kunt gebruiken in Adobe Target-activiteiten.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Doel - A/B-tests, multivariërende tests en doelgerichte ervaring
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Doel - A/B-tests, multivariërende tests en doelgerichte ervaring{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Leer hoe u Device Co-op-gegevens kunt gebruiken in Adobe Target-activiteiten.

U kunt de gegevens van de Co-op van het Apparaat in tests A/B, multivariate (MVT) tests, en ervaring gebruiken richtend activiteiten. De optie Apparaatcoop is beschikbaar tijdens het maken van activiteiten op het tabblad [!DNL Goals & Settings] pagina in de [!DNL Target] driestapsgerichte workflow.

U kunt geen gegevens van de Coop van het Apparaat in de activiteiten van Automated Personalization, de activiteiten van de Aanbeveling, of activiteiten gebruiken die [!DNL Adobe Analytics] als bron van de rapportage (de [!DNL Target] en [!DNL Analytics] integratie, bekend als A4T).

>[!NOTE]
>
>Zorg ervoor dat u beschikt over de vereiste versie van `mbox.js`. U kunt elke versie van `at.js`. Zie voor meer informatie [Lidmaatschapseisen](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## relevante inhoud leveren, ongeacht het apparaat {#section-bba8d41e96914c82a6d267a54f776354}

De verkopers willen de meest relevante ervaring aan elke bezoeker, ongeacht het apparaat leveren de bezoeker momenteel gebruikt om met hun bedrijf of merk in wisselwerking te staan.

Gebruikers gebruiken hetzelfde bedrijf of merk op verschillende apparaten: werklaptops, thuiscomputers, iPads, iPhones, verschillende browsers enzovoort. Als u niet kunt zien dat elk specifiek apparaat of elke browser wordt gebruikt door dezelfde persoon die eerder met uw merk heeft gewerkt op een ander apparaat of een andere browser, kunt u die persoon geen consistente en doelgerichte ervaring bieden.

Met de Co-op van het Apparaat, kunnen de diverse apparaten van een gebruiker worden geïdentificeerd zoals die door de zelfde gebruiker worden gebruikt. Wanneer die gebruiker een pagina ziet met [!DNL Target] activiteiten—activiteiten of gerichte inhoud— [!DNL Target] kan ervoor zorgen dat de gebruiker dezelfde ervaring ziet als op een ander apparaat.

## Doelactiviteiten door mensen analyseren in plaats van door bezoekers {#section-c25cf4f8483942d7836d60756235e62c}

Marketers die willen analyseren [!DNL Target] activiteiten van &quot; mensen &quot; in plaats van &quot; bezoekers &quot; .

Elke persoon communiceert waarschijnlijk met hetzelfde bedrijf of merk op verschillende apparaten en in verschillende browsers, maar zonder de interface voor apparaten wordt elk afzonderlijk apparaat of elke browser beschouwd als een aparte &quot;bezoeker&quot; in [!DNL Target] rapporten.

Door rapporten van individuele apparaten en browsers te bekijken, wordt het aantal bezoekers verhoogd tot een hoger aantal dan het aantal mensen dat met het bedrijf of merk communiceert. Deze personen converteren doorgaans slechts één keer naar een ander apparaat en een andere browser, zodat de conversiesnelheid lager is dan in werkelijkheid, omdat meer &quot;bezoekers&quot; worden meegerekend voor één conversie.

Met de Co-op van het Apparaat, wordt de inhoudslevering en het melden gedaan op het niveau van &quot;mensen&quot;, zodat tonen de rapporten nauwkeurig hoeveel verschillende mensen de activiteit zagen en hoeveel van de mensen omgezette.

Zonder apparaat-coopgegevens kunt u bepalen dat een bepaalde activiteit de winnaar is. omdat de rapportage echter nauwkeuriger is bij de Device Co-op, kan een andere activiteit in feite een hogere conversiekoers hebben en dus de winnaar zijn.

Voor meer informatie over dit concept raadpleegt u [Analyse: Metrisch met personen](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Apparaatcoopgegevens per activiteit gebruiken {#section-fb46fae482654023abb1a1e26564db9a}

Marketers kunnen de gegevens van de Coop van het Apparaat per activiteit kiezen. Bepaalde [!DNL Target] activiteiten zijn mogelijk niet geschikt voor Device Co-op-gegevens, zoals:

* Specifieke inhoud die geschikt is voor gebruikers op een iPad.

   Gebruikers die eerst een ervaring op een iPad bekijken, blijven die ervaring op hun thuiscomputer zien.

* Een rentevergoeding is alleen beschikbaar voor een strikt segment bezoekers.
* Producten mogen alleen in een bepaalde staat worden bekendgemaakt (bijvoorbeeld een verzekeringspolis met licentiebeperkingen).

Wanneer marketeers een publiek maken in [!DNL Target], worden ze gewaarschuwd als het publiek niet geschikt is voor activiteiten die geschikt zijn voor apparaatcoop. Het juiste publiek omvat alle bezoekers, nieuwe bezoekers en terugkerende bezoekers.
