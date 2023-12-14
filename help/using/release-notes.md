---
title: 發行說明
description: ' [!DNL Assets Essentials] 的發行說明和已知問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7a34bf9aa740c647530306c3edde6e493f80790a
workflow-type: ht
source-wordcount: '2562'
ht-degree: 100%

---

# [!DNL Assets Essentials] 的發行說明 {#release-notes}

目前版本的 Assets Essentials 於 2023 年 11 月 30 日發行。

新功能包括：

**AEM Assets 中的嵌入式 Adobe Express 編輯器**

可存取 Express 的使用者現在可以直接在 AEM Assets 中使用整合在內的 Adobe Express 和 Adobe Firefly 影像編輯和建立工具，以提升內容重複使用效能並加快內容速度。

![將中繼資料表單指派至資料夾](/help/using/assets/adobe-express-aem-assets.png)

<!--

**Smart tags blocklist** 

Assets Essentials now enables you to define a list of blocked tags. These tags are automatically removed from the auto-generated smart tags when you upload assets to the repository. This capability performs tags governance and saves a lot of time as you can add a tag to the block list and Assets Essentials automatically excludes it from the list of tags for any of the assets that are added to the repository.

  ![storage usage insights](/help/using/assets/block-tags.png)

-->

**Insights 中的儲存使用情況報告**：

管理員現在可以查看作為 Insights 一部分提供的儲存空間使用量報告。

![儲存空間使用量深入解析](/help/using/assets/storage-usage-insights.png)

**搜尋優先首頁設定**

Assets Essentials 現在可讓您設定組織的首頁體驗。如果您選取搜尋優先作為首頁，您可以為您的組織設定搜尋列對齊方式、背景影像和標誌。

![搜尋優先設定](/help/using/assets/search-first-configuration.png)



**根據客戶回饋意見進行的改進功能**

根據客戶意見回應進行的增強功能和錯誤修正。


## 已知問題 {#known-issues}

[!DNL Assets Essentials] 方案的已知問題清單將持續進行修訂和更新：

<!--

* Assets Essentials does not support creating Private collections.

-->


* 專用集合可供建立者和具有管理員權限的使用者使用。作為管理員，您無法將存取集合的權限委派給其他使用者。

* 作為管理員，您無法將存取集合的權限委派給其他使用者。

