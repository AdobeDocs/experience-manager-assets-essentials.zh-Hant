---
title: 發行說明
description: ' [!DNL Assets Essentials] 的發行說明和已知問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4fcac20c15ebabcafe851ce207bd937c8a7f6b03
workflow-type: tm+mt
source-wordcount: '761'
ht-degree: 72%

---

# [!DNL Assets Essentials] 的發行說明 {#release-notes}

當前版本 [!DNL Assets Essentials] 於2022年5月12日公佈。 此版本提供：

* [!DNL Assets Essentials] 現在支援 [建立集合](manage-collections.md)。 集合是Experience Manager Assets軟體包內的一組資產。 使用集合在用戶之間共用資產。 與資料夾不同，集合可以包含來自不同位置的資產。

* Assets Essentials現在也使你 [添加自定義篩選器](search.md#custom-filters) 到用戶介面。 然後，除了標準篩選器外，還可以應用這些自定義篩選器來細化搜索結果。

* Assets Essentials現在允許你 [設定狀態](manage-organize.md#set-asset-status) 儲存庫中可用的資源。 設定資產狀態以更好地管理和管理數字資產的下游消耗。

* 根據客戶意見回應進行的增強功能和錯誤修正。

## Chrome中的隱藏模式 {#incognito-mode}

通過此版本，我們正在優化UI交付的效能以及Assets Essentials的特定功能 — 對資產和影像編輯的注釋 — 取決於瀏覽器本地儲存和啟用了第三方Cookie。 預設情況下，Chrome Web瀏覽器中的隱藏模式會阻止第三方Cookie — 用戶有多種選項可繼續訪問所有功能：

* 當用戶需要分離瀏覽器會話時，使用Chrome配置檔案而不是Incognito模式

* 關閉 `Block third-party cookies` 在Chrome的Incognito模式螢幕上

## 已知問題 {#known-issues}

[!DNL Assets Essentials] 方案的已知問題清單將持續進行修訂和更新：

* 無法使用 `No Status` 資產狀態。

* Assets Essentials不支援建立私人收藏。

如果您遇到任何問題或甚至是增強功能請求，[請向團隊提供意見回饋](#provide-feedback)。

## 舊版本 {#past-release}

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] 2022年3月09日發佈，並更新如下：

* [!DNL Assets Essentials] 現在可讓您[產生連結，並和沒有 [!DNL Assets Essentials] 應用程式的外部利益關係人共用資產](share-links-for-assets.md)。您可以定義連結的到期日，然後使用您喜歡的通訊方式 (如電子郵件或簡訊服務) 與他人共用。連結的收件者可預覽和下載資產。

* 除了現有的一般和消費者使用者產品設定檔外，該 [!DNL Assets Essentials] 現在還包含[ Admin Console 中的管理員產品設定檔](deploy-administer.md#add-users-to-essentials)。管理員現在可以將其他使用者指派至該管理員產品設定檔。

* Assets Essentials 現在可讓管理員[管理存放庫中檔案夾的存取層級](manage-permissions.md)。 身為管理員，您可建立使用者群組並指派權限給這些群組，以管理存取層級。您還可以將權限管理權委派給檔案夾層級的使用者群組。

* 根據客戶意見回應進行的增強功能和錯誤修正。

此外，適用於 Creative Cloud (Photoshop、Illustrator 和 InDesign) 的 [!DNL Adobe Asset Link] 擴充功能已發行[新版本 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，包含面板啟動時間和下載速度中的效能改善。


### 2022.1.0 版本 {#january-2022}

[!DNL Assets Essentials] 於 2022 年 2 月 3 日發行，包含下列更新：

* [!UICONTROL 建立檔案夾]操作的效能提高。<!-- CQ-4338818 -->

### 2021.11.0 版本 {#november-2021}

[!DNL Assets Essentials] 於 2021 年 12 月 16 日發行，包含下列更新：

* Adobe 會在完成佈建程序後自動部署 Assets Essentials。管理員不需要執行額外的步驟，透過 [!DNL Cloud Manager] 使用者介面部署 Assets Essentials。此自動部署可供在 2022 年 1 月 6 日後佈建的環境使用。
* 搭配 Assets Essentials 的新版 Creative Cloud 增效模組可在 Adobe Exchange - [Adobe Asset Link for Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [Adobe Asset Link for Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) 上使用。
* 各種錯誤修正和產品增強功能，包括之前的已知問題 (上傳後資料夾現在會在正確在左導覽樹狀目錄中顯示<!-- CQ-4337638 -->、 拖放上傳功能可讓使用者在拖曳上傳時選取目前的資料夾或任何子資料夾<!-- CQ-4327753 -->)。

### 2021.8.0 版本 {#august2021}

[!DNL Assets Essentials] 2021.8.0 於 2021 年 8 月 30 日發行，包含下列更新：

* 與 [!DNL Adobe Workfront] 整合，可讓 [!DNL Workfront] 使用者在管理工作時管理其數位資產。如需詳細資訊，請參閱[與 Adobe 解決方案的整合](/help/integration.md)。

### 2021.7.0 版本 {#july2021}

[!DNL Assets Essentials] 2021.7.0 於 2021 年 7 月 29 日發行，包含下列更新：

* 您可以建立和管理自訂的中繼資料表單，以便用於在資產詳細資訊畫面 (在 [!DNL Settings] 下方的 [!UICONTROL 中繼資料表單] 選項中) 中向使用者顯示中繼資料屬性。請參閱[中繼資料表單](metadata.md#metadata-forms)。
* 各種錯誤修正和產品改良功能，包括上傳包含許多子資料夾的巢狀資料夾時效能提高。

### 2021.6.0 版本 {#june2021}

第一版的 [!DNL Assets Essentials] 於 2021 年 6 月 21 日推出，提供輕量版的資產管理功能。支援以下重要功能和 CRUD (建立、讀取、更新和刪除) 作業：

* 上傳和新增資產，包括巢狀資料夾。預覽資產和版本。
* 用於快速資產探索的全文檢索搜尋、細微搜尋篩選器和已儲存搜尋。
* 基本資產管理作業，例如更新、刪除、下載和管理中繼資料。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 使用者在建立訊息時管理資產。如需詳細資訊，請參閱[與 Adobe 解決方案的整合](/help/integration.md)。
