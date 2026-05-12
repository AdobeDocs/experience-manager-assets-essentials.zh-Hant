---
title: Assets Essentials 中的大量後設資料編輯
description: 了解如何針對 Assets Essentials 上多個資產的一組預先定義標準後設資料欄位同時進行更新。
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
TQID: https://experienceleague.adobe.com/zfRAzwQWEhdCwSVuWKDz-ndudFtv-mIhmjzyNkg8sOQ
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a01bfd36-4ab8-4bf8-9dc0-5b45b890552e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: f8a45b24-4be7-4f1b-909b-60d06b483a20
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 649
ht-degree: 100%

---

<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime 與 Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="http://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>AEM Assets 與 Edge Delivery Services 整合</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新">
            <a href="https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI 擴充性</b></a>
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

# Assets Essentials 中的大量後設資料編輯{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

使用者可以透過 Assets Essentials 中的&#x200B;**大量後設資料編輯**&#x200B;功能，針對多個資產檔案的一組預先定義標準後設資料欄位同時進行編輯。 選取多個資產並同時大量更新其預先定義的標準後設資料，而非針對每個資產分別更新這些標準後設資料。 此功能可以提升大量資產標準後設資料屬性的效率、一致性和準確性，從而改善資產可搜尋性及組織架構。

## 大量編輯資產後設資料 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

執行這些步驟，一次大量編輯多個資產的後設資料：

1. 在 Assets Essentials 上，按一下「**Assets**」。
1. 瀏覽尋找特定資產，或於搜尋列中使用關鍵字進行搜尋。
1. 選取資產，然後按一下上方選單中的「**大量後設資料編輯**」。
   ![大量後設資料編輯](/help/using/assets/bulk-metadata-edit1.png)
1. 在「編輯後設資料」頁面的「**屬性**」面板中，編輯下列欄位：
   * **狀態：**&#x200B;選取所選資產的狀態。
   * **到期日：**&#x200B;設定資產不再有效或不再是系統所需的日期。
   * **作者：**&#x200B;指定作者名稱。
   * **關鍵字：**&#x200B;新增提供資產概括性資訊的特定詞語或文字字串，提升資產的可搜尋性。 新增關鍵字，然後按下 Enter 鍵或返回鍵，將其他關鍵字新增至清單中。
   * **標記：**&#x200B;按一下![「標記」圖示](/help/using/assets/tags-icon.svg)，從可用的選項中選取標記。 標記可提供關於資產的更具體資訊，並增強其可搜尋性。 「**屬性**」面板中會顯示已套用至所選資產的標記。 如果未找到相關標記，請建立這些標記，並將其指派給所選資產。 如需關於建立標記及將其指派至資產的詳細資訊，請參閱[管理 Assets Essentials 中的標記](/help/using/tagging-management.md)。
   * 按一下「**儲存**」，將上述後設資料更新套用至所選資產。 儲存後，資產會增補「關鍵字」和「標記」的項目，而所更新的「狀態」、「到期日」和「作者」詳細資料會覆寫其現有資料。
     ![儲存大量後設資料編輯屬性](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >您一次可以編輯 100 個資產的後設資料。

若要查看已套用於資產的後設資料更新內容，請導覽至資產詳細資料頁面 (選取資產，然後按一下「**詳細資料**」)，然後按一下「![](/help/using/assets/info-icon-solid-black.svg)」，在「**資訊**」面板中查看資產的後設資料。

>[!NOTE]
>
>無論資料夾特定的後設資料為何，**狀態**、**到期日**、**作者**、**關鍵字**&#x200B;和&#x200B;**標記**&#x200B;是支援大量後設資料編輯的標準後設資料屬性。 這些後設資料屬性必須包含在套用至該資產資料夾的後設資料表單內，才會顯示於資產詳細資料頁面上。 如果在資產詳細資料頁面上找不到這些標準後設資料屬性，請編輯資產資料夾的後設資料表單並納入這些屬性。 請參閱 [Assets Essentials 的後設資料](/help/using/metadata.md)，了解如何建立或編輯後設資料表單並將其套用至資料夾。
