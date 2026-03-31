---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Verbeter uw vermogen om experimenten effectief uit te voeren en inzichten te genereren
topic: Content Management
role: User
level: Beginner
keywords: inhoud, experiment, meerdere, publiek, behandeling
source-git-commit: 4f30411591ab3bec4b749cfb58f437ddb3474ffa
workflow-type: tm+mt
source-wordcount: '431'
ht-degree: 0%

---

# Toegang tot Journey Optimizer Experimentation Accelerator

Na [&#x200B; het creëren van en het vormen van uw experiment &#x200B;](https://experienceleague.adobe.com/en/docs/journey-optimizer/using/content-management/content-experiment/content-experiment) en het verzenden van uw campagnes of reizen naar uw profielen, kunt u tot **[!UICONTROL Journey Optimizer Experimentation Accelerator]** toegang hebben om dieper in te duiken hoe uw experiment uitvoert.

U kunt **[!UICONTROL Journey Optimizer Experimentation Accelerator]** openen vanuit het linkermenu vanuit de vervolgkeuzelijst [!UICONTROL Experimentation] of via de Apps-schakeloptie. Gebruikers met alleen een Target-licentie hebben er alleen toegang toe via de Apps-schakeloptie.

![](assets/access.png)

Welke experimenten beschikbaar zijn, is afhankelijk van uw instellingen:

* **voor de gebruikers van Adobe Journey Optimizer**: De opstelling van experimenten in uw toegelaten zandbak van de organisatie wordt automatisch omvat.

* **voor de gebruikers van Adobe Target met Journey Optimizer**: Om het even welke A/B activiteiten in Doel verschijnen in **[!UICONTROL Journey Optimizer Experimentation Accelerator]** in de productiesandbox van Journey Optimizer.

* **voor Adobe Target-slechts gebruikers**: Alle activiteiten A/B in uw organisatie van het Doel zijn inbegrepen in de productiesandbox van Journey Optimizer.

Als u **[!UICONTROL Journey Optimizer Experimentation Accelerator]** wilt gebruiken, hebt u toegang tot de sandbox en de volgende gerelateerde machtigingen nodig:

* **[!UICONTROL View Experiments]**
* **[!UICONTROL Manage Experiment Metada]**

+++ Leer hoe u aan Experimentatie gerelateerde machtigingen kunt toewijzen met een Adobe Experience Platform- of Adobe Journey Optimizer-licentie

1. Ga in het **[!DNL Permissions]** -product naar de tab **[!UICONTROL Roles]** en selecteer de gewenste **[!UICONTROL Role]** .

1. Klik op **[!UICONTROL Edit]** om de machtigingen te wijzigen.

1. Voeg de **[!UICONTROL Experiment accelerator]** -bron toe en selecteer vervolgens **[!UICONTROL View Experiments]** en/of **[!UICONTROL Manage Experiment Metada]** in het keuzemenu.

   ![](assets/permissions-experiment.png)

1. Klik op **[!UICONTROL Save]** om wijzigingen toe te passen.

Voor alle gebruikers die al zijn toegewezen aan deze rol, worden hun machtigingen automatisch bijgewerkt.

Deze rol toewijzen aan nieuwe gebruikers:

1. Navigeer naar het tabblad **[!UICONTROL Users]** in het dashboard Rollen en klik op **[!UICONTROL Add User]** .

1. Voer de naam en het e-mailadres van de gebruiker in of kies een optie in de lijst en klik op **[!UICONTROL Save]** .

   Als de gebruiker niet eerder werd gecreeerd, verwijs naar [&#x200B; deze documentatie &#x200B;](https://experienceleague.adobe.com/en/docs/experience-platform/access-control/abac/permissions-ui/users).

De gebruiker ontvangt een e-mail met instructies om toegang te krijgen tot uw exemplaar.

+++

</br>

+++ Leer hoe u aan experimenten gerelateerde machtigingen kunt toewijzen met een Adobe Target-licentie

1. Open **[Admin Console &#x200B;](http://adminconsole.adobe.com/)**.

1. Kies **[!UICONTROL Adobe Experience Platform]** in **[!UICONTROL Products]** .

1. Klik op **[!UICONTROL New Profile]** .

   ![](assets/permission-target.png)

1. Voer een **[!UICONTROL Name]** en **[!UICONTROL Description]** in voor het profiel en klik vervolgens op **[!UICONTROL Save]** .

1. Open de nieuwe versie van **[!UICONTROL Profile]** en navigeer naar de tab **[!UICONTROL Permissions]** .

1. Klik op ![](assets/do-not-localize/Smock_Edit_18_N.svg) naast de machtiging **[!UICONTROL experimentation-accelerator]** .

   ![](assets/permission-target-1.png)

1. Voeg de machtigingen toe die dit profiel moet hebben, zoals **[!UICONTROL View Experiments]** en **[!UICONTROL Manage Experiment Metadata]** , en klik vervolgens op **[!UICONTROL Save]** .

   >[!TIP]
   >
   > Maak afzonderlijke profielen wanneer gebruikers verschillende toegangsniveaus nodig hebben. Maak bijvoorbeeld een **[!UICONTROL Experimentation Accelerator Viewer]** -profiel met alleen **[!UICONTROL View Experiments]** en een **[!UICONTROL Experimentation Accelerator Editor]** -profiel met zowel **[!UICONTROL View Experiments]** als **[!UICONTROL Manage Experiment Metadata]** .

   ![](assets/permission-target-2.png)

1. Selecteer op het tabblad **[!UICONTROL Permissions]** de optie **[!UICONTROL Sandboxes]** .

1. Voeg de sandboxen toe waar gebruikers Journey Optimizer Experimentation Accelerator moeten kunnen gebruiken en klik vervolgens op **[!UICONTROL Save]** .

1. Open het tabblad **[!UICONTROL Users]** en klik vervolgens op **[!UICONTROL Add users]** .

   ![](assets/permission-target-3.png)

1. Voeg de gebruikers toe die deze toegang moeten krijgen en klik vervolgens op **[!UICONTROL Save]** .

Gebruikers die aan dit profiel zijn toegevoegd, hebben nu toegang tot Journey Optimizer Experimentation Accelerator via de app-schakeloptie.

+++


<!--table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table-->
