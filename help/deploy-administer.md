---
title: 部署和管理用戶
description: 管理使用案例，例如 [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: cbf75aaf05a0f3d798edf4d508325b28d9ca0dcb
workflow-type: tm+mt
source-wordcount: '1030'
ht-degree: 1%

---

# 部署 [!DNL Assets Essentials] 新增使用者 {#administer}

[!DNL Adobe Experience Manager Assets Essentials] 由Adobe為其客戶布建。 作為布建的一部分， [!DNL Assets Essentials] 新增至 [!DNL Adobe Admin Console]. 客戶也可以 [!DNL Experience Manager Cloud Manager] 作為部署工具，並 [!DNL Admin Console] 若要管理使用者權益 [!DNL Assets Essentials] 解決方案。

## 自動部署Assets Essentials {#automatic-deployment-assets-essentials}

布建Assets Essentials解決方案後，管理員會收到來自Adobe的電子郵件。 電子郵件包含歡迎訊息和要開始的連結。 此外，Adobe會啟動程式以自動部署Assets Essentials。 部署過程需要一小時才能完成。

從電子郵件中的連結，存取並登入 [Admin Console](https://adminconsole.adobe.com). 如果您有多個組織帳戶的管理員存取權，請選取適當的組織，或使用頂端列的切換器切換至該組織。 完成自動部署過程後， [!DNL AEM Assets Essentials] 會顯示在 [!DNL Admin Console].

![Assets Essentials部署](assets/assets-essentials-deployment.png)

成功部署Assets Essentials解決方案後，管理員需要執行下列工作：

* [管理使用者存取權](#add-users-to-essentials) 組織成員 [!DNL Assets Essentials].
* （可選） [查看服務狀態和日誌](#view-logs).

>[!NOTE]
>
>如果在2022年1月06日之前布建Assets Essentials，請執行 [在Cloud Manager中部署步驟](#deploy-essentials) 管理組織成員的用戶訪問權限之前。


## 使用者管理 {#add-users-to-essentials}

管理員負責管理哪些使用者有權存取 [!DNL Assets Essentials]. 管理員使用 [!DNL Adobe Admin Console] 添加或刪除用戶訪問權限。 [!DNL Assets Essentials] 有下列兩種可用的使用者存取。

* **[!DNL Assets Essentials]使用者** 可存取完整的使用者介面。 這些使用者可以上傳、組織、標籤及尋找數位資產。
* **[!DNL Assets Essentials]消費者使用者**:可存取中內嵌的資產選擇體驗 [!DNL Adobe Journey Optimizer] 電子郵件範本編輯器。 如需詳細資訊，請參閱 [使用 [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

在 [!DNL Admin Console]，這兩種存取類型由兩種 [!UICONTROL Product Profiles]. 若要將組織的成員新增及移除至這兩個設定檔中的任何一個，請遵循下列步驟：

1. 存取 [!DNL Admin Console] 按一下 **[!UICONTROL Products]** 在頂端列中，按一下 **[!UICONTROL AEM Assets Essentials]**，然後按一下 [!DNL Assets Essentials] 環境。 [!DNL Assets Essentials] 有兩個產品設定檔，代表一般和消費者使用者的存取權。

   ![兩種使用者的兩個設定檔](assets/adminconsole-user-types.png)

   *圖：有兩種設定檔可供新增兩種使用者。*

1. 若要新增使用者至群組，請按一下群組，然後選取 **[!UICONTROL Add User]**，提供使用者詳細資訊，然後按一下 **[!UICONTROL Save]**. 新增使用者時，使用者會收到開始使用的電子郵件邀請。 您可以在 [!DNL Admin Console].

   ![新增使用者至 [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *圖：新增使用者至 [!DNL Assets Essentials] 從 [!DNL Admin Console].*

1. 若要從群組中移除使用者，請按一下群組，選取現有使用者，然後選取 **[!UICONTROL Remove User]**.

>[!TIP]
>
>在 [!DNL Admin Console]，您可以使用CSV檔案大量管理使用者。 要了解更多資訊，請參閱 [[!DNL Admin Console] 檔案](https://helpx.adobe.com/enterprise/using/accounts.html).

## 查看服務狀態和訪問日誌 {#view-logs}

布建後，管理員將部署 [!DNL Assets Essentials] 一次。 初始部署後，Adobe會執行服務維護和更新。 管理員可使用 [!DNL Cloud Manager] 用於檢查服務狀態和下載最近訪問日誌的用戶介面。

1. 當使用者回報問題時，請檢查 [!DNL Assets Essentials] 在 **[!UICONTROL Program Overview]** 介面。 在解決方案的正常運作期間，狀態為 `Running`. 若 [!DNL Cloud Manager] 顯示任何其他狀態，在 [!DNL Admin Console] 支援區段。

   ![的狀態 [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *圖：的正常狀態 [!DNL Assets Essentials] in [!DNL Cloud Manager] is `Running`.*

1. 若要下載最近的存取記錄檔，請按一下 ![選項表徵圖](assets/do-not-localize/options-ellipses-icon.png)，選取 **[!UICONTROL Download Logs]**，並遵循螢幕上的指示。 您可以使用記錄檔稽核HTTPS存取請求。

   ![ 下載存取記錄檔的選項](assets/cloudmanager-download-logs.png)

   *圖：下載存取記錄檔的選項。*

## 部署 [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>只有在2022年1月06日之前布建Assets Essentials時，才執行這些步驟。

布建後， [!DNL Assets Essentials] 在 [!DNL Admin Console]. 組織管理員必須先部署解決方案，才能將其提供給使用者使用。 管理員使用 [!DNL Cloud Manager] 使用者介面。 初始部署後，Adobe會執行服務維護和更新。 布建解決方案後，管理員會收到來自Adobe的電子郵件。 電子郵件包含歡迎訊息和要開始的連結。 要部署，請執行以下步驟：

1. 從電子郵件中的連結，存取並登入 [Admin Console](https://adminconsole.adobe.com). 如果您有多個組織帳戶的管理員存取權，請選取適當的組織，或使用頂端列的切換器切換至該組織。 用於 [!DNL Assets Essentials] 會顯示在 [!DNL Admin Console].

   ![[!DNL Assets Essentials] 卡片 [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *圖： [!DNL Assets Essentials] 卡片 [!DNL Admin Console].*

   >[!NOTE]
   >
   >如果您可以檢視 **[!UICONTROL AEM Assets Essentials]** 產品區段中的卡片，而非 **[!UICONTROL AEM Assets Essentials - Cloud Manager]** 卡片，Assets Essentials部署已完成。 您可以略過其餘步驟。

1. 將您新增為管理員 `AEM Assets Essentials - Cloud Manager` 中的產品設定檔 [!DNL Admin Console]. 您可以新增組織的其他成員，也可以新增多個管理員，而不是您自己。

1. 按一下 ![新增圖示](assets/do-not-localize/add-icon.svg) to [!UICONTROL Select product profiles]，然後選取 [!UICONTROL Deployment Manager - Assets Essentials] 作為 **[!UICONTROL product profile]**. 此步驟中新增的使用者會收到來自Adobe的電子郵件，其可存取 [!DNL Cloud Manager] 並可以進行部署。

   ![新增管理員並選取產品設定檔，位於 [!DNL Admin Console]](assets/adminconsole-user1.png)

   *圖：新增管理員並選取產品設定檔，位於 [!DNL Admin Console].*

1. 若要存取 [!DNL Cloud Manager]，按一下電子郵件中可存取 [!DNL Cloud Manager]. 或者，您也可以 [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) 在瀏覽器中。

1. 在Cloud Manager使用者介面中，按一下 **[!UICONTROL Add Program]** 從右上角。

1. 提供您選擇的名稱，並選擇性地上傳影像（代表中的程式） [!DNL Cloud Manager])，然後按一下 **[!UICONTROL Create]**. [!DNL Cloud Manager] 設定程式需要幾分鐘的時間。

1. 程式準備就緒時，將游標移至圖磚上，然後按一下 ![新增環境圖示](assets/do-not-localize/add-environment-icon.png).

1. 若要新增 [!DNL Assets Essentials] 服務至您的組織，按一下 **[!UICONTROL Add Environment]**，請選擇名稱和部署區域，然後按一下 **[!UICONTROL Save]**. 以後無法更改部署區域。 嘗試匹配 [!DNL Assets Essentials] 與您要使用的其他解決方案的部署區域 [!DNL Assets Essentials]. 配對的目的是確保以最快的速度網路存取數位資產，並盡可能縮短延遲時間。

   ![在中新增環境 [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *圖：在中新增環境 [!DNL Cloud Manager] 開始使用 [!DNL Assets Essentials].*

1. 幾分鐘後，當環境成功建立時，您可以存取 [!DNL Admin Console] 並將組織的使用者新增至 [!DNL Assets Essentials] 解決方案。 按一下 ![選項表徵圖](assets/do-not-localize/options-ellipses-icon.png) ，然後選取 **[!UICONTROL Manage Access]** 選項。

   ![中的就緒環境 [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *圖：中的環境 [!DNL Cloud Manager] 可供使用。*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] 說明](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] 說明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
>* [Adobe Journey Optimizer檔案](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [發行說明](release-notes.md)
>* [開始使用 [!DNL Assets Essentials]](get-started.md)

