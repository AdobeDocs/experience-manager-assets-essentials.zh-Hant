---
title: 在 [!DNL Assets Essentials]中搜尋和探索資產
description: 在 [!DNL Assets Essentials]中搜尋和探索資產。
role: Business Practitioner
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 0%

---


# 在[!DNL Assets Essentials] {#search-assets}中搜尋資產

[!DNL Assets Essentials] 提供有效的搜尋，預設情況下即可運作。搜索是全面性的，因為它是全文搜索。 強大的搜尋功能可讓您快速找到適當的資產，並協助您提高內容速度。 [!DNL Assets Essentials] 提供全文搜索，甚至通過元資料（如智慧標籤、標題、建立日期和版權）進行搜索。

若要搜尋資產，

* 按一下頁面頂端的搜尋方塊。 依預設，會在您目前瀏覽的資料夾中搜尋。 執行下列任一操作：

   ![搜尋方塊](assets/search-box.png)

   * 使用關鍵字進行搜索，並選擇更改資料夾。 按回車鍵。

   * 直接搜尋最近檢視的資產，即可開始使用。 按一下搜尋方塊中的，然後從建議中選取最近查看的資產。

## 篩選搜尋結果{#refine-search-results}

您可以根據下列參數來篩選搜尋結果。

![搜尋篩選器](assets/filters1.png)

*圖：根據各種參數篩選搜尋的資產。*

* 檔案類型：根據支援的檔案類型（即`Images`、`Documents`和`Videos`）篩選搜索結果。
* MIME類型：篩選一或多個支援的檔案格式。<!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 影像大小：提供篩選影像的最小和最大尺寸之一。 大小以像素為單位提供，而不是影像的檔案大小。
* 建立日期：中繼資料中提供的資產建立日期。 使用的標準日期格式為`yyyy-mm-dd`。
* 修改日期：資產的最後修改日期。 使用的標準日期格式為`yyyy-mm-dd`。

您可以依`Name`、`Relevancy`、`Size`、`Modified`和`Created`的遞增或遞減順序來排序搜尋的資產。

## 已保存的搜索{#saved-search}

搜索功能在[!DNL Assets Essentials]中相當容易使用。 在搜尋方塊內，您不僅可以輸入關鍵字並按回車查看結果，還可以按一下即可再次快速搜尋最近搜尋的關鍵字。

您也可以根據中繼資料和資產類型的特定條件來篩選搜尋結果。 對於常用的篩選器，若要改善搜尋體驗， [!DNL Assets Essentials]可讓您儲存搜尋參數。 然後，您也可以選取儲存的搜尋，只要按一下即可搜尋並套用篩選。

若要建立儲存的搜尋，請搜尋某些資產、套用一或多個篩選器，然後按一下[!UICONTROL Filters]面板中的[!UICONTROL Save Search]。

![從「篩選器」面板儲存搜尋](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
