---
title: 管理中繼資料
description: 在 [!DNL Assets Essentials]中管理資產的中繼資料
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: a176769247bcafcc0497f2480cdec86c5753f218
workflow-type: tm+mt
source-wordcount: '931'
ht-degree: 0%

---


# [!DNL Assets Essentials]中的元資料 {#metadata}

中繼資料是指資料或資料說明。 例如，您以資產形式使用的影像可以包含其所點按相機的相關資訊，或任何版權資訊。 此資訊是影像的中繼資料。 中繼資料對於有效管理資產至關重要。 中繼資料是資產可用所有資料的集合，但不一定包含在該資產中。

中繼資料可協助您進一步分類資產，並隨著數位資訊量增加而有所幫助。 僅根據檔案名稱、縮圖和記憶體管理幾百個檔案。 不過，此方法無法擴充。 當參與人數和受管理資產數量增加時，這個數字就不夠。

隨著中繼資料的增加，數位資產的值會隨著資產的增加而增加，

* 更容易訪問 — 系統和用戶可以輕鬆找到它。
* 易於管理 — 您可以更輕鬆找到具有相同屬性集的資產，並套用變更。
* 完整 — 資產包含更多資訊和內容，並包含更多中繼資料。

基於這些原因，Assets能提供您建立、管理和交換數位資產的中繼資料的適當方式。

## 檢視中繼資料 {#view-metadata}

若要檢視資產的中繼資料，請瀏覽至資產或搜尋資產，選取資產，然後按一下工具列中的&#x200B;**[!UICONTROL Details]**。

![檢視資產的中繼資料](assets/metadata-view1.png)

*圖：若要檢視資產及其中繼資料，請按一&#x200B;**[!UICONTROL Details]**下工具列中的，或連按兩下資產。*

[!UICONTROL Basic]標籤中提供標題、說明和上傳日期等基本中繼資料。 [!UICONTROL Advanced]標籤包含更高級的元資料，如相機型號、鏡頭詳細資訊和地理標籤。 [!UICONTROL Tags]標籤包含根據影像內容自動套用的標籤。

## 更新中繼資料 {#update-metadata}

您可以手動更新一些中繼資料欄位。 欄位包括[!UICONTROL Title]、[!UICONTROL Description]、[!UICONTROL Author]和[!UICONTROL Keywords]。

## 標記 {#tags}

[!DNL Assets Essentials] 使用AdobeSenseito提供的人 [工智](https://www.adobe.com/sensei.html) 慧，自動將相關標籤套用至所有上傳的資產。這些標籤（適當命名為「智慧標籤」）可協助您快速找到相關資產，以提高專案的內容速度。 智慧標籤是影像中未包含之中繼資料的範例。

所述智慧標籤以接近即時的方式應用並基於所述影像的內容而產生。 上傳資產時，使用者介面會在資產縮圖上顯示[!UICONTROL Processing]一段時間。 處理完成後，您可以[檢視中繼資料](#view-metadata)和智慧標籤。

![檢視資產的智慧標籤](assets/metadata-view-tags.png)

*圖：若要檢視資產的智慧標籤，請按一下工&#x200B;**[!UICONTROL Details]**具列中的，或連按兩下資產。*

智慧標籤也包含信賴分數（百分比）。 它指出與套用的標籤相關聯的信賴度。 您可以協調自動套用的智慧標籤。

## 新增或更新標籤 {#manually-tag}

除了使用[!DNL Adobe Sensei]智慧服務自動新增的智慧標籤以外，您還可以新增更多標籤至資產。 開啟資產以進行預覽，按一下[!UICONTROL Tags]，然後在[!UICONTROL Keywords]欄位中輸入所需的關鍵字。 要添加標籤，請按Return。 [!DNL Assets Essentials] 幾乎即時索引關鍵字，而您的團隊很快就可以使用新關鍵字搜尋更新的資產。

您也可以從[!UICONTROL Smart Tags]區段中移除標籤，這些標籤會由[!DNL Assets Essentials]自動新增至所有已上傳的資產。

## 中繼資料表單 {#metadata-forms}

Assets Essentials預設提供許多標準中繼資料欄位。 組織有其他中繼資料需求，且需要更多中繼資料欄位，才能新增業務專屬的中繼資料。 中繼資料表單可讓企業將自訂中繼資料欄位新增至資產的[!UICONTROL Details]頁面。 特定於業務的元資料改進了其資產的治理和發現。

您可以為不同資產類型（不同MIME類型）設定中繼資料表單。 使用與檔案的MIME類型相同的表單名稱。 Essentials會自動將上傳的資產與表單名稱相符。 例如，如果名稱為`PDF`或`pdf`的元資料表單存在，則上傳的PDF文檔包含表單中定義的元資料欄位。 您可以從頭建立表單，或重新調整現有表單的用途。

>[!IMPORTANT]
>
>特定檔案類型的新中繼資料表單會完全取代[!DNL Assets Essentials]提供的預設中繼資料表單。 如果您刪除或重新命名中繼資料表單，新資產將可再次使用預設中繼資料欄位。

要建立元資料表單，請執行以下步驟：

1. 在左側邊欄中，按一下「**[!UICONTROL Settings]** > **[!UICONTROL Metadata Forms]**」。

   ![左側邊欄中的元資料表單選項](assets/metadata-forms-sidebar.png)

1. 按一下用戶介面右上方區域的&#x200B;**[!UICONTROL Create]**。
1. 提供表單的名稱，然後按一下&#x200B;**[!UICONTROL Create]**。
1. 在右側邊欄的&#x200B;**[!UICONTROL Settings]**&#x200B;中提供索引標籤的名稱。
1. 從左側邊欄中可用的&#x200B;**[!UICONTROL Components]**，在表單的索引標籤上拖曳必要元件。 以所需順序拖曳元件。

   ![左側邊欄中的元資料表單選項](assets/metadata-form-new.png)

   *圖：元資料表單建立介麵包含可新增元件的選項和可預覽表單的選項。*

1. 對於每個元件，在右側邊欄的&#x200B;**[!UICONTROL Settings]**&#x200B;中提供名稱，提供與支援屬性的對應。
1. （可選）對於元件，選擇&#x200B;**[!UICONTROL Required]**&#x200B;使元資料欄位成為必填欄位，選擇&#x200B;**[!UICONTROL Read-Only]**&#x200B;使資產[!UICONTROL Details]頁面中的欄位不可編輯。
1. 或者，按一下&#x200B;**[!UICONTROL Preview]**&#x200B;預覽您正在建立的表單。
1. （可選）在每個標籤中新增更多標籤和必要的元件。
1. 表單完成時，按一下&#x200B;**[!UICONTROL Save]**。

建立表單後，當使用者上傳相符MIME類型的資產時，就會自動套用表單。

要重複使用現有表單以建立新表單，請選擇元資料表單，從工具欄按一下&#x200B;**[!UICONTROL Copy]**，提供名稱，然後按一下&#x200B;**[!UICONTROL Confirm]**。 您可以編輯中繼資料表單以進行變更。 當您變更表單時，該表單會用於變更後上傳的資產。 不會變更現有資產。

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
