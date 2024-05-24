---
title: 在 Assets Essentials 管理報告
description: 存取 Assets Essentials 報告部分的資料，評估產品和功能使用情況，並得出關鍵成功指標的見解。
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: eede4280258595b7c74061786a8c173afaeee058
workflow-type: tm+mt
source-wordcount: '930'
ht-degree: 92%

---

# 管理報告 {#manage-reports}

資產報告使管理員能夠查看 Adobe Experience Manager Assets Essentials 環境的活動。此資料提供有關使用者如何與內容和產品互動的有用資訊。所有使用者可以存取「深入分析」儀表板，且獲指派至管理員產品設定檔的使用者可以建立使用者定義的報告。

## 存取報告 {#access-reports}

指派至 [Assets Essentials 管理員產品設定檔](deploy-administer.md)的所有使用者可以在 Assets Essentials 中存取「深入分析」儀表板或建立使用者定義的報告。

若要存取報告，請導覽至「**[!UICONTROL 設定]**」下的「**[!UICONTROL 報告]**」。

![報告](assets/reports.png)
<!--
In the **[!UICONTROL Reports]** screen, various components are shown in the tabular format which includes the following:

* **Title**: Title of the report
* **Type**: Determines whether the report is uploaded or downloaded to the repository
* **Description**: Provide details of the report that was given during uploading/downloading the report
* **Status**: Determines whether the report is completed, under progress, or deleted.
* **Author**: Provides email of the author who has uploaded/downloaded the report.
* **Created**: Gives information of the date when the report was generated.
-->

## 檢視深入分析 {#view-live-statistics}

>[!CONTEXTUALHELP]
>id="assets_reports"
>title="報告"
>abstract="「深入分析」儀表板可讓您檢視過去 30 天或過去 12 個月內 Experience Manager Assets 環境的即時事件量度。事件清單包括下載次數、上傳次數、熱門搜尋次數等。"

Assets Essentials 使您能夠使用「深入分析」儀表板查看 Assets Essentials 環境的即時資料。您可以查看過去 30 天或過去 12 個月的即時事件度量。

<!--![Toolbar options when you select an asset](assets/assets-essentials-live-statistics.png)-->

按一下左側導覽窗格中可用的「**[!UICONTROL 深入分析]**」以檢視以下自動產生的圖表：

* **下載**：使用折線圖表示過去 30 天或 12 個月內從 Assets Essentials 環境下載的資產數量。
  ![下載](/help/using/assets/insights-downloads2341.svg)

* **上傳**：使用折線圖表示過去 30 天或 12 個月內上傳到 Assets Essentials 環境的資產數量。
  ![上傳](/help/using/assets/insights-uplods2.svg)

<!--* **Asset Count by Size**: The division of count of assets based on their range of various sizes from 0 MB to 100 GB.-->

* **儲存空間使用量**：使用長條圖表示的 Assets Essentials 環境儲存空間使用量 (以位元組為單位)。
  ![儲存空間使用量](/help/using/assets/insights-storage-usage1.svg)
  <!--* **Delivery**: The graph depicts the count of assets as the delivery dates.-->

<!--* **Asset Count by Asset Type**: Represents count of various MIME types of the available assets. For example, application/zip, image/png, video/mp4, application/postscripte.-->

* **熱門搜尋**：以表格格式檢視過去 30 天或 12 個月內，在 Assets Essentials 環境中熱門搜尋詞彙以及這些詞彙的搜尋次數。
  ![儲存空間使用量](/help/using/assets/insights-top-search.svg)

  <!--
   ![Insights](assets/insights1.png)
   ![Insights](assets/insights2.png)
   -->

* **資產計數（依大小）：** 對您Assets Essentials環境中的資產總數進行區段，根據資產的檔案型別突出顯示資產的計數和百分比，以環形圖表示。
  ![insights-assets-count-by-size](/help/using/assets/insights-assets-count-by-size.svg)
* **依資產型別的資產計數：** 將您Assets Essentials環境中的資產總數細分為不同大小範圍，以各個大小範圍中的資產計數和百分比強調顯示，並使用環形圖表示。
  ![insights-assets-count-by-size](/help/using/assets/insights-assest-count-by-asset-type1.svg)

## 建立下載報告 {#create-download-report}

若要建立下載報告：

1. 瀏覽到 **[!UICONTROL 設定]** > **[!UICONTROL 報告]** 按一下 **[!UICONTROL 建立報告]**。

1. 在[!UICONTROL 配置]頁籤，將報表類型指定為&#x200B;**[!UICONTROL 下載]**。

1. 指定報告的標題和說明 (選用)。

1. 使用 **[!UICONTROL 選取資料夾路徑]** 的子選單。

1. 選取報告的日期間隔。

   >[!NOTE]
   >
   > Assets Essentials 會將所有本地時區轉換為世界協調時間 (UTC)。

