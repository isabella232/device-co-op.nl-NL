---
description: Hoe de Grafiek van het Apparaat deterministische en probabilistische gegevens analyseert om een kaart te bouwen die apparaten samen verbindt.
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: Deterministische en probabilistische banden
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
exl-id: e9bd2b7a-7d39-425d-adbb-298944009fcc
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '845'
ht-degree: 0%

---

# Deterministische en probabilistische banden{#deterministic-and-probabilistic-links}

Hoe de Grafiek van het Apparaat deterministische en probabilistische gegevens analyseert om een kaart te bouwen die apparaten samen verbindt.

In de [!DNL Device Graph], interne processen een identiteitshiërarchie bouwen die apparaten in kaart brengt en hen met individuele, geanonimiseerde mensen verbindt. De uitvoer van de grafiek bevat apparaatkoppelingen die u kunt gebruiken voor het aanwijzen van doelen, en gegevens die worden weergegeven in bepaalde Experience Cloud-oplossingen. De oplossingen van de Adobe die met werken [!DNL Device Graph] gegevens zijn onder andere Analytics, Audience Manager, Media Optimizer en Target.

De [!DNL Device Graph] analyseert deterministische en probabilistische gegevens om een kaart te bouwen die apparaten samen verbindt. Deterministische gegevens verbinden apparaten samen die op hashed openings van een sessieinformatie worden gebaseerd. Probabilistische gegevens verbinden apparaten samen die op informatie zoals IP adressen en andere meta-gegevens worden gebaseerd. De [!DNL Device Graph] Koppelt de gekoppelde apparaatclusters aan een anonieme individuele persoon Deze verbindingen laten digitale marketers mensen bereiken in plaats van apparaten. In de [!DNL Device Graph]De eigenaar van een apparaat is de anonieme voorstelling van een echte persoon. Zowel deterministische als probabilistische verbindingen helpen een structuur van gebruikersidentiteit bouwen.

>[!NOTE]
>
>In de Adobe Experience Cloud Device Co-op, termen zoals *apparaat*, *persoon*, en *identiteit* specifieke betekenissen hebben. Bijvoorbeeld: *apparaat* kan verwijzen naar fysieke hardware zoals een telefoon of tablet en de toepassingen die op die hardware lopen. Zie de [woordenlijst](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) voor definities.

## Wat zijn koppelingen? {#section-2df4c6f01eba49369993146df0661f13}

Wanneer we het hebben over links, is het belangrijk om in gedachten te houden wat deze werkelijk in de context van [!DNL Experience Cloud] Apparaatgrafiek. In deze context, zijn de verbindingen geen fysieke verbindingen tussen apparaten. In plaats daarvan, is een verbinding hoe de Grafiek van het Apparaat verschillende apparaten aan de zelfde, onbekende persoon associeert. Stel dat we een mobiele telefoon en een desktopbrowser hebben. De telefoon en browser kunnen als &quot;verbonden&quot;worden beschouwd zodra de Grafiek van het Apparaat beide apparaten door de zelfde, onbekende persoon wordt gebruikt. Zoals u hieronder zult lezen, bouwt de Grafiek van het Apparaat identiteiten met deterministische en probabilistische verbindingen. En in de Grafiek van het Apparaat, is de eigenaar van een apparaat de anonieme vertegenwoordiging van een real-life persoon.

## Deterministische koppelingen {#section-33d41e828a674b398e36fe63da20ac09}

Deterministische koppelingen koppelen een apparaat aan een persoon op basis van een verificatiegebeurtenis (bijvoorbeeld een aanmeldingsactie naar een site van een apparaat). Met deze actie maakt u een geanonimiseerde id die een consumenten-id wordt genoemd. Laten we eens kijken hoe deterministisch koppelen werkt. In dit voorbeeld meldt Person A zich aan bij een nieuwssite via een app op hun mobiele apparaat. Later die dag meldt Person A zich opnieuw aan, maar dit keer via een browser op hun laptop.

