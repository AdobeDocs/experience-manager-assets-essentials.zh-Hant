---
title: 發行說明
description: ' [!DNL Assets Essentials] 的發行說明和已知問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 59%

---

# [!DNL Assets Essentials] 的發行說明 {#release-notes}

當前版本 [!DNL Assets Essentials] 於2022年3月9日公佈。 此版本提供：

* [!DNL Assets Essentials] 現在可以 [與外部利益相關方建立聯繫並共用資產](share-links-for-assets.md)，他們無權訪問 [!DNL Assets Essentials] 的子菜單。 您可以定義連結的過期日期，然後使用您首選的通信方法（如電子郵件或消息服務）與他人共用該連結。 連結的收件人可以預覽資產並下載它們。

* 的 [!DNL Assets Essentials] 現在 [管理員產品配置檔案](deploy-administer.md#add-users-to-essentials) Admin Console，以及現有常規和消費者產品配置檔案。 管理員現在可以將其他用戶分配給管理員產品配置檔案。

* Assets Essentials現在允許管理員 [管理儲存庫中可用資料夾的訪問級別](manage-permissions.md)。 作為管理員，您可以建立用戶組並將權限分配給這些組以管理訪問級別。 您還可以將權限管理權限委託給資料夾級別的用戶組。

* 基於客戶反饋的增強和錯誤修復。

另外， [!DNL Adobe Asset Link] Creative Cloud(Photoshop、Illustrator和InDesign) [新版本3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，在面板啟動時間和下載速度方面都提高了效能。


## 已知問題 {#known-issues}

[!DNL Assets Essentials] 方案的已知問題清單將持續進行修訂和更新：

* 無

如果您遇到任何問題或甚至是增強功能請求，[請向團隊提供意見回饋](#provide-feedback)。

## 舊版本 {#past-release}

### 2022.1.0 版本 {#january-2022}

[!DNL Assets Essentials] 2022年2月03日發佈，並更新如下：

* 對 [!UICONTROL 建立資料夾] 的下界。 <!-- CQ-4338818 -->

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

* 您可以建立和管理自定義元資料表單，以便在中的資產詳細資訊螢幕中向用戶顯示元資料屬性 [!UICONTROL 元資料Forms] 選項 [!DNL Settings]。 請參閱[中繼資料表單](metadata.md#metadata-forms)。
* 各種錯誤修正和產品改良功能，包括上傳包含許多子資料夾的巢狀資料夾時效能提高。

### 2021.6.0 版本 {#june2021}

第一版的 [!DNL Assets Essentials] 於 2021 年 6 月 21 日推出，提供輕量版的資產管理功能。支援以下重要功能和 CRUD (建立、讀取、更新和刪除) 作業：

* 上傳和新增資產，包括巢狀資料夾。預覽資產和版本。
* 用於快速資產探索的全文檢索搜尋、細微搜尋篩選器和已儲存搜尋。
* 基本資產管理作業，例如更新、刪除、下載和管理中繼資料。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 使用者在建立訊息時管理資產。如需詳細資訊，請參閱[與 Adobe 解決方案的整合](/help/integration.md)。
