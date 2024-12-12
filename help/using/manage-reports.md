---
title: 在 Assets Essentials 管理報告
description: 存取 Assets Essentials 報告部分的資料，評估產品和功能使用情況，並得出關鍵成功指標的見解。
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 810bb62cd5eb664e36a6ea267050dd025828e900
workflow-type: ht
source-wordcount: '1226'
ht-degree: 100%

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

## 建立報告 {#create-report}

AEM Assets Essentials 環境會透過「報告」儀表板來提供全面的報告功能。此功能可讓使用者產生和下載 CSV 報告，其中會詳細說明指定時間內的資產上傳和下載情況，時間範圍從一次性到每日、每週、每月或每年。

**若要建立報告：**

1. 導覽至「**報告**」，並按一下「**建立報告**」(從右上角)。「**建立報告**」對話框會顯示以下欄位：
   ![建立報告](/help/using/assets/executed-reports1.svg)

   **在「設定」標籤中：**

   1. **報告類型：**&#x200B;選取「[!UICONTROL 上傳]」或「[!UICONTROL 下載]」報告類型。
   1. **標題：**&#x200B;為報告新增標題。
   1. **說明：**&#x200B;為報告新增選擇性說明。
   1. **選取資料夾路徑：**&#x200B;選取資料夾路徑，以產生該特定資料夾中已上傳和下載資產的報告。例如，如果您需要上傳到某個資料夾的資產報告，請指定該資料夾的路徑。
   1. **選取日期間隔：**&#x200B;選取日期範圍，以檢視資料夾內的上傳或下載活動。
   <br>

   >[!NOTE]
   >
   > Assets Essentials 會將所有本地時區轉換為世界協調時間 (UTC)。

   **在「欄」標籤中：**&#x200B;選取要在報告中顯示的欄名稱。下表說明了所有欄的用途：

   <table>
    <tbody>
     <tr>
      <th><strong>欄名稱</strong></th>
      <th><strong>說明</strong></th>
      <th><strong>報告類型</strong></th>
     </tr>
     <tr>
      <td>標題</td>
      <td>輸入資產的標題。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>路徑</td>
      <td>資產在 Assets Essentials 可用的資料夾路徑。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>MIME 類型</td>
      <td>資產的 MIME 類型。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>大小</td>
      <td>資產的大小 (以位元組為單位)。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>下載者</td>
      <td>下載資產的使用者的電子郵件 ID。</td>
      <td>下載</td>
     </tr>
     <tr>
      <td>下載日期</td>
      <td>執行資產下載動作的日期。</td>
      <td>下載</td>
     </tr>
     <tr>
      <td>作者</td>
      <td>資產的作者。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>建立日期</td>
      <td>資產上載到 Assets Essentials 的日期。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>修改日期</td>
      <td>上次修改資產的日期。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>已到期</td>
      <td>資產的到期狀態。</td>
      <td>下載和上傳</td>
     </tr>
     <tr>
      <td>按使用者名稱下載</td>
      <td>下載資產的使用者的名稱。</td>
      <td>下載</td>
     </tr>              
    </tbody>
   </table>



## 檢視及下載現有報告 {#View-and-download-existing-report}

現有報告會顯示在「**已執行的報告**」標籤下方。按一下「**報告**」，並選取「**已執行的報告**」，即可檢視狀態為「**已完成**」(表示已可供下載) 的所有已建立的報告。若要下載 CSV 格式的報告或刪除報告，請選取報告列並選取&#x200B;**下載 CSV** 或 **刪除**。![檢視及下載現有報告](/help/using/assets/view-download-existing-report.png)

## 安排報告 {#schedule-report}

在 AEM Essentials UI 中，「**安排報告**」會設定在指定的未來時間間隔 (例如每日、每週、每月或每年) 自動產生報告。此功能可協助簡化定期報告的需求並確保及時更新資料，而「**建立報告**」則是產生過去日期的報告。已完成的報告會列在「**已執行的報告**」下方，即將執行的報告則可在「**排程報告**」下方找到。

若要安排報告，請依照下列步驟操作：

1. 按一下左側窗格中的「報告」，然後按一下「建立報告」(從右上角)。
1. 「報告」對話框會顯示以下資訊：
   1. **報告類型：**&#x200B;在上傳和下載類型之間進行選擇。
   1. **標題：**&#x200B;為報告新增標題。
   1. **說明：**&#x200B;為報告新增選擇性說明。
   1. **選取資料夾路徑：**&#x200B;選取資料夾路徑，為將來要上傳到該特定資料夾或從其中下載的資產產生報告。
   1. 切換「**安排報告**」開關：切換此開關以安排稍後或重複發生的報告。
      ![安排報告](/help/using/assets/schedule-reports1.svg)

   1. **選擇頻率：**&#x200B;指定產生報告的時間間隔 (例如，每日、每週、每月、每年或一次)，並設定執行報告的日期和時間以及重複的結束日期。對於一次性報告，請選取 AEM 環境中選定活動類型的報告的日期範圍。例如，如果您需要特定月份的 10 至 29 日 (未來日期) 的已下載資產的報告，請在「**選取日期間隔**」欄位中選取這些日期。

   >[!NOTE]
   >
   > Assets Essentials 會將所有本地時區轉換為世界協調時間 (UTC)。

## 檢視排程報告 {#view-scheduled-reports}

排程報告會以系統化組織的方式顯示在「**排程報告**」標籤下方。每個排程報告的所有已完成報告都會儲存在單一報告資料夾中。按一下 ![展開收合項目](/help/using/assets/expand-icon1.svg) 以檢視已完成的報告。例如，如果您安排了一個每日報告，則所有已完成的報告都會群組到一個資料夾中。這種組織方式簡化了報告的導覽和易尋性。若要檢視排程報告，請按一下「**報告**」，然後按一下「**排程報告**」。所有排程報告便會顯示，並包含如「進行中」或「已完成」狀態。已完成的報告已可供進行下載。
![排程報告](/help/using/assets/scheduled-reports-tab.png)

## 編輯及取消排程報告 {#edit-cancel-scheduled-reports}

1. 導覽至「**排程報告**」標籤。
1. 選取該報告列。
1. 按一下「**編輯**」。
1. 按一下「**取消排程**」，然後按一下「**確認**」，以取消該排程報告。對於已取消的報告，下次執行時間會變為空白，而狀態則會顯示為已取消。
   ![編輯及取消排程報告](/help/using/assets/cancel-edit-scheduled-reports.png)

### 恢復排程 {#resume-schedule}

若要恢復已取消的排程，請選取該報告列，然後按一下「**恢復排程**」。恢復後，下次執行時間項目會再次顯示，而狀態則會顯示為進行中。
![恢復排程](/help/using/assets/resume-schedule.png)

>[!NOTE]
>
> 如果您在排程結束日期之前恢復已取消的報告，則會自動產生從取消日期到恢復日期的報告。

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

* **依大小劃分的資產計數：**將 Assets Essentials 環境中的總資產計數劃分為不同的大小範圍，醒目標示每個大小範圍內的資產數量和百分比，以環狀圖表示。
  ![依大小劃分的資產計數深入分析](/help/using/assets/insights-assets-count-by-size.svg)

* **依資產類型劃分的資產計數：**將 Assets Essentials 環境中的總資產計數進行區段劃分，根據檔案類型醒目標示資產數量和百分比，以環狀圖表示。
  ![依大小劃分的資產計數深入分析](/help/using/assets/insights-assest-count-by-asset-type1.svg)

