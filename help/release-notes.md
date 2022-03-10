---
title: 發行說明
description: 發行說明和已知問題 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 0%

---

# 發行說明 [!DNL Assets Essentials] {#release-notes}

當前版本 [!DNL Assets Essentials] 於2022年3月9日公佈。 此版本提供：

* [!DNL Assets Essentials] 現在可以 [與外部利益相關方建立聯繫並共用資產](share-links-for-assets.md)，他們無權訪問 [!DNL Assets Essentials] 的子菜單。 您可以定義連結的過期日期，然後使用您首選的通信方法（如電子郵件或消息服務）與他人共用該連結。 連結的收件人可以預覽資產並下載它們。

* 的 [!DNL Assets Essentials] 現在 [管理員產品配置檔案](deploy-administer.md#add-users-to-essentials) Admin Console，以及現有常規和消費者產品配置檔案。 管理員現在可以將其他用戶分配給管理員產品配置檔案。

* Assets Essentials現在允許管理員 [管理儲存庫中可用資料夾的訪問級別](manage-permissions.md)。 作為管理員，您可以建立用戶組並將權限分配給這些組以管理訪問級別。 您還可以將權限管理權限委託給資料夾級別的用戶組。

* 基於客戶反饋的增強和錯誤修復。

另外， [!DNL Adobe Asset Link] Creative Cloud(Photoshop、Illustrator和InDesign) [新版本3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，在面板啟動時間和下載速度方面都提高了效能。


## 已知問題 {#known-issues}

已知問題清單 [!DNL Assets Essentials] 修訂並持續更新：

* 無

如果遇到任何問題，甚至是增強請求， [提供反饋](#provide-feedback) 給隊裡。

## 過去版本 {#past-release}

### 2022.1.0版 {#january-2022}

[!DNL Assets Essentials] 2022年2月03日發佈，並更新如下：

* 對 [!UICONTROL 建立資料夾] 的下界。 <!-- CQ-4338818 -->

### 2021.11.0版 {#november-2021}

[!DNL Assets Essentials] 2021年12月16日發佈，並更新如下：

* Adobe在完成設定過程後自動部署Assets Essentials。 管理員無需執行其他步驟即可使用 [!DNL Cloud Manager] 用戶介面。 此自動部署將適用於2022年1月6日以後配置的環境。
* 在Creative CloudExchange上提供了與Assets Essentials協作的新版Adobe插件 —  [AdobeAdobe XD2.1.0版資產連結](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [AdobePhotoshop資產連結/InDesign/Illustratorv 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)。
* 各種錯誤修復和產品增強功能，包括以前的已知問題(上載後，資料夾現在在左側導航樹中正確顯示<!-- CQ-4337638 -->，拖放上載允許用戶在拖放以上載時選擇當前資料夾或任何子資料夾<!-- CQ-4327753 -->)。

### 2021.8.0版 {#august2021}

[!DNL Assets Essentials] 2021.8.0於2021年8月30日發佈，更新如下：

* 與 [!DNL Adobe Workfront] 讓 [!DNL Workfront] 用戶在管理其工作時管理其數字資產。 有關詳細資訊，請參見 [與其他Adobe解決方案的整合](/help/integration.md)。

### 2021.7.0版 {#july2021}

[!DNL Assets Essentials] 2021.7.0於2021年7月29日發佈，更新如下：

* 您可以建立和管理自定義元資料表單，以便在中的資產詳細資訊螢幕中向用戶顯示元資料屬性 [!UICONTROL 元資料Forms] 選項 [!DNL Settings]。 請參閱 [元資料表單](metadata.md#metadata-forms)。
* 各種錯誤修復和產品改進，包括上載包含多個子資料夾的嵌套資料夾時的效能更好。

### 2021.6.0版 {#june2021}

第一版 [!DNL Assets Essentials]，於2021年6月21日上市，提供輕量資產管理功能。 它支援以下主要功能和CRUD（建立、讀取、更新和刪除）操作：

* 上載和添加資產，包括嵌套資料夾。 預覽資產和版本。
* 全文搜索、細緻搜索過濾器和保存搜索以快速發現資產。
* 基本資產管理操作，如更新、刪除、下載和管理元資料。
* [!DNL Assets Essentials] 可用 [!DNL Adobe Journey Optimizer] 用戶在建立消息時管理資產。 有關詳細資訊，請參見 [與其他Adobe解決方案的整合](/help/integration.md)。