如果您遇到任何問題或甚至是增強功能請求，[請向團隊提供意見回饋](#provide-feedback)。

## 舊版本 {#past-releases}

### 2023 年 10 月版 {#october2023-release}

**從 OneDrive 資料來源大量匯入資產**

管理員現在能夠[從 OneDrive 將大量資產匯入到 AEM Assets](/help/using/bulk-import-assets-view.md)。支援大量匯入的資料來源清單已更新，其中包括 Azure、AWS、Google Cloud、Dropbox 和 OneDrive。

![將中繼資料表單指派至資料夾](/help/using/assets/bulk-import-source-details.png)

**針對資料庫的跨組織權益支援**

Experience Manager Assets 現在可讓您設定在不同 IMS 組織中存取 Creative Cloud libraries。它允許更輕鬆地在 Creative Cloud 和 Experience Manager 之間存取最新跨產品工作流程，減少創作者工作所需時間和精力。

### 2023 年 9 月版本 {#september2023-release}

**將中繼資料表單指派至資料夾**

現在您可以將中繼資料表單指派到 Assets Essentials 部署中的特定資料夾。然後，資料夾中的所有資產 (包括子資料夾中的資產) 將顯示被指派中繼資料表單中定義的屬性。

![將中繼資料表單指派至資料夾](/help/using/assets/assign-to-folder.png)

**從資料來源大量匯入資產**

管理員現在能夠將大量資產從資料來源匯入到 AEM Assets。 管理員不再需要將個別資產或資料夾上傳到 AEM Assets。 支援大量匯入的資料來源包括 Azure、AWS、Google 雲端和 Dropbox。

![從資料來源大量匯入資產](/help/using/assets/bulk-import.png)

**由 Adobe Express 提供支援的影像編輯工具**

由 Adobe Express 提供支援的簡單且直觀的影像編輯工具可直接在 AEM Assets 中使用，以增加內容重複使用並加快內容流通速度。

![使用 Adobe Express 進行影像編輯](/help/using/assets/edit-adobe-express.png)

**為「我的工作區快速存取」釘選項目時具備靈活性**

能夠為您自己、整個組織或群組清單選取和釘選項目，讓這些項目能夠根據您的選取顯示在「我的工作區」的「快速存取」區段中。

![為群組釘選項目](assets/pin-items-for-groups.png)


### 2023 年 7 月版 {#july2023-release}

 **影像智慧標記已改良的人工智慧框架**

Experience Manager Assets 現在為影像智慧標記使用改良的人工智慧框架。 此內容智慧可提高智慧標記的相關性和準確性，在擷取時可用於所有影像資產。

**設定「資產清單」視圖的資料欄顯示**

Assets Essentials 現在提供可選取顯示在「資產清單」視圖中的資料欄功能，例如「狀態」、「格式」、「維度」、「大小」等。

![設定資料欄](/help/using/assets/configure-columns.png)

**根據相關性對為搜尋結果進行排序**

Assets Essentials 現在會根據相關性 (依預設) 為搜尋結果進行排序。您可以依照 `Name`、`Relevance`、`Size`、`Modified` 和 `Created` 的遞增或遞減順序排序搜尋的資產。

### 2023 年 6 月版 {#june2023-release}

**資產的階層式標記可提供更快速的搜尋體驗**

受控詞彙的平面清單會隨著時間推移而變得難以管理。Assets Essentials 現在支援標記階層結構，這有助於套用相關的中繼資料、將資產分類、支援搜尋、重複使用標記、提高易尋性等。

![標記管理](assets/tags-hierarchy.png)

**釘選檔案、資料夾和集合以便快速存取**

現在可以釘選檔案、資料夾和集合，以便在之後需要時可以更快速地存取這些項目。釘選的項目都顯示在「我的工作區」的&#x200B;**快速存取**&#x200B;部分。您可以使用「我的工作區」進行存取，而不是瀏覽到存放庫中儲存的位置。

![Workspace 中的任務](assets/quick-access.png)

**篩選「垃圾桶」資料夾的資產**

Assets Essentials 目前讓您可以篩選「垃圾桶」資料夾中的資產。您也可以套用標準或自訂篩選條件搜尋「垃圾桶」資料夾中的適當資產，以恢復或永久刪除。

**3D 資產的縮圖預覽**

Assets Essentials 現在可以生成常見 3D 檔案格式的縮圖預覽，包括 gLB、USDz、FBX、3DS、OBJ 和 SBSAR。當這些檔案上傳到 Assets Essentials 時，系統會依預設情況自動生成縮圖。

![工作區中的任務](assets/3d-preview.png)

**檢視熱門搜尋詞彙**

Assets Essentials 現在支援使用「我的工作區」的 **Insights** 部分，檢視在 Assets Essentials 部署中的熱門搜尋詞彙。您也可以瀏覽到詳細的 Insights 以檢視過去 30 天或 12 個月內的熱門搜尋。

![Workspace 中的任務](assets/insights-top-searches.png)

**中繼資料表單增強功能**

Assets Essentials 現在讓您可以在中繼資料表單新增多值文字和下拉式清單屬性元件。

### 2023 年的多個版本 {#multiple-releases-2023}

最近新增功能清單包括：

**熱門下載資產**

「我的工作區」現在會在「[!UICONTROL 內容]」區段顯示您 Assets Essentials 環境中前十個下載次數最多的資產。您也可以檢視每個所列資產的格式類型和下載次數。

**資產中繼資料的大量更新**

大量中繼資料更新可讓您同時對多個資產執行常見的中繼資料更新。您不需要個別更新記錄，可以快速將屬性套用到資產或資料夾 (透過搜尋存取)。

**我的工作區與可設定的 Widget**

Assets 現在為您提供一個可自訂的工作區，這可用作一站式解決方案，提供 Widget 以方便存取資產使用者介面的關鍵區域以及與您最相關的資訊。更快存取這些選項可以提高您專案的內容速度和效率。

「我的工作區」包括用於 Insights、任務和內容的 Widget。您可以根據自己的偏好設定這些 Widget 在 Workspace 中的顯示方式。

**專用任務管理 UI**

Assets Essentials 現在能讓您使用左側導覽窗格中可用的全新「**[!UICONTROL 任務]**」選項，在一個集中位置管理目前指派給您、您所建立以及您已完成的任務清單。您還可以選取任務來核准或拒絕它，或開啟任務詳細資訊來核准、拒絕、編輯或刪除它，藉以採取適當的動作。

![Workspace 中的任務](assets/tasks-workspace.png)

**自動產生的連結以共用資產**

Assets Essentials 現在會在您選取使用 Assets Essentials 使用者介面共用資產時，立即自動產生一個連結。即使您變更到期日，產生的連結仍然有效。

![Workspace 中的任務](assets/share-asset.png)


**根據客戶回饋意見進行的改進功能**

根據客戶意見回應進行的增強功能和錯誤修正。

### 2022.11.0 {#november-2022}

11 月版的 [!DNL Assets Essentials]於 2022 年 11 月 17 日發行。

此版本提供：

**使用 Document Cloud 檢視器預覽文件**

Assets Essentials 現在可讓您上傳其他支援格式類型的文件，並使用隨附的 Document Cloud 檢視器進行預覽。支援的格式類型包括 TXT、RTF、DOC、DOCX、PPT、PPTX、XLS 和 XLSX。

<!--

**View Smart Tags moderation reports**

Asset reporting now provides administrators with visibility into the Smart Tags promoted or deleted for an asset. You can specify a folder path and the report lists the Smart Tags promoted or deleted for all assets available at the folder path.

-->

<!--
**Read-only access to large number of users**

Assets Essentials allows administrators to provide read-only access to a large number of users for selected assets or folders in the repository. 
You can easily synchronize the user groups available on the external identity management of an organization with Adobe Admin Console and then manage permissions in Admin Console and Assets Essentials to provide the users with read-only access for selected assets or folders.

-->


**新的儲存中繼資料選項**

Assets Essentials 使用者介面現在提供了新的儲存中繼資料選項，以更好地管理中繼資料。

**根據客戶回饋意見進行的改進功能**

根據客戶意見回應進行的增強功能和錯誤修正。

**Adobe Asset Link 3.3 版**

[Adobe Asset Link](https://helpx.adobe.com/tw/enterprise/using/adobe-asset-link.html) 3.3 版於 2022 年 12 月 13 日發佈，包含以下功能：

* 除了先前支援的[適用於企業的 Creative Cloud](https://www.adobe.com/tw/creativecloud/business/enterprise.html) 之外，還支援[適用於團隊的 Creative Cloud](https://www.adobe.com/tw/creativecloud/business/teams.html)。

* 支援最新的 Adobe InDesign、Photoshop 和 Illustrator 2023 應用程式。

* 支援在具有代理伺服器的環境中使用 Adobe Asset Link CEP 外掛程式。

### 2022.8.0 {#august-2022}

八月版本的 [!DNL Assets Essentials] 於 2022 年 8 月 22 日發行。

此版本提供：

**集合通知**

Assets Essentials 通知可讓您監視對存放庫中可用集合執行的動作。您需要選取並訂閱向您傳送通知的集合。您還可以配置傳送通知的動作，例如在集合上執行的刪除、共用連結、移動、重新命名和更新動作。

**編輯智慧型集合**

Assets Essentials 現在還提供在建立智慧型集合時編輯搜尋條件的功能。儲存新的搜尋條件以動態更新集合內容。

**檢視儲存體帳戶的即時統計資料**

Assets Essentials 現在也可讓您使用「即時統計」儀表板檢視 Assets Essentials 環境的即時儲存體帳戶資料。您可以檢視過去 30 天或過去 12 個月的即時事件量度。

**查看上傳報告**

現在資產報告可讓管理員查看上傳到 Adobe Experience Manager Assets Essentials 部署的資產。管理員已經能為從 Assets Essentials 部署下載的資產生成報告。此資料提供有關使用者如何與內容和產品互動的有用資訊。

**根據客戶回饋意見進行的改進功能**

根據客戶意見回應進行的增強功能和錯誤修正。

### 2022.6.0 {#june-2022}

[!DNL Assets Essentials] 的六月版本於 2022 年 7 月 14 日發行。

此版本提供：

**Smart Collection**

將搜索結果另存為 Smart Collection 以動態更新集合內容。如果向 Assets Essentials 存放庫添加的資產符合在[建立 Smart Collection](manage-collections.md#create-smart-collection)，Smart Collection 的內容會自動更新。

**通知**

Assets Essentials 通知使您[監視對存放庫中可用的資產或資料夾執行的動作](manage-notifications.md)。您需要選取並訂閱將通知傳送給您的內容。您還可以配置通知傳送給您的類別。

**報告**

資產報告使管理員能夠評估 Adobe Experience Manager Assets Essentials 內的使用者活動。報告和即時統計儀表板提供有關使用者如何與部署中可用資產互動的有用資訊。[使用報告中的資訊](manage-reports.md)取得關鍵成功度量，以衡量企業內和客戶對資產的採用程度。

查看資產下載報告和即時統計儀表板模組，以查看正在下載哪些資產和下載頻率。

### 2022.5.0 {#may-2022}

[!DNL Assets Essentials] 的五月版本於 2022 年 6 月 16 日發行。

此版本提供：

**資產狀態增強功能**

* Assets Essentials 目前讓您可以[設定資產的有效日期](manage-organize.md#set-asset-status)。此外，您可以[](search.md#refine-search-results)根據`Expired`資產狀態和有效日期範圍篩選資產。

* 您現在可以在 Trash 檢視所有可用資產的資產狀態指示器。因此，您可以根據資產狀態來決定恢復資產。

**搜尋篩選增強功能**

* Assets Essentials 目前讓您可以[](search.md#refine-search-results)使用`No Status`資產狀態篩選資產。

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**收藏集增強功能**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials 現在支援[下載收藏集](manage-collections.md)。

* 您現在可以為收藏集編輯說明中繼資料欄位。

**文件增強功能**

* 目前已推出 [Assets Essentials 概述文件](introduction.md)的全新版本。

**根據客戶回饋意見進行的改進功能**

* 根據客戶意見回應進行的增強功能和錯誤修正。

### 2022.4.0 {#april-2022}

目前版本的 [!DNL Assets Essentials] 於 2022 年 5 月 12 日發行。此版本提供：

* [!DNL Assets Essentials] 現在支援[建立收藏集](manage-collections.md)。收藏集是 Experience Manager Assets Essentials 中的一組資產。使用收藏集在使用者之間共用資產。和檔案夾不同，收藏集可包含來自不同位置的資產。

* Assets Essentials 現在還能讓您[新增自訂篩選器](search.md#custom-filters)到使用者介面。然後，除了標準篩選器之外，您還可以套用這些自訂篩選器來縮小您的搜尋結果。

* Assets Essentials 現在可讓您對存放庫中的可用資產[設定狀態](manage-organize.md#set-asset-status)。設定資產狀態以將數位資產的下游消費控管和管理得更好。

* 根據客戶意見回應進行的增強功能和錯誤修正。

#### Chrome 中的無痕模式 {#incognito-mode}

在此版本中，我們將 UI 傳遞的效能和 Assets Essentials 中的特定功能 (對資產和影像編輯進行評論) 最佳化，會依據瀏覽器本機儲存空間和啟用的協力廠商 cookie 而定。預設情況下，Chrome 網頁瀏覽器中的無痕模式會封鎖協力廠商 cookie，使用者若要繼續存取所有功能，有多種選項。

* 當使用者需要將瀏覽器工作階段分開時，可使用 Chrome 設定檔代替無痕模式。

* 請關閉 Chrome 中無痕模式畫面上的 `Block third-party cookies`

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] 於 2022 年 3 月 9 日發行，包含下列更新：

* [!DNL Assets Essentials] 現在可讓您[產生連結，並和沒有 [!DNL Assets Essentials] 應用程式的外部利益關係人共用資產](share-links-for-assets.md)。您可以定義連結的到期日，然後使用您喜歡的通訊方式 (如電子郵件或簡訊服務) 與他人共用。連結的收件者可預覽和下載資產。

* 除了現有的一般和消費者使用者產品設定檔外，該 [!DNL Assets Essentials] 現在還包含[ Admin Console 中的管理員產品設定檔](deploy-administer.md#add-users-to-essentials)。管理員現在可以將其他使用者指派至該管理員產品設定檔。

* Assets Essentials 現在可讓管理員[管理存放庫中檔案夾的存取層級](manage-permissions.md)。身為管理員，您可建立使用者群組並指派權限給這些群組，以管理存取層級。您還可以將權限管理權委派給檔案夾層級的使用者群組。

* 根據客戶意見回應進行的增強功能和錯誤修正。

此外，適用於 Creative Cloud (Photoshop、Illustrator 和 InDesign) 的 [!DNL Adobe Asset Link] 擴充功能已發行[新版本 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，包含面板啟動時間和下載速度中的效能改善。


### 2022.1.0 版 {#january-2022}

[!DNL Assets Essentials] 於 2022 年 2 月 3 日發行，包含下列更新：

* [!UICONTROL 建立檔案夾]動作的效能提高。<!-- CQ-4338818 -->

### 2021.11.0 版 {#november-2021}

[!DNL Assets Essentials] 於 2021 年 12 月 16 日發行，包含下列更新：

* Adobe 會在完成佈建程序後自動部署 Assets Essentials。管理員不需要執行額外的步驟，透過 [!DNL Cloud Manager] 使用者介面部署 Assets Essentials。此自動部署可供在 2022 年 1 月 6 日後佈建的環境使用。
* 搭配 Assets Essentials 的新版 Creative Cloud 增效模組可在 Adobe Exchange - [Adobe Asset Link for Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [Adobe Asset Link for Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) 上使用。
* 各種錯誤修正和產品增強功能，包括之前的已知問題 (上傳後資料夾現在會在正確在左導覽樹狀目錄中顯示<!-- CQ-4337638 -->、 拖放上傳功能可讓使用者在拖曳上傳時選取目前的資料夾或任何子資料夾<!-- CQ-4327753 -->)。

### 2021.8.0 版 {#august2021}

[!DNL Assets Essentials] 2021.8.0 於 2021 年 8 月 30 日發行，包含下列更新：

* 與 [!DNL Adobe Workfront] 整合，可讓 [!DNL Workfront] 使用者在管理工作時管理其數位資產。

### 2021.7.0 版 {#july2021}

[!DNL Assets Essentials] 2021.7.0 於 2021 年 7 月 29 日發行，包含下列更新：

* 您可以建立和管理自訂的中繼資料表單，以便用於在資產詳細資訊畫面 (在 [!DNL Settings] 下方的 [!UICONTROL 中繼資料表單] 選項中) 中向使用者顯示中繼資料屬性。請參閱[中繼資料表單](metadata.md#metadata-forms)。
* 各種錯誤修正和產品改良功能，包括上傳包含許多子資料夾的巢狀資料夾時效能提高。

### 2021.6.0 版 {#june2021}

第一版的 [!DNL Assets Essentials] 於 2021 年 6 月 21 日推出，提供輕量版的資產管理功能。它支援下列主要功能和 CRUD (建立、讀取、更新和刪除) 作業：

* 上傳和新增資產，包括巢狀資料夾。預覽資產和版本。
* 用於快速資產探索的全文檢索搜尋、細微搜尋篩選器和已儲存搜尋。
* 基本資產管理作業，例如更新、刪除、下載和管理中繼資料。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 使用者在建立訊息時管理資產。
