---
title: Intégrer des PowerApps
ms.author: dawholl
author: dawholl
manager: kellis
ms.date: 12/18/2018
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
ms.assetid: 1fadcba3-4a7f-4a55-8476-d4e64d49a15f
description: Incluez des applications de navigateur dans les résultats de signet pour la fonctionnalité Recherche Microsoft
ms.openlocfilehash: 96b409274e3fa06cef7dcc6f1c43360a3e6b9d34
ms.sourcegitcommit: 3e91a6e70b48a0100adfed1b62ba79f2fd1735d2
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/13/2019
ms.locfileid: "33968376"
---
# <a name="integrate-powerapps"></a><span data-ttu-id="06759-103">Intégrer des PowerApps</span><span class="sxs-lookup"><span data-stu-id="06759-103">Integrate PowerApps</span></span>

> [!IMPORTANT]
> <span data-ttu-id="06759-104">Les paramètres de Recherche Microsoft dans Bing sont désormais accessibles dans le Centre d’administration Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="06759-104">Microsoft Search in Bing settings are now available in the Microsoft 365 admin center.</span></span> <span data-ttu-id="06759-105">Commencez par [assigner des administrateurs de recherche](https://docs.microsoft.com/fr-FR/microsoftsearch/setup-microsoft-search#step-2-assign-search-admin-and-search-editor) dans votre centre d’administration.</span><span class="sxs-lookup"><span data-stu-id="06759-105">Get started by [assigning search admins](https://docs.microsoft.com/en-us/microsoftsearch/setup-microsoft-search#step-2-assign-search-admin-and-search-editor) in your admin center.</span></span>
    
<span data-ttu-id="06759-106">Aidez vos utilisateurs à accomplir des tâches telles que saisir une période de vacances ou une note de frais en intégrant des PowerApps existants dans vos signets.</span><span class="sxs-lookup"><span data-stu-id="06759-106">Help your users complete tasks, such as entering vacation time or reporting expenses, by adding existing PowerApps to your bookmarks.</span></span> <span data-ttu-id="06759-107">Les PowerApps intégrés apparaissent dans un résultat de signet, ce qui élimine le besoin d’accéder à un autre site ou d’ouvrir un outil distinct, les heures enregistrés ainsi que vos efforts.</span><span class="sxs-lookup"><span data-stu-id="06759-107">Integrated PowerApps appear within a bookmark result, eliminating the need to go to a different site or open a separate tool, which saves times and effort.</span></span>
  
## <a name="what-are-powerapps"></a><span data-ttu-id="06759-108">Quelles sont les PowerApps ?</span><span class="sxs-lookup"><span data-stu-id="06759-108">What are PowerApps?</span></span>

<span data-ttu-id="06759-109">PowerApps est un service qui vous permet de créer des applications métier qui s’exécutent dans un navigateur ou sur un téléphone ou une tablette avec aucune expérience codage requise.</span><span class="sxs-lookup"><span data-stu-id="06759-109">PowerApps is a service that lets you build business apps that run in a browser or on a phone or tablet with no coding experience required.</span></span> <span data-ttu-id="06759-110">En savoir plus :</span><span class="sxs-lookup"><span data-stu-id="06759-110">Learn more:</span></span>
  
- <span data-ttu-id="06759-111">
  [Formation guidée](https://docs.microsoft.com/fr-FR/learn/browse/?products=powerapps)</span><span class="sxs-lookup"><span data-stu-id="06759-111">[Guided Learning](https://docs.microsoft.com/en-us/learn/browse/?products=powerapps)</span></span>
    
- <span data-ttu-id="06759-112">
  [Documentation](https://docs.microsoft.com/fr-FR/powerapps/)</span><span class="sxs-lookup"><span data-stu-id="06759-112">[Documentation](https://docs.microsoft.com/en-us/powerapps/)</span></span>
    
## <a name="add-a-powerapp-to-a-bookmark"></a><span data-ttu-id="06759-113">Ajouter un PowerApp à un signet</span><span class="sxs-lookup"><span data-stu-id="06759-113">Add a PowerApp to a bookmark</span></span>

<span data-ttu-id="06759-114">Les applications PowerApps fonctionnent dans n’importe quel navigateur ainsi que sur tout appareil, et leur ajout prend moins d’une minute.</span><span class="sxs-lookup"><span data-stu-id="06759-114">PowerApps work in any browser and on any device and take less than a minute to add.</span></span>
  
1. <span data-ttu-id="06759-115">
  [Trouvez l’ID du PowerApp](https://docs.microsoft.com/fr-FR/powerapps/maker/canvas-apps/get-sessionid#get-an-app-id) que vous souhaitez intégrer.</span><span class="sxs-lookup"><span data-stu-id="06759-115">Find the [App ID for the PowerApp](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/get-sessionid#get-an-app-id) that you want to add.</span></span> 
    
2. <span data-ttu-id="06759-116">Dans le portail d’administration de la fonctionnalité Recherche Microsoft, accédez à **Favoris**.</span><span class="sxs-lookup"><span data-stu-id="06759-116">In the Microsoft SearchAdmin portal, go to **Bookmarks**</span></span>
    
3. <span data-ttu-id="06759-117">Ajoutez un signet ou rechercher un signet existant auquel vous souhaitez ajouter un PowerApp.</span><span class="sxs-lookup"><span data-stu-id="06759-117">Add a bookmark or find an existing bookmark that you want to add a PowerApp to.</span></span>
    
4. <span data-ttu-id="06759-118">Dans les paramètres du signet, cliquez sur **PowerApp**, puis sur **Ajouter un PowerApp**.</span><span class="sxs-lookup"><span data-stu-id="06759-118">In Bookmark settings, select Power App, and then Add a Power App.</span></span>
    
5. <span data-ttu-id="06759-119">Entrez ou collez l’ID de l’application.</span><span class="sxs-lookup"><span data-stu-id="06759-119">Enter or paste the App ID.</span></span>
    
    <span data-ttu-id="06759-120">La hauteur et la largeur sont ajoutées automatiquement.</span><span class="sxs-lookup"><span data-stu-id="06759-120">The height and width are automatically adjusted.</span></span> <span data-ttu-id="06759-121">Les signets peuvent prendre en charge les orientations portrait et paysage mais il n’est actuellement pas possible de modifier la taille.</span><span class="sxs-lookup"><span data-stu-id="06759-121">Bookmarks can support both portrait and landscape orientations, but currently the size can't be changed.</span></span>
    
6. <span data-ttu-id="06759-122">L’aperçu du signet montre comment le PowerApp apparaîtra dans le résultat de signet.</span><span class="sxs-lookup"><span data-stu-id="06759-122">The bookmark preview shows how the PowerApp will appear in the bookmark result</span></span>
    
    <span data-ttu-id="06759-123">PowerApp dans l’aperçu est pleinement fonctionnel pour en faciliter le test et l’utilisation.</span><span class="sxs-lookup"><span data-stu-id="06759-123">The PowerApp in the preview is fully functional to make it easy to test and use.</span></span>
    
7. <span data-ttu-id="06759-124">Cliquez sur**Publier**.</span><span class="sxs-lookup"><span data-stu-id="06759-124">Click **Publish**.</span></span>
    
<span data-ttu-id="06759-125">Quand un utilisateur autorisé de la fonctionnalité Recherche Microsoft cherche sur Bing des mots clés ou mots clés réservés d’un des signets, le PowerApp s’affiche dans le résultat de signet.</span><span class="sxs-lookup"><span data-stu-id="06759-125">When an authorized Microsoft Search user searches on Bing for any of the bookmark's keywords or reserved keywords, the PowerApp will appear in the bookmark result.</span></span>

  

