---
title: 管理您的數位資產
description: 在 [!DNL Assets Essentials]中移動、刪除、複製、重新命名、更新和版本您的資產。
role: User,Leader
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '604'
ht-degree: 0%

---


# 管理資產 {#manage-assets}

您可以使用[!DNL Assets Essentials]的好記介面，輕鬆執行各種數位資產管理(DAM)工作。 新增資產後，您可以搜尋、下載、移動、複製、重新命名、刪除、更新及編輯資產。

使用[!DNL Assets Essentials]完成下列資產管理任務。 選取資產時，頂端的工具列會顯示下列選項。

![選取資產時的工具列選項](assets/toolbar-image-selected.png)

*圖：工具列中所選影像的可用選項。*

* ![取消選](assets/do-not-localize/close-icon.png) 取圖示取消選取選取項目。
* ![詳細資](assets/do-not-localize/edit-in-icon.png) 訊圖示按一下以預覽資產並檢視詳細中繼資料。預覽時，您可以檢視版本並編輯影像。
* ![下載](assets/do-not-localize/download-icon.png) 圖示將選取的資產下載至本機檔案系統。
* ![刪除](assets/do-not-localize/delete-icon.png) 圖示刪除選取的資產或資料夾。
* ![結帳](assets/do-not-localize/checkout-icon.png) 圖示結帳選取的資產。
* ![複製](assets/do-not-localize/copy-icon.png) 表徵圖複製選定的檔案或資料夾。
* ![移動](assets/do-not-localize/move-icon.png) 圖示將選取的資產或資料夾移至存放庫階層中的不同位置。
* ![重新命](assets/do-not-localize/rename-icon.png) 名圖示重新命名選取的資產或資料夾。使用唯一名稱，否則重新命名會失敗並顯示警告。 您可以使用新名稱重試。
* ![指派任](assets/do-not-localize/review-delegate-icon.png) 務圖示指派任務給其他使用者以對資產共同作業。

您可以在「資產」縮圖上檢視相同的選項。

![資產縮圖上的選項以管理資產](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] 只會在工具列中顯示與所選資產類型相關的選項。

![選取資產時的工具列選項](assets/toolbar-folder-selected.png)

*圖：工具欄中所選資料夾的可用選項。*

![選取資產時的工具列選項](assets/toolbar-pdf-selected.png)

*圖：工具欄中所選PDF檔案的可用選項。*

## 下載和發佈資產 {#download}

您可以選取一或多個資產或資料夾，或兩者的組合，然後將選取的項目下載至本機檔案系統。 您可以編輯資產並再次上傳或在[!DNL Assets Essentials]外部分發資產。 您也可以[下載資產的轉譯](/help/add-delete.md#renditions)。

## 資產版本設定 {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] 會在資產再次上傳且經過更新或編輯時版本化資產。您可以檢視版本記錄、舊版，並可將資產的舊版還原為最新版本，視需要將其還原為舊版。 資產版本會在下列情況下建立：

* 上傳檔案名稱與現有資產相同且與現有資產位於相同資料夾的新資產。 [!DNL Assets Essentials] 系統會提示覆寫舊資產或將新資產儲存為版本。請參閱[上傳重複資產](/help/add-delete.md#resolve-upload-fails)。

   ![上傳時建立版本](assets/uploads-manage-duplicates.png)

   *圖：上傳與現有資產命名相同的資產時，您可以建立資產的版本。*

* 編輯影像，然後按一下&#x200B;**[!UICONTROL Save as Version]**。 請參閱[編輯影像](/help/edit-images.md)。

   ![將已編輯的影像儲存為版本](assets/edit-image2.png)

   *圖：將已編輯的影像儲存為版本。*

* 開啟現有資產的版本。 按一下&#x200B;**[!UICONTROL New Version]**，然後在存放庫中上傳資產的較新版本。

   ![從版本記錄上傳資產新版本的選項](assets/view-asset-versions2.png)

### 檢視資產版本 {#view-versions}

上傳重複副本或修改的資產副本時，您可以建立其版本。 版本設定可讓您檢閱歷史資產，並視需要回復至舊版。

若要檢視版本，請開啟資產的預覽，然後從右側邊欄按一下&#x200B;**[!UICONTROL Versions]** ![版本圖示](assets/do-not-localize/versions-clock-icon.png)。 若要預覽特定版本，請選取它。 要還原，請按一下&#x200B;**[!UICONTROL Make Latest]**。

您也可以從版本時間軸建立版本。 選取最新版本，按一下&#x200B;**[!UICONTROL New Version]**，然後從本機檔案系統上傳資產的新副本。

![檢視資產版本](assets/view-asset-versions1.png)

*圖：檢視資產的版本、回復至舊版或上傳其他新版本。*
