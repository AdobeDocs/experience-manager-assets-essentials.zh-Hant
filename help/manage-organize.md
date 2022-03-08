---
title: 管理您的數字資產
description: 在中移動、刪除、複製、更名、更新和版本 [!DNL Assets Essentials]。
role: User,Leader
contentOwner: AG
exl-id: b01e98b9-0cc2-47c5-9f5b-79b8e6bef39f
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 0%

---

# 管理資產 {#manage-assets}

您可以使用用戶友好的介面輕鬆執行各種數字資產管理(DAM)任務 [!DNL Assets Essentials]。 添加資產後，您可以搜索、下載、移動、複製、更名、刪除、更新和編輯資產。

使用 [!DNL Assets Essentials] 完成以下資產管理任務。 選擇資產時，頂部的工具欄中將顯示以下選項。

![選擇資產時的工具欄選項](assets/toolbar-image-selected.png)

*圖：所選影像的工具欄中可用的選項。*

* ![取消選擇表徵圖](assets/do-not-localize/close-icon.png) 取消選擇所選內容。
* ![詳細資訊表徵圖](assets/do-not-localize/edit-in-icon.png) 按一下以預覽資產並查看詳細元資料。 預覽時，可以查看版本並編輯影像。
* ![下載表徵圖](assets/do-not-localize/download-icon.png) 將所選資產下載到本地檔案系統。
* ![刪除表徵圖](assets/do-not-localize/delete-icon.png) 刪除所選資產或資料夾。
* ![簽出表徵圖](assets/do-not-localize/checkout-icon.png) 簽出所選資產。
* ![複製表徵圖](assets/do-not-localize/copy-icon.png) 複製所選檔案或資料夾。
* ![移動表徵圖](assets/do-not-localize/move-icon.png) 將所選資產或資料夾移動到儲存庫層次結構中的其他位置。
* ![更名表徵圖](assets/do-not-localize/rename-icon.png) 更名所選資產或資料夾。 使用唯一名稱，否則更名失敗並出現警告。 可以使用新名稱重試。
* ![分配任務表徵圖](assets/do-not-localize/review-delegate-icon.png) 將任務分配給其他用戶以對資產進行協作。

您可以在資產縮略圖上查看相同的選項。

![資產縮略圖選項以管理資產](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] 僅在工具欄中顯示取決於選定資產類型的相關選項。

![選擇資產時的工具欄選項](assets/toolbar-folder-selected.png)

*圖：所選資料夾的工具欄中可用的選項。*

![選擇資產時的工具欄選項](assets/toolbar-pdf-selected.png)

*圖：工具欄中可用於選定PDF檔案的選項。*

## 下載和分發資產 {#download}

您可以選擇一個或多個資產或資料夾或兩者的組合，然後將所選內容下載到本地檔案系統。 您可以編輯資產並再次上載或將資產分發到外部 [!DNL Assets Essentials]。 另外，你可以 [下載格式副本](/help/add-delete.md#renditions) 資產。

## 資產版本設定 {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] 版本在再次上載更新或編輯資產時的資產。 您可以查看版本歷史記錄、過去的版本，並且可以將資產的過去版本還原為最新版本，如果需要，該版本將還原為以前的版本。 資產版本在以下方案中建立：

* 上載與現有資產具有相同檔案名且與現有資產位於同一資料夾中的新資產。 [!DNL Assets Essentials] 提示您改寫以前的資產或將新資產另存為版本。 請參閱 [上載重複資產](/help/add-delete.md#resolve-upload-fails)。

   ![上載時建立版本](assets/uploads-manage-duplicates.png)

   *圖：上載與現有資產名稱相同的資產時，您可以建立資產版本。*

* 編輯影像，然後按一下 **[!UICONTROL 另存為版本]**。 請參閱 [編輯影像](/help/edit-images.md)。

   ![將編輯的影像另存為版本](assets/edit-image2.png)

   *圖：將編輯的影像另存為版本。*

* 開啟現有資產的版本。 按一下 **[!UICONTROL 新版本]** 並在儲存庫中上載資產的較新版本。

   ![從版本歷史記錄中上載資產的新版本的選項](assets/view-asset-versions2.png)

### 查看資產的版本 {#view-versions}

上載資產的重複副本或修改副本時，可以建立其版本。 版本控制允許您複查歷史資產，並在需要時恢復到以前的版本。

要查看版本，請開啟資產的預覽並按一下 **[!UICONTROL 版本]** ![版本表徵圖](assets/do-not-localize/versions-clock-icon.png) 右邊欄。 要預覽特定版本，請選擇它。 要還原到它，請按一下 **[!UICONTROL 最新]**。

也可以從版本時間軸建立版本。 選擇最新版本，按一下 **[!UICONTROL 新版本]**，並從本地檔案系統上載資產的新副本。

![查看資產的版本](assets/view-asset-versions1.png)

*圖：查看資產的版本、還原到以前的版本或上載其他新版本。*
