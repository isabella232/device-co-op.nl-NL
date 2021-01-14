---
description: Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.
seo-description: Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.
seo-title: Lidmaatschapseisen
title: Lidmaatschapseisen
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 1ab7be570ea63645c6d6065341d31bf170f79715
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 4%

---


# Lidmaatschapseisen{#membership-requirements}

Uw bedrijf moet aan deze minimumnormen voldoen alvorens u de Co-op van het Apparaat van de Experience Cloud kunt beginnen te gebruiken.

## Vereisten {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Bespreek met uw [!DNL Adobe representative to get started]. Adobe behoudt zich het recht voor om een eventueel toekomstig lidmaatschap van een klant aan de Experience Cloud Device Co-op te zeggen indien Adobe bepaalt dat de deelname van een toekomstige klant aan de Device Co-op (1) een schending van een toepasselijk recht kan inhouden; of (2) een wezenlijk risico opleveren voor de veiligheid of de activiteiten van Adobe of een van haar klanten.

## Experience Cloud-vereisten {#section-76218a50385d43e6b9323e49f598394a}

U moet voor [!DNL Adobe Experience Cloud] worden toegelaten en de volgende oplossingen en de diensten gebruiken om aan co-op deel te nemen.

**Oplossingen**

Aanvragers moeten ten minste een van de volgende [!DNL Adobe]oplossingen gebruiken:

* [Analytics](http://www.adobe.com/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/marketing-cloud/data-management-platform.html)
* [Media optimaliseren](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**Kerndiensten**

Aanvragers moeten de [Experience Cloud ID Service](https://docs.adobe.com/content/help/nl-NL/id-service/using/home.html) implementeren.

## Vereisten voor Adobe codebibliotheek {#section-931a3fca1ce54afd90b88ba032e75f05}

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

Uw SDK-code moet zijn ingeschakeld voor de id-service [!DNL Experience Cloud]. Schakel de nieuwste SDK-code voor elke toepassing in uw [Adobe Mobile Services](https://mobilemarketing.adobe.com/)-account in en download deze. Zie [Serviceopties voor SDK-bezoeker-id configureren](https://docs.adobe.com/content/help/en/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Gebruik voor elke SDK de juiste `visitorSyncIdentifier`-methode die aan uw behoeften voldoet. Zie:

* [Methoden van Android Experience Cloud ID-service](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID-servicemethoden](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Vereist versie 1.5.4.

[!DNL Analytics] klanten kunnen de bibliotheek VisitorAPI.js downloaden van  [!DNL Code Manager]. Deze bevindt zich in de JavaScript- (Nieuw) of JavaScript-bestanden (Verouderd). Neem contact op met [Klantenservice](https://helpx.adobe.com/marketing-cloud/contact-support.html) als u geen toegang hebt tot [!DNL Code Manager].

**Doelbibliotheek**

Vereist een van de volgende [!DNL Target] JavaScript-bibliotheken:

* at.js (elke versie)
* mbox.js, versie 58 of hoger

