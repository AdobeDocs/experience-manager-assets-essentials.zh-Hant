---
title: 將資產上載到儲存庫
description: 將資產上載到 [!DNL Assets Essentials]、查看上載狀態並解決上載問題。
role: User
exl-id: a85a4455-4456-48af-aee9-f05300677605
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '747'
ht-degree: 0%

---

# 上載資產 {#add-assets}

要添加新資產以使用，請從本地檔案系統上載一些資產。 <!-- TBD: Many of the [common file formats are supported](/help/supported-file-formats.md). -->

您可以使用以下方法上載一個或多個資產或包含資產的資料夾：

* 在用戶介面上拖動資產或資料夾，並按照螢幕上的說明進行操作。
* 按一下 **[!UICONTROL 添加資產]** 的子菜單。

<!-- TBD: Update this GIF
![Asset and nested folder upload demo](assets/do-not-localize/upload-assets.gif) -->

建立資料夾後，可以使用其中任何一種方法上載資產。 要建立空資料夾，請按一下 **[!UICONTROL 建立資料夾]** 的子菜單。 同時 [!DNL Assets Essentials] 提供了功能強大的全文搜索功能，您還可以使用資料夾更好地組織資產。

選擇檔案後，您將獲得一個確認對話框，以添加更多檔案或刪除已選定的檔案。 要向所選內容添加更多檔案，請按一下 **[!UICONTROL 瀏覽]** 的 **[!UICONTROL 瀏覽檔案]** 或 **[!UICONTROL 瀏覽資料夾]**。 從同一資料夾或另一個資料夾中添加更多檔案或資料夾。

所有檔案都排隊後，按一下 **[!UICONTROL 上載]**。

![上載檔案和資料夾](assets/upload-browse-files-folders.png)

*圖：在上載所選資產之前，您可以添加或從隊列中刪除資產。*

>[!CAUTION]
>
>使用檔案名中沒有空格的資產。 對評論的答復對這類資產不起作用。

## 查看上載進度和狀態 {#upload-progress}

將許多資產或嵌套資料夾上載到 [!DNL Assets Essentials]，某些資產可能因重複資產和網路問題等各種原因無法上載。

要跟蹤上載進度，請按一下 **[!UICONTROL 上載進度]** 的上界。 一個面板顯示所有資產的上載進度。

要查看基於上載進度或狀態的資產子集，請使用 **[!UICONTROL 上載進度]** 工具欄。 各種篩選器將顯示所有資產、已完成上載、正在進行上載、要上載的已排隊資產、暫停上載、重複資產和無法上載的資產。

![根據上載狀態篩選上載進度](assets/filter-upload-progress.png)

*圖：根據上載狀態或上載進度篩選您嘗試上載的資產。*

資產上傳後， [!DNL Assets Essentials] 處理資產以生成縮略圖並處理元資料。 對於許多資產，處理需要一些時間。 如果看不到縮略圖並在佔位符縮略圖上看到處理消息，請在幾分鐘後再次檢查資料夾。 在處理期間， [!DNL Assets Essentials] 生成格式副本、添加智慧標籤並為資產詳細資訊編製索引以進行搜索。

![資產是上載時的進程，磁貼顯示處理](assets/upload-processing.png)

*圖：已處理的磁貼上的資產顯示處理。*

## 資產格式副本 {#renditions}

[!DNL Assets Essentials] 幾乎即時地處理上載的資產，並且對於許多受支援的檔案類型，它會生成格式副本。 為影像建立格式副本後，將調整上載影像的大小。 您不僅可以下載資產，還可以下載格式副本以使用適當的版本。 您可以在您 [預覽資產](/help/navigate-view.md#preview-assets)。

![轉譯](assets/renditions-view-download.png)

*圖：查看並下載格式副本。*

## 管理失敗的上載 {#resolve-upload-fails}

如果受支援資產的上載由於某種原因失敗，請按一下 **[!UICONTROL 重試]** 從 [!UICONTROL 上載進度] 的子菜單。

![重試上載失敗](assets/upload-retry.png)

*圖：如果受支援的檔案由於某種原因無法上載，請重試。*

如果嘗試上載重複資產，則在明確確認上載之前不會上載這些資產。 首先，重複資產被標籤為失敗的上載。 要解決此問題，您只需建立版本、刪除和替換現有資產，或通過更名資產建立重複副本即可。 您可以一次解決一個資產或一次針對所有失敗的重複項批量執行此類故障。

![一次管理重複的資產](assets/uploads-manage-duplicates.png)

*圖：對於預設情況下無法上載的重複資產，請一次解決一個資產問題。*

![批量管理所有失敗的上載](assets/upload-progress-manage-failed-uploads.png)

*圖：對於預設情況下無法上載的重複資產，請立即解決所有資產的問題。*

>[!TIP]
>
>您可以直接從您的 [!DNL Creative Cloud] 案頭應用程式。 查看方式 [[!DNL Assets Essentials] 整合 [!DNL Adobe Asset Link]](/help/integration.md)。

## 刪除資產或資料夾 {#delete-assets}

用戶可以刪除不再需要的單個資產或資料夾。 要刪除資產或資料夾，請執行以下操作之一：

* 使用資產或資料夾的縮略圖上可用的選項。

   ![資產縮略圖選項以管理資產](assets/options-on-thumbnail.png)

   *圖：在資產或資料夾磁貼上可以執行檔案和資料夾操作。*

* 選擇資產或資料夾，然後按一下 **[!UICONTROL 刪除]** ![刪除表徵圖](assets/do-not-localize/delete-icon.png) 的子菜單。
