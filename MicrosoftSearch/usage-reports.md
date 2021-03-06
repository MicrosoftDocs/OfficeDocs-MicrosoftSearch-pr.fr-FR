---
title: Rapports d’utilisation de la recherche
ms.author: ankmis
author: jeffkizn
manager: parulm
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Consulter les rapports d’utilisation de Microsoft Search (recherche Microsoft)
ms.openlocfilehash: ad349e60794f219fa757861081b12a33c6806091
ms.sourcegitcommit: 25b82bce1eaec5803111161b04ee9fd9e82a0bd8
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/02/2021
ms.locfileid: "50072238"
---
# <a name="microsoft-search-usage-reports"></a>Rapports d’utilisation de Microsoft Search (recherche Microsoft)

Les rapports d’utilisation de la recherche vous permettent de mieux comprendre le fonctionnement de la recherche dans votre organisation. Les informations générées à partir [](https://docs.microsoft.com/microsoftsearch/make-content-easy-to-find) de ces rapports vous aideront à faciliter la recherche de contenu et à prendre des mesures qui donnent à vos utilisateurs une expérience plus utile et agréable.

Les [rapports d’utilisation](https://admin.microsoft.com/Adminportal/Home?#/MicrosoftSearch/insights) de Microsoft Search (recherche Microsoft) incluent des graphiques et des tableaux générés à partir de recherches qui sont exécutées à partir de l’accueil SharePoint et Office.com zones de recherche. Vous pouvez voir les données des 31 derniers jours, par jour ou par mois de l’année précédente. Ces rapports sont simplement en cours de déploiement, de sorte que l’ensemble des données historiques prendra du temps.

Une version précédente de cette page incluait les données des recherches exécutées pour Microsoft Search (recherche Microsoft) dans Bing sur Bing.com. Ces données seront bientôt intégrées dans ces rapports, mais pour **l’instant,** vous pouvez toujours voir ces rapports en cliquant sur le lien en bas de la page pour afficher les requêtes les plus récentes de Bing et la distribution des impressions.

> [!div class="mx-imgBorder"]
> ![Tableau de bord des rapports d’utilisation de la recherche](media/usage-reports/usage_reports_v2.png)

## <a name="overview-of-search-reports"></a>Vue d’ensemble des rapports de recherche

| Rapport | Description |
|:-----|:-----|
|Volume de requête|Ce rapport indique le nombre de requêtes de recherche effectuées. Utilisez ce rapport pour identifier les tendances des volumes de requêtes de recherche et pour déterminer les périodes d’activité de recherche élevée et faible.|
|Requêtes les plus courantes|Ce rapport indique les requêtes de recherche les plus populaires. Utilisez ce rapport pour comprendre les types d’informations que vos utilisateurs recherchent.|
|Requêtes abandonnées|Ce rapport affiche les requêtes de recherche les plus populaires qui reçoivent un faible clic. Il permet d'identifier les requêtes de recherche pouvant provoquer l'insatisfaction des utilisateurs et d'améliorer la détectabilité du contenu. Vous pouvez ensuite déterminer si la création d’une réponse, comme un signet, ou l’ing d’un nouveau contenu via un connecteur Graph est l’action la plus appropriées.|
|Requêtes sans résultats|Ce rapport indique les requêtes de recherche populaires qui n'ont retourné aucun résultat. Il permet d'identifier les requêtes de recherche pouvant provoquer l'insatisfaction des utilisateurs et d'améliorer la détectabilité du contenu. Vous pouvez ensuite déterminer si la création d’une réponse, telle qu’un signet, ou l’ing d’un nouveau contenu via un connecteur Graph est l’action la plus appropriées.|

## <a name="viewing-reports"></a>Affichage des rapports

Lorsque vous accédez à la page rapports d’utilisation, tous les rapports sont disponibles. Vous pouvez utiliser le filtre de date pour sélectionner un jour ou un mois spécifique à afficher.

Le téléchargement d’un rapport vous permettra de voir les rapports à partir d’un plus large éventail de temps. Cliquez sur la flèche de téléchargement et sélectionnez **les 31 derniers jours** ou **les 12 derniers mois.** Le rapport est téléchargé en tant que feuille de calcul Excel. Si vous avez sélectionné au-delà de 31 jours, la feuille de calcul aura un onglet individuel pour chaque jour. Le téléchargement des 12 derniers mois aura un onglet pour chaque mois.

Pour afficher les principales requêtes de Bing et les rapports de distribution des impressions, cliquez sur le lien de la page.

## <a name="frequently-asked-questions"></a>Foire aux questions

**Lorsque je sélectionne les 31 derniers jours ou les 12 derniers mois, pourquoi dois-je choisir un jour ou un mois spécifique ?**

L’affichage Calendrier, aujourd’hui, dans les rapports d’utilisation de la recherche Microsoft est un processus en deux étapes. Tout d’abord, sélectionnez la plage de dates dans la dropdown (31 derniers jours ou 12 derniers mois), puis sélectionnez le jour ou le mois de début.

Les tables de requête en haut, abandonnées et échouées indiquent les résultats du jour ou du mois que vous choisissez.

**Quand vais-je voir les données agrégées pour les 7 derniers jours, les 30 derniers jours, etc... like Bing’s top queries reports?**

Nous envisageons ce type d’agrégation et simplifions le filtrage des plages de données pour les futures versions de ces rapports.

**Pourquoi ne puis-je pas voir une répartition des rapports d’utilisation par différentes applications (sources) ?**

Actuellement, le filtrage par source n’est pas disponible. Les rapports combinent les recherches à partir de La page d’accueil SharePoint Office.com. Notre prochaine version inclut le filtrage source afin que vous pouvez voir des mesures spécifiques à chaque application.

**Quel autre filtrage des rapports d’utilisation sera-t-il à venir ?**

Nous travaillons sur des filtres supplémentaires qui vous aideront à donner un sens à l’utilisation de la recherche à un niveau plus granulaire de votre organisation. Par exemple, vous pourrez voir le volume de requête pour une zone géographique ou un service spécifique.

**Pourquoi la recherche Microsoft dans les rapports Bing se trouve-t-elle sur une page distincte ?**

La modernisation de la recherche dans les applications Office 365 vers Microsoft Search (recherche Microsoft) nous a obligés à joindre des systèmes précédemment disparates, y compris la génération de rapports. Cela prend du temps et nous estimions qu’il était plus important d’obtenir ces rapports maintenant que d’attendre la fin de l’intégration des données Bing. Une fois l’intégration terminée, les données de tous les points de terminaison de recherche sont incluses dans les mêmes rapports.
