---
title: 管理元資料
description: 管理中資產的元資料 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '962'
ht-degree: 0%

---

# 元資料 [!DNL Assets Essentials] {#metadata}

元資料是指有關資料的資料或描述。 例如，作為資產的影像可以包含與其按一下的相機或任何版權資訊有關的資訊。 此資訊是映像的元資料。 元資料對於高效的資產管理至關重要。 元資料是資產可用的所有資料的集合，但不一定包含在該資產中。

元資料有助於您進一步對資產進行分類，並有助於隨著數字資訊量的增長。 僅基於檔案名、縮略圖和記憶體就可以管理幾百個檔案。 但是，這種方法不可擴展。 當涉及人數和管理資產數量增加時，這個數字就不夠。

隨著元資料的增加，數字資產的價值會增加，因為資產會變成，

* 更易於訪問 — 系統和用戶可以輕鬆找到它。
* 更易於管理 — 您可以更輕鬆地查找具有相同屬性集的資產，並將更改應用於這些資產。
* 完成 — 資產攜帶更多資訊和上下文以及更多元資料。

出於這些原因， Assets為您提供了為您的數字資產建立、管理和交換元資料的正確方法。

## 查看元資料 {#view-metadata}

要查看資產的元資料，請瀏覽到資產或搜索資產，選擇資產，然後按一下 **[!UICONTROL 詳細資訊]** 的子菜單。

![查看資產的元資料](assets/metadata-view1.png)

*圖：要查看資產及其元資料，請按一下&#x200B;**[!UICONTROL 詳細資訊]**或按兩下該資源。*

基本元資料（如標題、說明和上載日期）可在 [!UICONTROL 基本] 頁籤。 的 [!UICONTROL 高級] 頁籤包含更高級的元資料，如相機模型、鏡頭詳細資訊和幾何標籤。 的 [!UICONTROL 標籤] 頁籤包含基於影像內容的自動應用標籤。

## 更新元資料 {#update-metadata}

您可以手動更新幾個元資料欄位。 欄位包括 [!UICONTROL 標題]。 [!UICONTROL 說明]。 [!UICONTROL 作者], [!UICONTROL 關鍵字]。

## 標記 {#tags}

[!DNL Assets Essentials] 使用人工智慧 [Adobe Sensei](https://www.adobe.com/sensei.html) 自動將相關標籤應用於所有上載的資產。 這些標籤恰如其分地命名為「智慧標籤」，通過幫助您快速查找相關資產來提高項目的內容速度。 智慧標籤是映像中未包含的元資料的示例。

該智慧標籤被近即時地應用並基於影像的內容產生。 上載資產時，用戶介面將顯示 [!UICONTROL 處理] 在資產縮略圖上顯示一段時間。 處理完成後，您可以 [查看元資料](#view-metadata) 和智慧標籤。

![查看資產的智慧標籤](assets/metadata-view-tags.png)

*圖：要查看資產的智慧標籤，請按一下&#x200B;**[!UICONTROL 詳細資訊]**或按兩下該資源。*

智慧標籤還包含置信度分數（百分比）。 它指示與應用的標籤關聯的置信度。 您可以調整自動應用的智慧標籤。

## 添加或更新標籤 {#manually-tag}

除了使用 [!DNL Adobe Sensei] 智慧服務。 開啟資產進行預覽，按一下 [!UICONTROL 標籤]，並在 [!UICONTROL 關鍵字] 的子菜單。 要添加標籤，請按Return。 [!DNL Assets Essentials] 對關鍵字進行近即時索引，您的團隊很快就可以使用新關鍵字搜索更新的資產。

也可以從 [!UICONTROL 智慧標籤] 自動添加的節 [!DNL Assets Essentials] 所有上載的資產。

## 元資料表單 {#metadata-forms}

Assets Essentials預設提供許多標準元資料欄位。 組織有其他元資料需要，需要更多元資料欄位來添加特定於業務的元資料。 元資料表單允許企業將自定義元資料欄位添加到資產 [!UICONTROL 詳細資訊] 的子菜單。 特定於業務的元資料可改進其資產的治理和發現。

您可以為不同類型的資產（不同的MIME類型）配置元資料表單。 使用與檔案的MIME類型相同的表單名稱。 Essentials會自動將上載的資產與表單名稱匹配。 例如，如果元資料表單的名稱 `PDF` 或 `pdf` 存在，然後上載的PDF文檔包含在表單中定義的元資料欄位。 您可以從頭建立表單或重新調整現有表單的用途。

>[!IMPORTANT]
>
>特定檔案類型的新元資料表單將完全替換預設元資料表單 [!DNL Assets Essentials] 提供。 如果刪除或更名元資料表單，則預設元資料欄位將再次可用於新資產。

要建立元資料表單，請執行以下步驟：

1. 在左滑軌中，按一下 **[!UICONTROL 設定]** > **[!UICONTROL 元資料Forms]**。

   ![元資料表單選項在左側邊欄](assets/metadata-forms-sidebar.png)

1. 按一下 **[!UICONTROL 建立]**，在用戶介面的右上角。
1. 提供表單的名稱，然後按一下 **[!UICONTROL 建立]**。
1. 為中的頁籤提供名稱 **[!UICONTROL 設定]** 右欄。
1. 從 **[!UICONTROL 元件]** 在左滑軌中可用，拖動窗體中的頁籤上所需的元件。 按所需順序拖動元件。

   ![元資料表單選項在左側邊欄](assets/metadata-form-new.png)

   *圖：元資料表單建立介面，其中包含添加元件的選項和預覽表單的選項。*

1. 對於每個元件，在中 **[!UICONTROL 設定]** 在右滑軌中，提供具有支援屬性的映射。
1. （可選）對於元件，選擇 **[!UICONTROL 必需]** 將元資料欄位設定為必填欄位並選擇 **[!UICONTROL 只讀]** 使該欄位在資產中不可編輯 [!UICONTROL 詳細資訊] 的子菜單。
1. （可選）按一下 **[!UICONTROL 預覽]** 預覽要建立的窗體。
1. （可選）在每個頁籤中添加更多頁籤和所需元件。
1. 按一下 **[!UICONTROL 保存]** 的子菜單。

建立表單後，當用戶上載匹配MIME類型的資產時，將自動應用表單。

要重用現有表單以建立新表單，請選擇元資料表單，按一下 **[!UICONTROL 複製]** 中，提供名稱，然後按一下 **[!UICONTROL 確認]**。 您可以編輯元資料表單以更改它。 更改表單時，它用於更改後上載的資產。 它不會改變現有資產。

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
