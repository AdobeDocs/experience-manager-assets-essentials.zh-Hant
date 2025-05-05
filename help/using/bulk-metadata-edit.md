---
title: 在Assets Essentials中大量中繼資料編輯
description: 瞭解如何同時為Assets Essentials上的多個資產更新預先定義的標準中繼資料欄位集。
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
source-git-commit: 461773235cb2d27d334b5ceb23f959dc9a848716
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 4%

---


<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime和Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="http://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>AEM Assets與Edge Delivery Services整合</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI擴充性</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>自訂搜尋篩選器</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>搜尋最佳實務</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>中繼資料最佳實務</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Content Hub</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>具有 OpenAPI 功能的 Dynamic Media</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>AEM Assets 開發人員文件</b></a>
        </td>
    </tr>
</table>

# 在Assets Essentials中大量中繼資料編輯{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Assets Essentials中的&#x200B;**大量中繼資料編輯**&#x200B;功能可讓使用者同時編輯多個資產檔案的預定義標準中繼資料欄位集。 選取多個資產並一次大量更新其預先定義的標準中繼資料集，而非針對每個資產個別更新這些標準中繼資料。 此功能可提升大量資產標準中繼資料屬性的效率、一致性和準確性，進而改善資產搜尋能力及組織架構。

## 大量編輯資產中繼資料 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

執行這些步驟，一次大量編輯多個資產的中繼資料：

1. 在Assets Essentials上，按一下&#x200B;**Assets**。
1. 瀏覽特定資產，或使用搜尋列中的關鍵字進行搜尋。
1. 選取資產，然後從頂端功能表按一下&#x200B;**大量中繼資料編輯**。
   ![大量中繼資料 — 編輯](/help/using/assets/bulk-metadata-edit1.png)
1. 在「編輯中繼資料」頁面上，編輯&#x200B;**屬性**&#x200B;面板中的下列欄位：
   * **狀態：**&#x200B;選取所選資產的狀態。
   * **到期日：**&#x200B;設定資產不再有效或不再需要的日期。
   * **作者：**&#x200B;請指定作者名稱。
   * **關鍵字：**&#x200B;新增提供資產相關高階資訊的特定辭彙或文字字串，以增強其發現能力。 新增關鍵字，然後按Enter鍵或返回鍵以新增其他關鍵字至清單。
   * **標籤：**&#x200B;按一下![標籤圖示](/help/using/assets/tags-icon.svg)從可用選項中選取標籤。 標籤提供有關資產的更具體資訊，並增強其可發現性。 已套用至所選資產的標籤會顯示在&#x200B;**屬性**&#x200B;面板中。 如果您找不到相關標籤，請建立這些標籤，並將其指派給選取的資產。 如需建立和指派標籤給資產的詳細資訊，請參閱[管理Assets Essentials中的標籤](/help/using/tagging-management.md)。
   * 按一下「儲存」**&#x200B;**，將上述中繼資料更新套用至選取的資產。 儲存後，會附加關鍵字和標籤，而狀態、到期日和作者的更新詳細資訊會覆寫其現有詳細資訊。

     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >您可以一次編輯100個資產的中繼資料。

若要檢視套用至資產的中繼資料更新，請瀏覽至資產詳細資料頁面（選取資產，然後按一下&#x200B;**詳細資料**），然後按一下![](/help/using/assets/info-icon-solid-black.svg)，在&#x200B;**資訊**&#x200B;面板中檢視資產的中繼資料。

>[!NOTE]
>
>**狀態**、**到期日**、**作者**、**關鍵字**&#x200B;和&#x200B;**標籤**&#x200B;是可用於大量中繼資料編輯的標準中繼資料屬性，無論資料夾特定的中繼資料為何。 只有當這些中繼資料屬性包含在套用至資產資料夾的中繼資料表單中時，才會顯示在資產詳細資訊頁面上。 如果在資產詳細資訊頁面上找不到這些標準中繼資料屬性，請編輯資產資料夾的中繼資料表單以包含這些屬性。 請參閱Assets Essentials[&#128279;](/help/using/metadata.md)中的中繼資料，瞭解如何建立或編輯中繼資料表單並將其套用至資料夾。
