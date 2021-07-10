---
title: 支援的檔案格式
description: ' [!DNL Assets Essentials]各種使用案例支援的檔案格式'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 21%

---


# [!DNL Assets Essentials]中支援檔案格式 {#file-format-support}

[!DNL Assets Essentials] 支援多種檔案格式，而且每種功能對不同檔案類型的支援各不相同。

* ![影像檔案類](assets/do-not-localize/image-icon.png) 型圖示影像：GIF、JPG、PNG和TIFF
* ![文檔檔案類型](assets/do-not-localize/document-icon.png) 表徵圖文檔：DOCX、PDF、PPTX和XLSX
* ![視訊檔案類](assets/do-not-localize/video-icon.png) 型icon視訊：MP4

各種檔案類型對使用案例和功能的支援程度不同，如下所述。 使用圖例來了解支援層級。

| 支援層級 | 說明 |
|-------------------|-------------------------|
| ✓ | 支援 |
| ✓ | 有條件支援 |
| - | 不適用 |

## 新增、上傳和檢視資產 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 資產類型 | [瀏覽](/help/navigate-view.md) | 複製 | [上傳](/help/add-delete.md) | 建立 | [刪除](/help/add-delete.md#delete-assets) | 詳細資料 | 影像縮放 | [最近檢視的項目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 光柵影像 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4影片 | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD、AI和INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 搜尋、使用和編輯資產 {#support-to-search-use-edit}

| 資產類型 | [下載](/help/manage-organize.md#download) | 拖放 | [影像編輯器](/help/edit-images.md) | [搜尋](/help/search.md) | [智慧標記](/help/metadata.md#tags) | [重新命名](/help/manage-organize.md) | [版本](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 光柵影像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | - | ✓ | - | ✓ | - |
| 視訊 | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| CC Libraries | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## 審核資產和協作 {#support-to-review-collaborate}

| 資產類型 | 注釋 | 評論 | 建立任務和審閱 |
|---------------|----------|----------|-------------------------|
| 光柵影像 | ✓ | ✓ | ✓ |
| 資料夾 | - | - | - |
| 視訊 | - | ✓ | ✓ |
| CC Libraries | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## 其他資產管理任務 {#support-to-manage-assets}

| 資產類型 | [中繼資料](/help/metadata.md) | [轉譯](/help/add-delete.md#renditions) | [垃圾桶](/help/add-delete.md#delete-assets) | 複製 | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| 光柵影像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | - | ✓ | ✓ | ✓ |
| 視訊 | ✓ | - | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD | ✓ | - | ✓ | ✓ | ✓ |
| AI | ✓ | - | ✓ | ✓ | ✓ |
| INDD | ✓ | - | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link]的用戶可以從支援的[!DNL Adobe Creative Cloud]案頭應用程式將光柵影像簽入[!DNL Assets Essentials]儲存庫。

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
