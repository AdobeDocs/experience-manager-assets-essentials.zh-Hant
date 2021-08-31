---
title: 發行說明
description: ' [!DNL Assets Essentials]的發行說明和已知問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 1%

---


# [!DNL Assets Essentials]的發行說明 {#release-notes}

目前的[!DNL Assets Essentials]版本將於2021年8月30日發行。 它提供與[!DNL Adobe Workfront]的整合，讓[!DNL Workfront]使用者在管理其工作的情境下管理其數位資產。 請參閱[與其他Adobe解決方案的整合](/help/integration.md)。

若要深入了解解決方案，請參閱[ [!DNL Assets Essentials]](introduction.md)簡介。 若要開始使用功能，請參閱[get started](/help/get-started.md)。

## 已知問題 {#known-issues}

[!DNL Assets Essentials]產品的已知問題清單不斷修訂和更新：

* 若要上傳資料夾或資產，將項目拖曳至存放庫中具有子資料夾的資料夾時，上傳會自動進入其中一個子資料夾。 因應措施是按一下[!DNL Upload assets]選項，然後拖曳至對話方塊中。<!-- CQ-4327753 -->
* 上傳資料夾後，新資料夾有時會在左側邊欄中顯示錯誤，而非顯示在樹狀檢視中。 因應措施是重新整理瀏覽器。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

如果您遇到任何問題或甚至是增強功能要求，請[向團隊提供意見](#provide-feedback)。

## 舊版 {#past-release}

### 2021.7.0版 {#july2021}

[!DNL Assets Essentials] 2021.7.0已於2021年7月29日發行，並提供下列更新：

* 您可以在[!DNL Settings]下的[!UICONTROL Metadata Forms]選項中，建立和管理用於向用戶顯示元資料屬性的自定義元資料表單。 請參閱[中繼資料表單](metadata.md#metadata-forms)。
* 各種錯誤修正和產品改良，包括上傳含有許多子檔案夾的巢狀資料夾時，提供更佳的效能。

### 2021.6.0版 {#june2021}

2021年6月21日推出的[!DNL Assets Essentials]第一版提供輕量型資產管理功能。 它支援下列主要功能和CRUD（建立、讀取、更新和刪除）操作：

* 上傳和新增資產，包括巢狀資料夾。 預覽資產和版本。
* 全文搜尋、細緻的搜尋篩選，以及儲存的搜尋，以快速探索資產。
* 基本資產管理操作，例如更新、刪除、下載和管理元資料。
* [!DNL Assets Essentials] 可供使 [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html)用。
