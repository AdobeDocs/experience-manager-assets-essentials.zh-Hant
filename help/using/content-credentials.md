---
title: content credentials整合
description: 整合至AEM Assets並在AEM Assets Essentials UI中精選的Content credentials，可提供資產歷史記錄的內容，包括資產的製作方式以及誰參與建立資產。 就像數位內容的營養標籤一樣，Content credentials可以協助提高透明度，並建立與受眾之間的信任。
role: User
source-git-commit: bb7a86c737f862411e2f06997d8b4d720d55a3c5
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 0%

---


# 內容憑證 {#content-credentials}

各大品牌對於內容透明度、AI揭露以及防止資產竄改的關注度前所未有。 Adobe的Content Authenticity Initiative (CAI)建立符合[內容來源與真偽聯盟](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA)技術標準的工具。 content credentials是一種新型加密的、可顯示篡改的中繼資料，可協助檢視者瞭解內容的譜系並確保品牌資產的完整性。 這類變數可包含範圍廣泛的來源資料，提供數位資產歷史記錄的深入分析。

此資訊包括：

* **簽發者或簽署者：**&#x200B;發行數位簽章以驗證或簽署資產的實體或公司的相關資訊。
* **問題日期：**&#x200B;將內容認證套用至資產的日期。
* **評分和使用狀況：**&#x200B;資產製作者的相關資訊，包括名稱、社群媒體控制代碼或其他身分相關資訊。
* **處理序：**&#x200B;對資產進行任何編輯或修改的記錄。
* **裝置詳細資料：**&#x200B;用來建立或編輯資產的應用程式或裝置相關資訊。
* **使用的AI工具：**&#x200B;如果使用generative AI編輯或建立資產，則可能會包含使用的模型名稱。
* **其他相關資訊：**&#x200B;可能也會包含其他資料，以協助提供有關資產歷史記錄的更多內容。

如需完整檢視，[驗證](https://contentcredentials.org/verify)可提供更完整的資產歷史記錄分析。

Adobe Experience Manager Assets現在可支援Content credentials，讓使用者直接在AEM的Assets EssentialsUI中檢視Content credentials。 檢視資產詳細資訊時，任何含有Content credentials的影像（例如使用GenAI服務建立的影像）都會在專用面板中顯示資訊清單詳細資訊。 如果資產已下載、發佈或共用，憑證與資產會維持不變。

![資產](/help/using/assets/content-credentials.png)

## 存取Content credentials {#access-content-credentials}

1. 前往Assets Essentials UI，然後從左窗格按一下&#x200B;**Assets**。
1. 導覽至資料夾，然後選取所需的資產。
1. 按一下&#x200B;**詳細資料**，然後從最右邊的窗格中選取`Cr pin`。 content credentials標籤會顯示資產的下列資訊。
   1. **產生的影像：**&#x200B;套用Content credentials的日期和時間。
   1. **內容摘要：**指出資產是部分或完全由AI產生，或是如何編輯。
      ![內容摘要](/help/using/assets/content-credentials1.png)
   1. **處理序：**詳細說明用來產生資產的應用程式、裝置和AI工具(例如Adobe Firefly)，以及之後進行的變更。
      ![處理程式](/help/using/assets/CR-Process.png)
   1. **關於此Content credentials：**發行者的名稱以及發行的日期和時間。
      ![簽發者](/help/using/assets/CR-issuer.png)