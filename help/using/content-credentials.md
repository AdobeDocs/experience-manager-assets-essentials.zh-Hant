---
title: Content Credentials 整合
description: Content Credentials 已整合至 AEM Assets 並呈現在 AEM Assets Essentials UI 中，可提供關於資產歷史的背景資訊，包括資產的製作方式以及誰參與建立。 如同數位內容的營養成分標籤一樣，Content Credentials 可以協助提高透明度並建立客群的信任感。
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 100%

---

# Content Credentials {#content-credentials}

各大品牌均比從前更加關注內容透明度、AI 揭露，以及防止資產被篡改等情況。 Adobe 的 Content Authenticity Initiative (CAI) 可建置符合[內容來源與真實性聯盟](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA) 技術標準的工具。 Content Credentials 是一種加密式、防篡改的新型後設資料，可協助檢視者了解內容的譜系，並確保品牌資產的完整性。 其中可能包含廣泛的溯源資料，提供關於數位資產歷史記錄的洞察。

這些資訊包括：

* **簽發者或簽署者：**&#x200B;發行數位簽名以供驗證或簽署資產使用的實體或公司之相關資訊。
* **簽發日期：** Content Credential 套用至資產的日期。
* **製作者和使用情形：**&#x200B;資產製作者的相關資訊，包括名稱、社交媒體帳號或其他身分相關資訊。
* **處理：**&#x200B;編輯或修改資產的任何記錄。
* **裝置詳細資料：**&#x200B;用於建立或編輯資產之應用程式或裝置的相關資訊。
* **使用的 AI 工具：**&#x200B;如果使用生成式 AI 編輯或建立資產，則可能會包含所使用的模型名稱。
* **其他相關資訊：**&#x200B;也可能會包含其他資料，以便提供關於資產歷史的更多背景資訊。

若要檢視完整的資料，「[驗證](https://contentcredentials.org/verify)」可以提供更完整的資產歷史洞察。

Adobe Experience Manager Assets 現在支援 Content Credentials，使用者可以直接於 AEM 的 Assets Essentials UI 中檢視 Content Credentials。 檢視資產詳細資料時，任何包含 Content Credentials 的影像 (例如使用生成式 AI 服務建立的影像) 都會在專用面板中顯示資訊清單的詳細資料。 如果有人下載、發佈或共用資產，資產的認證內容維持不變。

![資產](/help/using/assets/content-credentials.png)

## 存取 Content Credentials {#access-content-credentials}

1. 前往 Assets Essentials UI，然後於左側窗格按一下「**Assets**」。
1. 導覽至資料夾，然後選取所需的資產。
1. 按一下「**詳細資料**」，然後在最右邊的窗格中選取「`Cr pin`」。 Content Credentials 標籤會顯示下列資產資訊。
   1. **產生的影像：**&#x200B;套用 Content Credentials 的日期和時間。
   1. **內容摘要：**指出資產是否部分或完全由 AI 產生，或者其編輯歷程。
      ![內容摘要](/help/using/assets/content-credentials1.png)
   1. **處理：**詳細說明用於產生資產的應用程式、裝置和 AI 工具 (例如 Adobe Firefly)，以及後續進行的變更。
      ![處理](/help/using/assets/CR-Process.png)
   1. **Content Credentials 相關資訊：**簽發者的名稱以及簽發日期和時間。
      ![簽發者](/help/using/assets/CR-issuer.png)
