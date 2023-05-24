---
description: Informatie over het delen van koppelingen in de apparaatgrafiek.
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: Delen van koppelingen in de apparaatgrafiek
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
exl-id: 91ecc493-89d8-40d6-a98b-c2349e25c854
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---

# Delen van koppelingen in de apparaatgrafiek{#link-sharing-in-the-device-graph}

Informatie over het delen van koppelingen in de apparaatgrafiek.

De [!DNL Device Graph] deelt deterministische en probabilistische banden met verschillende leden van de Coop van het Apparaat van Adobe Experience Cloud. Het delen van koppelingen is wat de [!DNL Device Co-op] zo krachtig. Het breidt uit wat elk lid over de apparaten verbonden aan een anonieme persoon weet, maar slechts als u minstens één van de apparaten van die anonieme persoon eerder hebt gezien.

## Overzicht apparaatgrafiek {#section-7858e9f61b5644c981ffb53626fcc19d}

Voordat u aan de slag gaat, bekijken we eerst hoe de [!DNL Device Graph] werkt. Leden van de [!DNL Device Co-op] gegevens verzenden naar de [!DNL Device Graph]. De [!DNL Device Graph] gebruikt deze gegevens om de identiteit van een persoon te construeren op basis van [deterministische en probabilistische banden](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) tussen apparaten. Als [!DNL Device Co-op] deelnemer, verstrekken deze verbindingen inzicht over de verhouding tussen uw voor authentiek verklaarde gebruikers, andere gebruikers, en hun apparaten. Laten we eens kijken hoe dit werkt in de onderstaande sectie.

## Voorbeeld van delen van koppeling {#section-cb410d827cf14f76bc9b0bd4d31ed767}

In het volgende voorbeeld wordt de kracht van het delen van koppelingen getoond in de interface van het apparaat. In dit voorbeeld hebben we twee fictieve bedrijven, de News Company en de Finance Company. Beide ondernemingen zijn lid van de [!DNL Device Co-op]. Persoon A is een consument die of de websites van elk bedrijf van veelvoudige apparaten het programma opent of doorbladert.

![](assets/share1.png)

Omdat Person A met hun mobiele telefoon en tablet voor authentiek verklaard aan de nieuwsplaats is, identificeert het Bedrijf van het Nieuws hen met een consument identiteitskaart De id wordt naar de [!DNL Device Graph] als cryptografische hash. Het Bedrijf van Financiën heeft deze apparaten eerder gezien, maar Persoon A heeft niet aan de plaats het programma geopend. Bijgevolg weet de Finance Company niet of of of deze apparaten op elkaar betrekking hebben of hoe zij met Persoon A geassocieerd zijn.

![](assets/share2.png)

Gezien de cryptografische hash van de consument-id [!DNL Device Graph] erkent dat deze apparaten aan elkaar en een bepaalde persoon verwant zijn. Aan ondernemingen die niet deelnemen aan de [!DNL Device Co-op] deze bezoeken lijken afkomstig te zijn van afzonderlijke , willekeurige middelen . In elk geval, zodra [!DNL Device Graph] heeft de hashed-id:

* Wist dat mobiele telefoon en laptop aan elkaar zijn gekoppeld.
* Erkent dat de Finance Company wil weten of de mobiele telefoon en laptop aan elkaar gekoppeld zijn.

Gezien deze omstandigheden [!DNL Device Graph] deelt nu de verbinding die deze apparaten voor het Bedrijf van het Nieuws met het Bedrijf van de Financiën verbindt. Tijdens dit proces [!DNL Device Graph] dupliceert en deelt de verbinding van één cooplid aan een andere.

![](assets/share3.png)

Op dit punt [!DNL Device Graph] heeft zijn rol met succes uitgevoerd. Zowel de News Company als de Finance Company hebben een duidelijk beeld van een identiteit. Zij kunnen Persoon A nauwkeurig over al hun apparaten bereiken.

## Privacy en delen van koppelingen {#section-7b566018b3304420a4b3e4c079826110}

Handhaving van de privacy van consumenten en gegevensintegriteit voor [!DNL Device Co-op] de leden zijn van cruciaal belang gedurende het gehele koppelingsproces . Tijdens deze procedure voor het delen van klanten en koppelingen [!DNL Device Graph] niet:

* Vertel de Finance Company dat de link van de News Company kwam.
* De klant-id delen die door een van de gebruikers wordt gebruikt [!DNL Device Co-op] lid met een andere.
* Geef andere informatie op dan dat het mobiele apparaat en de laptop een gemeenschappelijke koppeling delen.

## Volgende stappen {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Als u de documentatie over identiteit, koppelingen en het delen van koppelingen leest, krijgt u een goed idee hoe de [!DNL Device Graph] verzamelt intern gegevens. Als volgende stap adviseren wij een blik bij onze documentatie te nemen die beschrijft hoe het concept *`known device`* levert verbindingen over het apparaat aan de leden van de Coop van het Apparaat. Zie [Bekende apparaten](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) en [Onbekende apparaten](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
