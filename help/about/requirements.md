---
description: Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.
seo-description: Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.
seo-title: Lidmaatschapseisen
title: Lidmaatschapseisen
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 4%

---


# Lidmaatschapseisen{#membership-requirements}

Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.

## Vereisten {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Praat met je [!DNL Adobe representative to get started]. Als u geen Adobe-vertegenwoordiger hebt, gaat u naar de portal [voor](http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html) Device Co-op-lidmaatschap en vult u het onlineformulier in.

Adobe behoudt zich het recht voor om een eventueel toekomstig lidmaatschap van een klant aan de Experience Cloud Device Co-op te zeggen indien Adobe bepaalt dat de deelname van een toekomstige klant aan de Device Co-op (1) een schending van een toepasselijk recht kan inhouden; of (2) een wezenlijk risico opleveren voor de veiligheid of de activiteiten van Adobe of een van haar klanten.

## Experience Cloud-eisen {#section-76218a50385d43e6b9323e49f598394a}

U moet voor coop worden toegelaten [!DNL Adobe Experience Cloud] en de volgende oplossingen en de diensten gebruiken om aan deel te nemen.

**Oplossingen**

De aanvrager moet ten minste een van de volgende [!DNL Adobe]oplossingen gebruiken:

* [Analytics](http://www.adobe.com/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/marketing-cloud/data-management-platform.html)
* [Media optimaliseren](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**Kerndiensten**

Aanvragers moeten de [Experience Cloud ID-service](https://docs.adobe.com/content/help/nl-NL/id-service/using/home.html)implementeren.

## Vereisten voor de Adobe-codebibliotheek {#section-931a3fca1ce54afd90b88ba032e75f05}

De volgende lijst maakt een lijst van de minimumversies van de codebibliotheken of SDKs die door diverse [!DNL Experience Cloud] oplossingen en de diensten worden gebruikt. Als u om het even welk van deze code gebruikt en aan de Co-op van het Apparaat wilt deelnemen, zorg ervoor u aan deze minimumvereisten voldoet.

>[!TIP]
>
>We raden u aan de nieuwste codeversies te gebruiken in plaats van de vereiste minimale versies.

**AppMeasurement (Flash)**

Vereist versie 4.1. Zie [AppMeasurement voor Flash, Flex en AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Vereist versie 1.5.4. Zie [AppMeasurement voor Flash, Flex en AIR](https://docs.adobe.com/content/help/en/analytics/implementation/js/migrate-from-hcode.html).

**Mobiele SDK&#39;s**

Minimale vereisten voor mobiele SDK:

* Android versie 4.8.3.
* iOS versie 4.8.5.

De SDK-code moet zijn ingeschakeld voor de [!DNL Experience Cloud] ID-service. Schakel de nieuwste SDK-code voor elke app in uw [Adobe Mobile Services](https://mobilemarketing.adobe.com/) -account in en download deze. Zie Opties voor [SDK-bezoekersidentiteitskaart](https://docs.adobe.com/content/help/en/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html)configureren.

Gebruik voor elke SDK de juiste `visitorSyncIdentifier` methode die aan uw behoeften voldoet. Zie:

* [Methoden van Android Experience Cloud ID-service](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID-servicemethoden](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Vereist versie 1.5.4.

[!DNL Analytics] klanten kunnen de bibliotheek VisitorAPI.js downloaden van [!DNL Code Manager]. Deze bevindt zich in de JavaScript- (Nieuw) of JavaScript-bestanden (Verouderd). Neem contact op met de [klantenservice](https://helpx.adobe.com/marketing-cloud/contact-support.html) als u geen toegang hebt tot [!DNL Code Manager].

**Doelbibliotheek**

Vereist een van de volgende [!DNL Target] JavaScript-bibliotheken:

* at.js (elke versie)
* mbox.js, versie 58 of hoger

