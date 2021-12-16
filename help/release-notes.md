---
title: 發行說明
description: 發行說明和 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 1%

---

# 的發行說明 [!DNL Assets Essentials] {#release-notes}

的最新發行 [!DNL Assets Essentials] 將於2021年12月16日發行。 透過此版本：

* Adobe在完成布建過程後自動部署Assets Essentials。 管理員不需要執行其他步驟，即可使用 [!DNL Cloud Manager] 使用者介面。 此自動部署將適用於2022年1月6日之後布建的環境。
* 可與Assets Essentials搭配使用的新版Creative Cloud外掛程式可在Exchange上取得 —  [Adobe XD的Adobe資產連結v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [AdobePhotoshop的資產連結/InDesign/Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* 各種錯誤修正和產品增強功能，包括先前的已知問題（上傳後資料夾現在可在左側導覽樹狀結構中正確顯示）<!-- CQ-4337638 -->，拖放上傳可讓使用者在拖放以上傳時選取目前資料夾或任何子資料夾<!-- CQ-4327753 -->)。

若要深入了解解決方案，請參閱 [簡介 [!DNL Assets Essentials]](introduction.md). 若要開始使用功能，請參閱 [快速入門](/help/get-started.md).

## 已知問題 {#known-issues}

已知問題清單 [!DNL Assets Essentials] 對產品進行持續修訂和更新：

* 無法將個別資產上傳至頂端資料夾（資產），只能上傳至系統中的任何子資料夾。 <!-- CQ-4337638 -->

如果您遇到任何問題，甚至是增強功能要求， [提供意見回饋](#provide-feedback) 敬隊裡。

## 舊版 {#past-release}

### 2021.8.0版 {#august2021}

[!DNL Assets Essentials] 2021.8.0已於2021年8月30日發行，並提供下列更新：

* 與 [!DNL Adobe Workfront] 讓 [!DNL Workfront] 使用者在管理其工作的情境下管理其數位資產。 如需詳細資訊，請參閱 [與其他Adobe解決方案的整合](/help/integration.md).

### 2021.7.0版 {#july2021}

[!DNL Assets Essentials] 2021.7.0已於2021年7月29日發行，並提供下列更新：

* 您可以建立並管理自訂的中繼資料表單，以在的資產詳細資料畫面中，將中繼資料屬性顯示給使用者 [!UICONTROL Metadata Forms] 選項 [!DNL Settings]. 請參閱 [中繼表單](metadata.md#metadata-forms).
* 各種錯誤修正和產品改良，包括上傳含有許多子檔案夾的巢狀資料夾時，提供更佳的效能。

### 2021.6.0版 {#june2021}

的第一個版本 [!DNL Assets Essentials]，於2021年6月21日推出，提供輕量型資產管理功能。 它支援下列主要功能和CRUD（建立、讀取、更新和刪除）操作：

* 上傳和新增資產，包括巢狀資料夾。 預覽資產和版本。
* 全文搜尋、細緻的搜尋篩選，以及儲存的搜尋，以快速探索資產。
* 基本資產管理操作，例如更新、刪除、下載和管理元資料。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 使用者在建立訊息時管理資產。 如需詳細資訊，請參閱 [與其他Adobe解決方案的整合](/help/integration.md).
