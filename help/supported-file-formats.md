---
title: 支援的檔案格式
description: ' [!DNL Assets Essentials] 各種使用案例支援的檔案格式'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: ht
source-wordcount: '308'
ht-degree: 100%

---

# [!DNL Assets Essentials] 的檔案格式支援 {#file-format-support}

[!DNL Assets Essentials] 支援各式各樣的檔案格式，而且每種功能對於不同的檔案類型都有不同的支援。

* ![影像檔案類型圖示](assets/image-icon.svg) 影像：JPG、PNG、GIF、TIFF 和其他
* ![creative cloudtype 圖示](assets/creative-cloud-files.svg) Creative Cloud 檔案：PSD、AI 和 INDD
* ![相機類型圖示](assets/camera-icon.svg) Camera RAW 檔案：CR2/CR3、NEF、SRW/SRF 和其他
* ![文字檔案類型圖示](assets/document-icon.svg) 文件：DOCX、PDF、PPTX 和 XLSX
* ![影片檔案類型圖示](assets/video-icon.svg) 影片：MP4

[!DNL Assets Essentials] 支援任何二進位檔案格式和基本服務，例如儲存、上傳、複製、移動、刪除和新增中繼資料。

[!DNL Assets Essentials] 也支援各式各樣領先相機製造商的 Camera RAW 檔案 (採用 Adobe Camera Raw 技術)，包括 Canon (CR2/CR3)、Nikon (NEF)、Sony (SRW/SRF)、Fujifilm (RAF)、Olympus (ORF) 和其他廠商。

各種檔案類型對於使用案例和功能有不同程度的支援，如下所述。請參閱圖例以了解支援程度。

| 支援程度 | 說明 |
|-------------------|-------------------------|
| ✓ | 支援 |
| ✓ ‡ | 有條件支援 |
| − | 不適用 |

## 新增、上傳和檢視資產 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 資產類型 | [瀏覽](/help/navigate-view.md) | 複製 | [上傳](/help/add-delete.md) | 建立 | [刪除](/help/add-delete.md#delete-assets) | 詳細資料 | 影像縮放 | [最近檢視的項目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 點陣圖 | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| RAW 檔案 | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4 影片 | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD、AI 和 INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| 其他二進位檔案 | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 搜尋、使用和編輯資產 {#support-to-search-use-edit}

| 資產類型 | [下載](/help/manage-organize.md#download) | 拖放 | [影像編輯器](/help/edit-images.md) | [搜尋](/help/search.md) | [智慧標記](/help/metadata.md#tags) | [重新命名](/help/manage-organize.md) | [版本](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 點陣圖 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 檔案 | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| 影片 | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC Libraries | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD、AI 和 INDD | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| 其他二進位檔案 | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## 檢閱資產和共同作業 {#support-to-review-collaborate}

| 資產類型 | 注釋 | 評論 | 建立任務和檢閱 |
|---------------|----------|----------|-------------------------|
| 點陣圖 | ✓ | ✓ | ✓ |
| RAW 檔案 | ✓ | ✓ | ✓ |
| 資料夾 | − | − | − |
| 影片 | − | ✓ | ✓ |
| CC Libraries | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD、AI 和 INDD | − | ✓ | ✓ |
| 其他二進位檔案 | − | ✓ | ✓ |

## 其他資產管理任務 {#support-to-manage-assets}

| 資產類型 | [中繼資料](/help/metadata.md) | [轉譯](/help/add-delete.md#renditions) | [垃圾桶](/help/add-delete.md#delete-assets) | 複製 | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| 點陣圖 | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 檔案 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 資料夾 | ✓ | − | ✓ | ✓ | ✓ |
| 影片 | ✓ | − | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| PSD、AI 和 INDD | ✓ | − | ✓ | ✓ | ✓ |
| 其他二進位檔案 | ✓ | − | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link] 的使用者可以從支援的 [!DNL Adobe Creative Cloud] 桌面應用程式上傳和簽入 (上傳新版本) 檔案到 [!DNL Assets Essentials] 存放庫。

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