![](assets/link1.png)

Gebaseerd op de openings van een sessieinformatie, de Grafiek van het Apparaat:

* Wist dat Person A met een combinatie van een mobiele telefoon/app en een laptop/browser-apparaat is geverifieerd voor de nieuwssite.
* Koppelt deze apparaten aan Persoon A.
* Bouwt een identiteit die op verbonden apparaten verbonden aan een anonieme persoon wordt gebaseerd.

![](assets/link2.png)

>[!NOTE]
>
>Geen van beide [!DNL Adobe Experience Cloud Device Co-op] of de [!DNL Device Graph] daadwerkelijk verificatiegegevens of persoonlijk identificeerbare informatie (PII) in deze gegevens ontvangt. Leden van de [!DNL Experience Cloud Device Co-op], geeft u cryptografisch gehakte unieke consumenten-id&#39;s door aan de apparaatgrafiek. De consument-id vertegenwoordigt een geverifieerde gebruiker in de grafiek en beschermt de privacy van de consument.

## Betrouwbare koppelingen {#section-5f5aa755da984f9d851f7cb380262998}

Probabilistische verbindingen verbinden een apparaat aan een persoon algoritmisch, die op kenmerken en meta-gegevens zoals wordt gebaseerd:

* Browsergedrag
* IP-adressen
* Besturingssystemen
* IDFA- en GAID-ID&#39;s

Laten we eens kijken hoe probabilistische link werkt. In dit voorbeeld bladert Person A naar een nieuwssite op hun tablet en later vanaf een desktopcomputer. Tijdens het bladeren meldt Person A zich niet aan bij de nieuwssite. Tijdens elk afzonderlijk bezoek delen de tablet en de desktop hetzelfde IP-adres.

![](assets/link3.png)

Op basis van deze informatie [!DNL Device Graph] evalueert IP adres delend patronen tussen beide apparaten en verbindt deze apparaten samen als de resultaten suggereren zij tot Persoon A behoren. Het eindresultaat is de hiërarchie van de identiteit die wordt afgeleid van algoritmische waarschijnlijkheidsberekeningen.

![](assets/link4.png)

In dit voorbeeld koppelde de Grafiek van het Apparaat beide apparaten nadat zij werden gebruikt om tot de zelfde nieuwssite toegang te hebben. Apparaten hoeven echter niet op dezelfde site te worden bekeken om te worden gekoppeld. Om dit punt te illustreren, laten wij zeggen elk apparaat in dit voorbeeld bezoeken volledig verschillende websites. De [!DNL Device Graph] algoritme kan nog een probabilistische verbinding maken die op hun gedeeld IP adres en van een analyse van andere gegevens wordt gebaseerd. Dit proces draagt ertoe bij dat probabilistische banden zo krachtig worden voor leden van het [!DNL Experience Cloud] Apparaatcoop.

## Beide typen gegevens bieden waarde {#section-43d22d8c10634edcb261e7bda6fdf323}

Deterministische en probabilistische gegevens vullen elkaar aan. Een apparaatgrafiek die alleen deterministische gegevens bevat, geeft u daarentegen een beperkte weergave van de identiteit van een persoon. Zonder verificatie kan een apparaatgrafiek u niet informeren over andere apparaten en personen die door uw site bladeren. Probabilistische gegevens kunnen deze verbindingen maken en u helpen unauthenticated apparaten, mensen, en huishoudens bereiken.

deterministische gegevens zijn echter ook belangrijk. Het kan bijvoorbeeld de probabilistische besluitvorming verbeteren door het wegnemen van valse verbindingen die ontstaan op plaatsen waar probabilistische signalen overvloedig en overlappend zijn (bijv. koffiewinkels, bibliotheken, luchthavens, enz.).

Bij beide typen gegevens geeft de grafiek van het apparaat u een uitgebreider beeld van de identiteit van een persoon dan bij elk type afzonderlijk.

![](assets/link5.png)
