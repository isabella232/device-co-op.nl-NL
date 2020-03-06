---
description: Ongeveer verbinding delend in de Grafiek van het Apparaat.
seo-description: Ongeveer verbinding delend in de Grafiek van het Apparaat.
seo-title: Het delen van de verbinding in de Grafiek van het Apparaat
title: Het delen van de verbinding in de Grafiek van het Apparaat
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Het delen van de verbinding in de Grafiek van het Apparaat{#link-sharing-in-the-device-graph}

Ongeveer verbinding delend in de Grafiek van het Apparaat.

De [!DNL Device Graph] aandelen deterministische en probabilistische verbindingen met verschillende leden van het Apparaat van het Apparaat van de Wolk van de Ervaring van Adobe Co-op. Het delen van de verbinding is wat het [!DNL Device Co-op] zo krachtig maakt. Het breidt uit wat elk lid over de apparaten verbonden aan een anonieme persoon weet, maar slechts als u minstens één van de apparaten van die anonieme persoon eerder hebt gezien.

## Overzicht apparaatgrafiek {#section-7858e9f61b5644c981ffb53626fcc19d}

Voordat we beginnen, laten we even kijken hoe het [!DNL Device Graph] werkt. De leden van het [!DNL Device Co-op] verzenden gegevens naar het [!DNL Device Graph]. Het [!DNL Device Graph] gebruikt deze gegevens om de identiteit van een persoon te construeren van [deterministische en probabilistische verbindingen](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) tussen apparaten. Als [!DNL Device Co-op] deelnemer, verstrekken deze verbindingen inzicht over het verband tussen uw voor authentiek verklaarde gebruikers, andere gebruikers, en hun apparaten. Laten we eens kijken hoe dit werkt in de sectie hieronder.

## Het delen van de verbinding voorbeeld {#section-cb410d827cf14f76bc9b0bd4d31ed767}

Het volgende voorbeeld toont de macht van verbinding aan delend in de Co-op van het Apparaat. In dit voorbeeld hebben we twee fictieve bedrijven, de News Company en de Finance Company. Beide bedrijven zijn lid van de [!DNL Device Co-op]groep. De persoon A is een consument die of het programma opent of de websites van elk bedrijf van veelvoudige apparaten doorbladert.

![](assets/share1.png)

Omdat de Persoon A aan de nieuwsplaats met hun mobiele telefoon en tablet voor authentiek heeft verklaard, identificeert het Bedrijf van het Nieuws hen met een identiteitskaart van de consument. Het verzendt die identiteitskaart naar [!DNL Device Graph] als cryptografische knoeiboel. Het bedrijf van de Financiën heeft deze apparaten eerder gezien, maar de Persoon A heeft niet aan de plaats het programma geopend. Bijgevolg weet de Financiële Onderneming niet of of of deze apparaten op elkaar betrekking hebben of hoe zij met Persoon A worden geassocieerd.

![](assets/share2.png)

Gezien de cryptografische knoeiboel van de identiteitskaart van de consument, [!DNL Device Graph] erkent het dat deze apparaten met elkaar en een bepaalde persoon verwant zijn. Voor bedrijven die niet deelnemen aan de [!DNL Device Co-op] bezoeken ter plaatse lijken afzonderlijke, willekeurige apparaten te worden gebruikt. In elk geval, zodra de hak-ID het [!DNL Device Graph] heeft:

* Is bekend dat mobiele telefoon en laptop met elkaar verbonden zijn.
* Erkent dat de Finance Company wil weten of de mobiele telefoon en laptop met elkaar verbonden zijn.

Gezien deze voorwaarden, deelt de [!DNL Device Graph] nu de verbinding die deze apparaten voor het Bedrijf van het Nieuws met het Bedrijf van de Financiën verbindt. Tijdens dit proces, [!DNL Device Graph] dupliceert en deelt de verbinding van één co-op lid aan een andere.

![](assets/share3.png)

Op dit punt, [!DNL Device Graph] presteerde het met succes zijn rol. Zowel de News Company als de Finance Company hebben een duidelijk beeld van een identiteit. Zij kunnen Persoon A nauwkeurig over al hun apparaten bereiken.

## Privacy en delen van koppelingen {#section-7b566018b3304420a4b3e4c079826110}

Het handhaven van de privacy en de gegevensintegriteit van de consument voor [!DNL Device Co-op] leden is essentieel gedurende het proces van het delen van verbindingen. Tijdens dit proces voor cliëntidentificatie en het delen van verbindingen [!DNL Device Graph] niet:

* Vertel de Finance Company dat de verbinding van het Bedrijf van het Nieuws kwam.
* Deel de klant-ID die door een [!DNL Device Co-op] lid wordt gebruikt met een andere.
* Verstrek om het even welke informatie buiten dat het mobiele apparaat en laptop een verbinding in gemeenschappelijk delen.

## Volgende stappen {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Het lezen van de documentatie over identiteit, het verbinden, en het verbinding delen zou u een goed gevoel van moeten geven hoe de gegevens intern [!DNL Device Graph] assembleert. Als volgende stap, adviseren wij het nemen van een blik bij onze documentatie die beschrijft hoe het concept van een *`known device`* dwars-apparatenverbindingen aan de leden van Co-op van het Apparaat levert. Zie [Bekende Apparaten](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) en [Onbekende Apparaten](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
