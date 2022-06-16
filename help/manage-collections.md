---
title: 管理收藏集
description: 收藏集是 Experience Manager Assets Essentials 中的一組資產。使用收藏集在使用者之間共用資產。
exl-id: 33c889f5-c989-4772-9591-db62f50e5c80
source-git-commit: 88dd604492ffd5be305fe2f54edae1f158247e26
workflow-type: tm+mt
source-wordcount: '524'
ht-degree: 91%

---

# 管理收藏集 {#manage-collections}

收藏集是 Experience Manager Assets Essentials 中的一組資產。使用收藏集在使用者之間共用資產。

和檔案夾不同，收藏集可包含來自不同位置的資產。

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

您可以和使用者共用多個收藏集。每個收藏集都包含資產的參考資料。資產的參考完整性會跨越收藏集來維護。

![集合](assets/collections.png)

您可以執行下列任務以管理和使用收藏集：

* [建立收藏集](#create-collection)

* [將資產新增至收藏集](#add-assets-to-collection)

* [從收藏集移除資產](#remove-assets-from-collection)

* [檢視和編輯收藏集中繼資料](#view-edit-collection-metadata)

* [下載收藏集元素](#download-collection-elements)

* [刪除收藏集](#delete-collection)

## 建立收藏集 {#create-collection}

若要建立收藏集：

1. 請按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**，然後按一下&#x200B;**[!UICONTROL 建立收藏集]**。

1. 指定收藏集的標題和說明 (選用)。

1. 按一下&#x200B;**[!UICONTROL 儲存]**&#x200B;以建立收藏集。

![建立集合](assets/create-collection.png)

<!--

1. Select if you need to a create a Private collection or a Public collection.

   A Public collection is available for viewing and editing to all users. However, if you are a non-administrator user, a Private collection is available for viewing and editing only to users with the appropriate [permissions](#manage-collection-access). 

-->

## 將資產新增至收藏集 {#add-assets-to-collection}

若要將資產新增至收藏集：

1. 按一下左側邊欄中的&#x200B;**[!UICONTROL 資產]**，然後選取資產。

1. 按一下&#x200B;**[!UICONTROL 新增至收藏集]**。

1. 在[!UICONTROL 收藏集]對話框中，選取收藏集以新增所選取的資產。

1. 按一下&#x200B;**[!UICONTROL 新增]**，以將資產新增到所選取的收藏集。

若要將資產新增到收藏集，您還可以按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**，按一下要新增資產的收藏集，按一下&#x200B;**[!UICONTROL 新增至收藏集]**，選取資產並按一下&#x200B;**[!UICONTROL 選取]**。

## 從收藏集移除資產 {#remove-assets-from-collection}

若要從收藏集移除資產：

1. 請按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**，以檢視收藏集清單。

1. 按一下收藏集，然後選取您需要從收藏集移除的資產。

1. 按一下&#x200B;**[!UICONTROL 移除]**。

<!--

## Manage access to a Private collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

-->

<!--

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## 檢視和編輯收藏集中繼資料 {#view-edit-collection-metadata}

收藏集中繼資料包含有關收藏集的資料，例如標題和說明。

若要檢視和編輯收藏集中繼資料：

1. 請按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**，選一個收藏集，然後按一下&#x200B;**[!UICONTROL 詳細資訊]**。
1. 使用&#x200B;**[!UICONTROL 基本]**&#x200B;索引標籤來檢視收藏集中繼資料。
1. 修改中繼資料欄位 (如有必要)。您可以修改[!UICONTROL 標題]、[!UICONTROL 說明]以及[!UICONTROL 作者]欄位。

![集合元資料](assets/collection-metadata.png)

## 共用收藏集的連結 {#share-collection-links}

[!DNL Assets Essentials] 可讓您產生連結，並和無法存取 [!DNL Assets Essentials] 應用程式的外部利益關係人共用收藏集和收藏集中的資產。您可以定義連結的到期日，然後使用您喜歡的通訊方式 (如電子郵件或簡訊服務) 與他人共用。連結的收件者可預覽和下載資產。

![共用資產連結](assets/share-link-collections.png)

如需更多有關如何與外部利益關係人共用收藏集連結的資訊，請參閱[共用資產連結](share-links-for-assets.md)。

## 下載收藏集 {#download-collection}

要下載集合，請執行以下操作：

1. 按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**。

1. 選擇要下載的集合，然後按一下 **[!UICONTROL 下載]**。

1. 在 [!UICONTROL 正在下載資產] 對話框，按一下 **[!UICONTROL 確定]**。

該集合以.ZIP檔案形式下載到本地電腦上。

## 刪除收藏集 {#delete-collection}

若要刪除收藏集：

1. 按一下左側邊欄中的&#x200B;**[!UICONTROL 收藏集]**。

1. 選取您需要刪除的收藏集。

1. 按一下&#x200B;**[!UICONTROL 刪除]**。

## 後續步驟 {#next-steps}

* 使用 Assets Essentials 使用者介面中所提供的[!UICONTROL 意見回饋]選項提供產品意見回饋

* 若要提供文件意見回饋，請使用右側邊欄提供的[!UICONTROL 編輯此頁面]![來編輯頁面](assets/do-not-localize/edit-page.png)或[!UICONTROL 記錄問題]![來建立 GitHub 問題](assets/do-not-localize/github-issue.png)

* 連絡[客戶服務](https://experienceleague.adobe.com/?support-solution=General#support)
