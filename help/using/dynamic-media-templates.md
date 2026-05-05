---
title: 如何管理 Dynamic Media 範本？
description: 了解如何使用所見即所得範本編輯器建立 Dynamic Media 範本並加入多個影像和文字圖層，以便快速建立橫幅和傳單，並在下游應用程式中使用。
hide: true
hidefromtoc: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 4c176db86c9f3219f2cb63edda71435a2aa76850
workflow-type: tm+mt
source-wordcount: '3000'
ht-degree: 99%

---

# Dynamic Media 範本{#dynamic-media-templates}

| [搜尋最佳實務](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [中繼資料最佳實務](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [Content Hub](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [AEM Assets 開發人員文件](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="管理 Dynamic Media 範本"
>abstract="透過容易使用的所見即所得介面即時建立影像和文字橫幅並進行個人化設定，再將 Dynamic Media URL 嵌入任何第一方或第三方應用程式中，打造極具吸引力的體驗。 馬上試用！"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="觀看影片"

使用所見即所得範本編輯器建立 Dynamic Media 範本並加入多個影像和文字圖層，以便快速建立橫幅和傳單，並在下游應用程式中使用。 您也可以針對範本中包含的影像和文字圖層新增參數，並使用 [Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) 即時更新這些圖層的值。

其中一些主要功能包括：

* **Dynamic Media 所見即所得範本編輯器：**&#x200B;利用影像與文字圖層建立可自訂的橫幅。
* **圖層參數化：**&#x200B;定義圖層的動態索引鍵值配對，啟用即時更新。
* **Dynamic Media URL 支援：**&#x200B;在範本中使用 Dynamic Media URL，整合來自第一方或第三方應用程式的個人化值。
* **圖層可見度控制：**&#x200B;視需要動態收合或展開圖層。
* **智慧調整文字大小：**&#x200B;自動調整文字大小，使其符合指定的區域。

Dynamic Media 範本的一些主要優勢包括：

* **最佳化 1:1 個人化：**&#x200B;根據即時客戶訊號量身打造內容。
* **減少手動工作：**&#x200B;將內容創作和管理自動化並加速執行。
* **確保一致的全通道體驗：**&#x200B;保持管道間的品牌一致性。
* **有效地重複使用內容：**&#x200B;避免內容僅使用一次，並透過動態的參數化範本進行擴展。
* **降低風險：**&#x200B;即時更新定價、折扣和連結。
* **增強客戶參與度：**&#x200B;推動互動式、情境相關的體驗。

>[!NOTE]
>
>訂閱 Enhanced Security SKU 的客戶，無法在該雲端服務方案中使用任何 Dynamic Media 功能，包括 Dynamic Media 範本。

## 開始之前{#prerequisites-for-dynamic-media-wysiwyg-template}

若要建立 Dynamic Media 範本，您必須：

1. 具備 Dynamic Media 存取權。
1. [已將您 AEM Assets 執行個體中的可用影像與 Dynamic Media 同步，以便用於建立範本](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。
1. 已在觸控式UI上驗證下列專案：
   * 在&#x200B;**[!UICONTROL 編輯 Dynamic Media 設定頁面]**&#x200B;上，設為&#x200B;**[!UICONTROL 停用 (預設)]** 的 **[!UICONTROL Dynamic Media 同步模式]**&#x200B;不會套用至所有 AEM 資料夾 (未勾選&#x200B;**[!UICONTROL 同步所有內容]**)。 如需詳細資訊，請參閱[設定 Dynamic Media 雲端服務](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。
   * 範本建立完成後要儲存之目的地資料夾或子資料夾的 **[!UICONTROL Dynamic Media 同步模式]**&#x200B;已設定為&#x200B;**[!UICONTROL 對子資料夾啟用]**。 如需詳細資訊，請參閱[設定 Dynamic Media 雲端服務](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。

## 建立 Dynamic Media 所見即所得範本{#how-to-create-dynamic-media-wysiwyg-template}

若要建立 DM 範本，請依循下列步驟：

1. [建立空白畫布](#create-a-canvas)
1. [將影像新增至畫布](#add-images-to-the-canvas)
1. [將文字圖層新增至畫布](#add-text-to-the-canvas)
1. [編輯或刪除圖層](#edit-or-delete-a-layer)
1. [將圖層參數化](#parameterise-a-layer)

### 建立空白畫布{#create-a-canvas}

執行以下步驟來建立空白畫布：

1. 導覽至 Assets Essentials 並按一下可於左側面板中看到的 **[!UICONTROL Dynamic Media Assets]**。

   ![Dynamic Media 範本](/help/using/assets/DM-Assets1.png)

1. 按一下「**[!UICONTROL 建立範本]**」，將範本儲存在 Dynamic Media Assets 之下，或導覽至資料夾並按一下「**[!UICONTROL 建立範本]**」，將範本儲存在該資料夾中。 接著出現&#x200B;**[!UICONTROL 新範本]**&#x200B;對話框。
   ![如何建立可即時自訂的動態範本](/help/using/assets/new-template.png)
若要在 **[!UICONTROL Dynamic Media Assets]** 之下[建立資料夾](/help/using/add-delete.md)，請於&#x200B;**[!UICONTROL 資產]**&#x200B;下建立資料夾。 **[!UICONTROL Assets]** 之下的資料夾樹狀結構會複製到 **[!UICONTROL Dynamic Media Assets]** 之下。
1. 指定範本名稱、定義畫布寬度和高度，然後按一下「**[!UICONTROL 建立]**」。 接著顯示空白畫布，其兩側都提供建立範本時可使用的選單選項。 停留在選單選項上即可檢視其工具提示。
   ![可即時自訂的範本](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> 允許的寬度和高度範圍是從 50 到 5000。

**右側窗格上的選單選項：**&#x200B;使用這些選項，將必要的影像和文字圖層新增至畫布。

* ![DM 範本](/help/using/assets/add-image.svg)：按一下可將影像新增至畫布。
* ![可自訂的範本](/help/using/assets/add-text.svg)：按一下可將文字新增至畫布。
* ![可自訂的範本](/help/using/assets/show-layers-list.svg)：按一下可檢視畫布上所有圖層 (影像和文字) 的清單。 新增至畫布的每個影像和文字都會以獨立的圖層呈現。

**左側窗格上的選單選項：**&#x200B;一般的編輯器動作可以使用這些選項，如下所述。

* ![DM 範本](/help/using/assets/layer-selector.svg)：選取一個圖層。
* ![建立可立即自訂的範本](/help/using/assets/undo.svg)：按一下，或按 **Ctrl** + **Z** (Windows) 或 **Cmd** + **Z** (Mac)，可復原上一個動作。
* ![用於快速建立橫幅的範本](/help/using/assets/redo.svg)：按一下，或按 **Ctrl** + **Y** (Windows) 或 **Cmd** + **Y** (Mac)，可重做上一個動作。
* ![用於快速建立傳單的範本](/help/using/assets/zoomin.svg)：按一下，或 **Ctrl** + **+** (Windows) 或 Cmd + **+** (Mac)，可放大畫布。
* ![用於快速建立橫幅的範本](/help/using/assets/ZoomOut-1.svg)：按一下，或按 **Ctrl** + **-** (Windows) 或 **Cmd** + **-** (Mac)，可縮小畫布。
* 若未編輯任何文字或屬性，請按下 **Backspace 鍵**&#x200B;或「**刪除**」來刪除所選圖層。

建立範本的過程中，於畫布圖層上按一下![「用於快速建立傳單的範本」](/help/using/assets/show-layers-list.svg)**>**「更多選項」(![](/help/using/assets/three-dots.svg))，即可隨時編輯畫布維度。
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> 範本可使用最多 20 個圖層，包括畫布。

### 將影像新增至畫布{#add-images-to-the-canvas}

執行以下步驟，將影像新增至畫布：

1. 按一下「![立即建立橫幅](/help/using/assets/add-image.svg)」，顯示「[資產選擇器](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector)」面板。 面板會顯示 AEM Assets 執行個體中同步至 Dynamic Media 的影像。
1. 瀏覽面板或使用搜尋列中的關鍵字來搜尋特定影像。
1. 將影像拖放到畫布上使用。 查看「[**[!UICONTROL 屬性面板]**](#reposition-resize-delete-a-layer)」，在畫布上縮放或移動圖層。
   ![於數秒內建立橫幅](/help/using/assets/add-image-to-canvas.png)

### 將文字圖層新增至畫布{#add-text-to-the-canvas}

執行以下步驟，將文字圖層新增至畫布：

1. 按一下「![快速建立新橫幅](/help/using/assets/add-text.svg)」，將文字圖層新增至畫布，並開啟屬性面板。
1. 選取圖層並按一下文字進行更新。
1. 啟用屬性面板中的&#x200B;**[!UICONTROL 智慧調整文字大小]**，自動調整文字長度和字型大小，以完美符合指定區域的大小。
   ![最佳自訂橫幅](/help/using/assets/add-text-layer.png)

查看[**[!UICONTROL 屬性面板]**](#reposition-resize-delete-a-layer)以便移動、縮放、旋轉或刪除圖層。 將文字格式設定為您所需的字型、大小、顏色、樣式、對齊方式 (在圖層中)，只需在面板的「**[!UICONTROL 文字]**」區段下變更各自欄位中的值。

>[!NOTE]
>
> 若要使用預設之 Adobe Sans F2 字型系列以外的字型，您必須上傳字型檔案並將其發佈至 AEM Assets 和 Dynamic Media。 如果您的實例中有一些舊字型，請務必進行[重新處理](/help/using/reprocessing.md)，方能在範本編輯器中檢視這些字型。

### 編輯或刪除圖層 {#edit-or-delete-a-layer}

執行以下步驟來編輯或刪除畫布圖層：

1. 按一下![支援動態更新的範本](/help/using/assets/show-layers-list.svg)，然後在畫布上或從「圖層」清單中選取圖層。
1. 按一下&#x200B;**更多選項**(![支援即時更新的範本](/help/using/assets/three-dots.svg))，編輯或刪除圖層。
1. 按一下「**[!UICONTROL 刪除]**」以刪除圖層。
1. 按一下「**[!UICONTROL 編輯]**」，使用「[**[!UICONTROL 屬性面板]**](#reposition-resize-delete-a-layer)」編輯圖層。
   ![快速建立橫幅](/help/using/assets/edit-delete-layer.png)

### 屬性面板{#properties-panel}

若要導覽至圖層的屬性面板：

1. 按一下![快速創作內容](/help/using/assets/show-layers-list.svg)。
1. 從清單中選取圖層。

此面板會顯示圖層中心點在畫布平面上的位置 (X 和 Y 值) 以及圖層的維度 (寬度和高度)，並提供文字格式設定選項。

![快速創作內容](/help/using/assets/properties-panel.png)

從圖層的屬性面板中，選取畫布上的另一個圖層以導覽至其屬性面板。


#### 移動、縮放、旋轉或刪除圖層{#reposition-resize-delete-a-layer}

查看編輯文字或影像圖層的常見圖層編輯動作：

* **移動圖層：**&#x200B;拖曳圖層並移動到畫布上任何位置。 此動作會更新屬性面板中的 X 和 Y 值。
* **縮放圖層：**&#x200B;選取圖層並拖曳其邊緣控點進行縮放。 此動作會更新屬性面板中的 W (寬度) 和 H (高度) 值。
* **旋轉圖層：**&#x200B;拖曳垂直放置在圖層上方的方形控點，使其繞中心旋轉。 此動作會更新屬性面板中的角度值。
* **刪除圖層：**&#x200B;按下 **Backspace 鍵**&#x200B;或「**刪除**」，然後按一下「**[!UICONTROL 確認]**」，刪除所選取的圖層。

#### 文字格式選項{#text-formatting-options-on-properties-panel}

將文字格式設定為您所需的字型、大小、顏色、樣式、對齊方式 (在圖層中)，只需在面板的「**[!UICONTROL 文字]**」區段下變更各自欄位中的值。

**[!UICONTROL 智慧調整文字大小]**&#x200B;確定納入&#x200B;**[!UICONTROL 智慧調整文字大小]** ([自動適配文字](https://experienceleague.adobe.com/zh-hant/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting))，藉由智慧調整文字大小和長度，完美符合指定區域的大小。 此功能可防止文字溢位，或盡量減少文字底部的額外空白。
![快速創作內容](/help/using/assets/smart-text-resize.png)

### 將圖層參數化 {#parameterise-a-layer}

建立包含多個影像和文字圖層的範本後，將所選取的圖層參數化。 將圖層或其屬性參數化後，便會取得索引鍵值組 (也稱為參數)。 您可以在範本 URL 中包含這個參數，以便即時更新圖層的位置、大小或內容，達到即時自訂範本的效果。

若要將圖層參數化：

1. 按一下![立即創作內容](/help/using/assets/show-layers-list.svg)，選取圖層並一下「**[!UICONTROL 參數]**」。 接著顯示「**[!UICONTROL 參數]**」面板。
1. 切換「**[!UICONTROL 包含引數]**」功能，將屬性參數化。 查看[此處](#parameterisation-options-or-allowed-parameters)，了解參數化後的屬性行為。
1. **選用：**&#x200B;將參數重新命名。 參數名稱是在圖層名稱之後加上後綴。 所選圖層的所有參數化屬性會使用相同的圖層名稱並在後面加上不同的後綴。 依照語意命名慣例將圖層重新命名，以便在 URL 中加入此參數時，參數名稱本身就能說明圖層的內容或其用途。
1. 按一下&#x200B;**[!UICONTROL 儲存]**。
   ![立即創作內容](/help/using/assets/parameterise-a-layer.png)
若要在影像和文字圖層的參數面板之間切換，請選取畫布上的圖層，然後按一下「**[!UICONTROL 參數]**」。

#### 參數面板選項 {#parameterisation-options-or-allowed-parameters}

參數化的屬性可做為 URL 參數加入到範本 URL 中，以便使用 URL 即時編輯範本。

**影像參數：**

**X：**&#x200B;加入後，只要變更 URL 中的參數值，即可讓圖層沿其中心線水平移動，且平行於範本平面的 X 軸。
**Y：**&#x200B;加入後，只要變更 URL 中的參數值，即可讓圖層沿其中心線垂直移動，且平行於範本平面的 Y 軸。
**寬度：**&#x200B;加入後，只要變更 URL 中的參數值，即可調整圖層的寬度。
**高度：**&#x200B;加入後，只要變更 URL 中的參數值，即可調整圖層的高度。
**收合：**&#x200B;加入後，即可使用 0 (展開) 和 1 (收合) 來收合或展開範本中的圖層。
**來源：**&#x200B;加入後，只要透過 URL 中的參數值變更影像路徑，即可用新影像取代圖層的影像。

**文字格式化參數：**

加入以下參數，只要更新 URL 中的參數值，即可透過 URL 編輯文字、其字型、顏色和大小。

**文字：**&#x200B;加入後即可透過 URL 更新文字。
**字型系列：**&#x200B;加入後即可透過 URL 更新文字的字型。
**字型大小：**&#x200B;加入後，即可透過 URL 更新文字的字型大小。
**文字顏色：**&#x200B;加入後，即可透過 URL 更新文字的字型顏色。

### 將圖層分組，以便同時控制其可見度{#group-layers}

另一種保持範本靈活性的方式是使用單一參數名稱來控制多個圖層。 此策略對於可見度 (收合或展開圖層) 參數有效，可更新單一範本的設計或圖形。

依照下列步驟，將多個圖層的收合參數 (![快速創作內容](/help/using/assets/Visibility-icon.svg)) 指定相同的名稱，讓您同時收合或展開這些圖層。

1. 導覽至圖層的「[**[!UICONTROL 屬性面板]**](#parameterise-a-layer)」。
1. 若之前未參數化，切換「**[!UICONTROL 收合]**」參數。
1. **選用：**&#x200B;重新命名「收合」參數。
1. 複製「收合」參數名稱。
1. 從畫布中選取其他圖層，然後切換其「**[!UICONTROL 收合]**」參數 (若未參數化)，即可前往這些圖層的「參數」面板。
1. 用複製的名稱取代其&#x200B;**[!UICONTROL 「收合」參數]**&#x200B;名稱。
1. 按一下「**[!UICONTROL 儲存]**」，將圖層分組。
1. 在「[**[!UICONTROL 預覽和發佈]**](#preview-and-publish-template-and-copy-template-deliver-url)」區段中執行步驟 3 再執行步驟 4，以檢視您的變更。

## 預覽並發佈範本以複製傳遞 URL{#preview-and-publish-template-and-copy-template-deliver-url}

執行以下步驟以預覽和發佈範本，並複製傳遞 URL：

1. 在畫布頁面上，按一下「**[!UICONTROL 預覽]**」。 您也可以導覽至 **[!UICONTROL Assets Essentials]**&#x200B;**>** **[!UICONTROL Dynamic Media Assets]** **，**&#x200B;尋找並選取您的範本&#x200B;**，**&#x200B;再按一下「**[!UICONTROL 編輯範本]**」**>**「**[!UICONTROL 預覽]**」。 預覽頁面會顯示範本、其參數 (參數化的圖層和屬性)、發佈狀態以及&#x200B;**[!UICONTROL 發佈]**&#x200B;選項。
1. 從&#x200B;**[!UICONTROL 範本參數]**&#x200B;面板中選取參數，編輯參數值並立即更新預覽中對應範本圖層的內容、大小、位置或文字格式。 例如：
   1. 選取文字圖層並編輯其文字，或
   1. 選取影像圖層，按一下![快速創作內容](/help/using/assets/add-image.svg)，從資產選擇器選取影像，然後按一下「**[!UICONTROL 重新整理]**」。

   範本會立即更新，顯示編輯過的文字，並將先前的影像替換為新影像。 此外，影像參數值會反映新的影像路徑。 同樣地，您可以調整圖層的值來進行縮放，而相關變更會即時套用至範本。
1. 從清單中選取[分群圖層](#group-layers)的收合參數，以便在範本中同時展開或收合這些圖層。
1. **選用：**&#x200B;變更「**[!UICONTROL 收合]**」參數值為 0 或 1，然後按一下「**[!UICONTROL 重新整理]**」以檢視變更。 具有相同收合參數的圖層會同時收合或展開。 同樣地，您可以於 URL 控制圖層的可見度。

   ![快速創作內容](/help/using/assets/dm-templates-publish-status.png)
您也可以切換「**[!UICONTROL 包含所有參數]**」，以編輯顯示的所有參數值，並在範本預覽中檢視更新。
   <br>
1. 若要在預覽頁面上發佈範本，請按一下「**[!UICONTROL 發佈]**」並確認發佈的內容。 接著顯示「發佈完成」訊息，且發佈狀態會更新為「已發佈」。

>[!NOTE]
>
>發佈範本需要先發佈範本影像。

### 複製傳遞 URL

在「**[!UICONTROL 預覽]**」頁面上選取的參數會成為範本 URL 中的 URL 參數。

若要複製預覽中顯示之已發佈範本的 URL：

1. 按一下「**[!UICONTROL 複製 URL]**」。 接著顯示「**[!UICONTROL 複製 URL]**」對話框。 選取並複製顯示的 URL。 請注意，URL 中的第一個參數於問號 **(?)** 之後開始 而索引鍵值組開頭為 **$**，結尾為 **&amp;**。 鍵和值由等號 **(=)** 分隔，鍵在左側，值在右側。
1. 將此 URL 貼到瀏覽器分頁中，即可檢視您的即時範本。 直接在 URL 中更新所需參數的值 (索引鍵值)，即可即時自訂範本，如&#x200B;**預覽和發佈**&#x200B;區段的[步驟 2](#preview-and-publish-template-and-copy-template-deliver-url) 所示。
1. 使用此 URL 快速推廣與銷售您的產品或服務。 您可以與客戶共用此 URL，或將 URL 整合至您的網站或任何下游第三方應用程式中，以便顯示橫幅並進行即時更新，藉此反映目前的優惠活動。

觀看這段影片並了解建立 Dynamic Media 範本的逐步流程。
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## 透過 URL 即時更新範本{#update-the-template-from-the-url}

直接在 URL 中編輯參數可能是很繁瑣的工作。 若要簡化：

1. 複製 URL 並貼到記事本中。
1. 使用 Cmd+F (Mac) 或 Ctrl+F (Windows) 來尋找及編輯參數值。 例如：
   * 取代影像圖層的影像路徑。
   * 調整圖層維度與位置 (若有[參數化](#parameterise-a-layer))。
   * 編輯文字圖層的文字、字型、顏色、大小或對齊方式。
   * 以 0 或 1 的值來變更可見度。

將此更新後的 URL 貼到瀏覽器中可檢視變更。

## 編輯範本{#edit-the-template}

依照下列步驟編輯範本：

1. 在 Assets Essentials 上，按一下 **[!UICONTROL Dynamic Media Assets]**。
2. 導覽至範本位置。
3. 選取範本。
4. 按一下「**[!UICONTROL 編輯範本]**」。 範本畫布會在「圖層」面板中顯示範本及其所有圖層的清單。 根據您的需求開始編輯範本。

## 需要注意的重要事項 {#important-points-to-note}

* 建立包含參數化影像圖層以供動態更新的範本後，請確保未來將進行更新的圖片與參數化影像具有相同的維度。 這樣能確保影像完美地嵌入圖層中，既不會溢出，也不會留下空白處。 目前，範本不支援自動調整維度讓影像符合圖層規格。
* 文字圖層不支援子字串。 使用者無法在文字圖層的子字串上套用不同的字型屬性。
* Dynamic Media 範本目前不支援多家 Dynamic Media 公司。
* 若是複製或移動，目的地選擇器會顯示所有資料夾 (包括未與 Dynamic Media 同步的資料夾)。 此外，目前也不會顯示 Dynamic Media 範本資產 (兩者都是目的地選擇器的限制)。
* 「資產」區段中對資料夾所做的任何更新 (例如「發佈」或「刪除」) 都會影響該資料夾中可用的 Dynamic Media 範本。
* 垃圾桶不適用於 Dynamic Media 範本。 如果資產移至垃圾桶後又還原，資產會在 AEM 中而非 Dynamic Media 上還原。 Dynamic Media 範本也是同樣情形。

## 另請參閱

1. 探索 [Dynamic Media 及其功能](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. 探索[具有 OpenAPI 功能的 Dynamic Media](https://experienceleague.adobe.com/zh-hant/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)