1. 在 [!UICONTROL 列] 頁籤，選取需要在報告中顯示的列名。

1. 按一下&#x200B;**[!UICONTROL 建立]**。

   ![下載報告](assets/download-reports-config.png)

下表說明了可添加到報告的所有列的使用：

<table>
    <tbody>
     <tr>
      <th><strong>資料行名稱</strong></th>
      <th><strong>說明</strong></th>
     </tr>
     <tr>
      <td>標題</td>
      <td>輸入資產的標題。</td>
     </tr>
     <tr>
      <td>路徑</td>
      <td>資產在 Assets Essentials 可用的資料夾路徑。</td>
     </tr>
     <tr>
      <td>MIME 類型</td>
      <td>資產的 MIME 類型。</td>
     </tr>
     <tr>
      <td>大小</td>
      <td>資產位元組的大小。</td>
     </tr>
     <tr>
      <td>下載者</td>
      <td>下載資產的使用者的電子郵件ID。</td>
     </tr>
     <tr>
      <td>下載日期</td>
      <td>執行資產下載動作的日期。</td>
     </tr>
     <tr>
      <td>作者</td>
      <td>資產的作者。</td>
     </tr>
     <tr>
      <td>建立日期</td>
      <td>資產上載到 Assets Essentials 的日期。</td>
     </tr>
     <tr>
      <td>修改日期</td>
      <td>上次修改資產的日期。</td>
     </tr>
     <tr>
      <td>過期</td>
      <td>資產的到期狀態。</td>
     </tr>
     <tr>
      <td>按使用者名稱下載</td>
      <td>下載資產的使用者的名稱。</td>
     </tr>           
    </tbody>
   </table>

## 建立上傳報告 {#create-upload-report}

若要建立上傳報告：

1. 瀏覽到 **[!UICONTROL 設定]** > **[!UICONTROL 報告]** 按一下 **[!UICONTROL 建立報告]**。

1. 在[!UICONTROL 配置]頁籤，將報表類型指定為&#x200B;**[!UICONTROL 上傳]**。

1. 指定報告的標題和說明 (選用)。

1. 使用 **[!UICONTROL 選取資料夾路徑]** 的子選單。

1. 選取報告的日期間隔。

1. 在 [!UICONTROL 列] 頁籤，選取需要在報告中顯示的列名。

1. 按一下&#x200B;**[!UICONTROL 建立]**。

   ![上傳報告](assets/upload-reports-config.png)

下表說明了可添加到報告的所有列的使用：

<table>
    <tbody>
     <tr>
      <th><strong>資料行名稱</strong></th>
      <th><strong>說明</strong></th>
     </tr>
     <tr>
      <td>標題</td>
      <td>輸入資產的標題。</td>
     </tr>
     <tr>
      <td>路徑</td>
      <td>資產在 Assets Essentials 可用的資料夾路徑。</td>
     </tr>
     <tr>
      <td>MIME 類型</td>
      <td>資產的 MIME 類型。</td>
     </tr>
     <tr>
      <td>大小</td>
      <td>資產的大小。</td>
     </tr>
     <tr>
      <td>作者</td>
      <td>資產的作者。</td>
     </tr>
     <tr>
      <td>建立日期</td>
      <td>資產上載到 Assets Essentials 的日期。</td>
     </tr>
     <tr>
      <td>修改日期</td>
      <td>上次修改資產的日期。</td>
     </tr>
     <tr>
      <td>過期</td>
      <td>資產的到期狀態。</td>
     </tr>              
    </tbody>
   </table>

## 查看現有報告 {#view-report-list}

[建立報告](#create-download-report)之後，您可以查看現有報告的清單並選取以 CSV 格式下載或刪除它們。

要查看報告清單，請瀏覽至 **[!UICONTROL 設定]** > **[!UICONTROL 報告]**。

對於每個報告，您都可以查看報告標題、報告類型、建立報告時指定的說明、報告狀態、建立報告的作者的電子郵件識別碼以及報告建立日期。

`Completed ` 報告的狀態表示報告已準備好下載。

![報告清單](assets/list-of-reports.png)


## 下載 CSV 報告 {#download-csv-report}

要以 CSV 格式下載的報告：

1. 瀏覽到 **[!UICONTROL 設定]** > **[!UICONTROL 報告]**。

1. 選取報告並按一下 **[!UICONTROL 下載 CSV]**。

所選報告以 CSV 格式下載。CSV 報告中顯示的列取決於您在選取[建立報告](#create-download-report)時選取的資料行。

## 刪除報告 {#delete-report}

若要刪除報告：

1. 瀏覽到 **[!UICONTROL 設定]** > **[!UICONTROL 報告]**。

1. 選取報告並按一下 **[!UICONTROL 刪除]**。

1. 再按一次「**[!UICONTROL 刪除]**」以進行確認。
