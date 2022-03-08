---
title: 在中搜索和發現資產 [!DNL Assets Essentials]
description: 在中搜索和發現資產 [!DNL Assets Essentials]。
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 0%

---

# 在中搜索資產 [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] 提供有效的搜索，這在預設情況下是有效的。 搜索是全文搜索，因此是全面搜索。 強大的搜索功能使您能夠快速發現適當的資產並幫助您提高內容速度。 [!DNL Assets Essentials] 提供全文搜索，甚至搜索智慧標籤、標題、建立日期和版權等元資料。

要搜索資產，

* 在頁面頂部的搜索框中按一下。 預設情況下，它會在您當前正在瀏覽的資料夾內搜索。 執行下列操作之一：

   ![搜索框](assets/search-box.png)

   * 使用關鍵字搜索，並可選地更改資料夾。 按回車。

   * 開始使用最近查看的資產，直接搜索它。 在搜索框中按一下，然後從建議中選擇最近查看的資產。

## 篩選搜索結果 {#refine-search-results}

可以根據以下參數篩選搜索結果。

![搜索篩選器](assets/filters1.png)

*圖：根據各種參數篩選搜索的資產。*

* 檔案類型：按支援的檔案類型篩選搜索結果， `Images`。 `Documents`, `Videos`。
* MIME類型：篩選一個或多個支援的檔案格式。 <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 影像大小：提供篩選影像的最小和最大尺寸中的一個。 大小以像素為單位提供，而不是影像的檔案大小。
* 建立日期：元資料中提供的資產的建立日期。 使用的標準日期格式為 `yyyy-mm-dd`。
* 修改日期：資產的上次修改日期。 使用的標準日期格式為 `yyyy-mm-dd`。

您可以按以下順序對搜索的資產進行排序： `Name`。 `Relevancy`。 `Size`。 `Modified`, `Created`。

## 已保存的搜索 {#saved-search}

搜索功能在 [!DNL Assets Essentials]。 在搜索框中，您不僅可以鍵入關鍵字並按回車鍵查看結果，而且還可以通過按一下快速再次搜索最近搜索的關鍵字。

您還可以根據元資料和資產類型的特定條件篩選搜索結果。 對於常用的篩選器，要改進搜索體驗， [!DNL Assets Essentials] 用於保存搜索參數。 然後，也可以選擇保存的搜索以搜索並僅按一下一次即可應用篩選器。

要建立已保存的搜索，請搜索某些資產，應用一個或多個篩選器，然後按一下 [!UICONTROL 保存搜索] 的 [!UICONTROL 篩選器] 的子菜單。

![從「篩選器」面板保存的搜索](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
