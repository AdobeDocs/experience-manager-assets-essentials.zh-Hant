---
title: 支援的檔案格式
description: 支援的各種檔案格式 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 14%

---

# 檔案格式支援 [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] 支援多種檔案格式，每種功能都支援不同的檔案類型。

* ![影像檔案類型表徵圖](assets/image-icon.svg) 影像：JPG、PNG、GIF、TIFF和其他
* ![creative cloudtype表徵圖](assets/creative-cloud-files.svg) Creative Cloud檔案：PSD、人工智慧和INDD
* ![相機類型表徵圖](assets/camera-icon.svg) Camera Raw檔案：CR2/CR3、NEF、SRW/SRF等
* ![文檔檔案類型表徵圖](assets/document-icon.svg) 文檔：DOCX、PDF、PPTX和XLSX
* ![視頻檔案類型表徵圖](assets/video-icon.svg) 視頻：MP4

[!DNL Assets Essentials] 支援任何具有基本服務的二進位檔案格式，如儲存、上載、複製、移動、刪除和添加元資料。

[!DNL Assets Essentials] 還支援來自眾多領先照相機製造商的照相機RAW檔案，這些製造商包括佳能(CR2/CR3)、尼康(NEF)、索尼(SRW/SRF)、富士(RAF)、奧林匹斯(ORF)，以及由Adobe Camera Raw提供動力的其他公司。

各種檔案類型對使用案例和功能的支援程度不同，如下所述。 使用圖例瞭解支援級別。

| 支援級別 | 說明 |
|-------------------|-------------------------|
| ✓ | 支援 |
| ✓? | 有條件支援 |
| - | 不適用 |

## 添加、上載和查看資產 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 資產類型 | [瀏覽](/help/navigate-view.md) | 複製 | [上傳](/help/add-delete.md) | 建立 | [刪除](/help/add-delete.md#delete-assets) | 詳細資料 | 影像縮放 | [最近檢視的項目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 光柵影像 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 原始檔案 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4視頻 | ✓ | ✓ | ✓ | - | ✓ | ✓? | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD、人工智慧和INDD | ✓ | ✓ | ✓ | - | ✓ | ✓? | - | ✓ |
| 其他二進位檔案 | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 搜索、使用和編輯資產 {#support-to-search-use-edit}

| 資產類型 | [下載](/help/manage-organize.md#download) | 拖放 | [影像編輯器](/help/edit-images.md) | [搜尋](/help/search.md) | [智慧標記](/help/metadata.md#tags) | [重新命名](/help/manage-organize.md) | [版本](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 光柵影像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| 原始檔案 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| 視訊 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC庫 | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD、人工智慧和INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 其他二進位檔案 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## 審查資產和協作 {#support-to-review-collaborate}

| 資產類型 | 注釋 | 評論 | 建立任務和審閱 |
|---------------|----------|----------|-------------------------|
| 光柵影像 | ✓ | ✓ | ✓ |
| 原始檔案 | ✓ | ✓ | ✓ |
| 資料夾 | - | - | - |
| 視訊 | - | ✓ | ✓ |
| CC庫 | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD、人工智慧和INDD | - | ✓ | ✓ |
| 其他二進位檔案 | - | ✓ | ✓ |

## 其他資產管理任務 {#support-to-manage-assets}

| 資產類型 | [中繼資料](/help/metadata.md) | [轉譯](/help/add-delete.md#renditions) | [垃圾桶](/help/add-delete.md#delete-assets) | 複製 | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| 光柵影像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 原始檔案 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | - | ✓ | ✓ | ✓ |
| 視訊 | ✓ | - | ✓ | ✓ | ✓ |
| CC庫 | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD、人工智慧和INDD | ✓ | - | ✓ | ✓ | ✓ |
| 其他二進位檔案 | ✓ | - | ✓ | ✓ | ✓ |

用戶 [!DNL Adobe Asset Link] 可以將檔案上載並簽入（上載新版本） [!DNL Assets Essentials] 支援的儲存庫 [!DNL Adobe Creative Cloud] 案頭應用程式。

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
