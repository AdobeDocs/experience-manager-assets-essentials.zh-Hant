---
title: 管理和管理用戶
description: 管理使用案例，如部署和用戶管理 [!DNL Assets Essentials]。
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: fb4ca5b3ab85f77cc1013c2d4743530f5d48e96d
workflow-type: tm+mt
source-wordcount: '1129'
ht-degree: 1%

---

# 管理 [!DNL Assets Essentials] 添加用戶 {#administer}

[!DNL Adobe Experience Manager Assets Essentials] 由Adobe為其客戶提供。 作為配置的一部分， [!DNL Assets Essentials] 添加到中的客戶組織 [!DNL Adobe Admin Console]。 管理員將使用 [!DNL Admin Console] 要管理用戶權利 [!DNL Assets Essentials] 解決方案，並分配應用程式管理員以在 [!DNL Assets Essentials]。

## 自動部署Assets Essentials {#automatic-deployment-assets-essentials}

配置Assets Essentials解決方案後，管理員將收到來自Adobe的電子郵件。 電子郵件包含歡迎郵件和要開始的連結。 此外，Adobe還會啟動自動部署Assets Essentials的進程。 部署過程需要一個小時才能完成。

從電子郵件中的連結，訪問和登錄到 [Admin Console](https://adminconsole.adobe.com)。 如果您擁有對多個組織帳戶的管理員訪問權限，請選擇相應的組織或使用頂欄中的交換機切換到該組織。 完成自動部署過程後， [!DNL AEM Assets Essentials] 在 [!DNL Admin Console]。

![Assets Essentials部署](assets/assets-essentials-deployment.png)

成功部署Assets Essentials解決方案後，管理員需要執行以下任務：

* [設定用戶組、資料夾結構並分配權限](manage-permissions.md) 為瞭解決問題。 關注 [最佳做法](permission-management-best-practices.md) 確保設定簡單有效的權限。
* [管理用戶訪問](#add-users-to-essentials) 組織成員到 [!DNL Assets Essentials]。
* （可選） [查看服務狀態和日誌](#view-logs)。

>[!NOTE]
>
>如果在2022年1月6日之前設定了Assets Essentials，請執行 [雲管理器中的部署步驟](#deploy-essentials) 管理組織成員的用戶訪問。


## 用戶管理 {#add-users-to-essentials}

管理員管理哪些用戶有權訪問 [!DNL Assets Essentials]。 管理員使用 [!DNL Adobe Admin Console] 添加或刪除用戶訪問權限。 [!DNL Assets Essentials] 具有以下兩種用戶訪問類型。

* **[!DNL Assets Essentials]管理員** 具有對應用程式的管理訪問權限。 除了所有最終用戶權能外，此組中的應用程式管理員可以管理整個應用程式儲存庫中任何資料夾和組/用戶的權限。
* **[!DNL Assets Essentials]用戶** 有權訪問完整的用戶介面。 這些用戶可以上傳、組織、標籤和查找數字資產。
* **[!DNL Assets Essentials]消費者用戶**:有權在Oracle Group獲得 [!DNL Adobe Journey Optimizer] 電子郵件模板編輯器。 有關詳細資訊，請參見 [使用 [!DNL Assets Essentials] 在 [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html)。

在 [!DNL Admin Console]，這三種訪問類型由三種表示 [!UICONTROL 產品配置檔案]。 要將組織成員添加到這兩個配置檔案中的任意一個並將其移除，請執行以下步驟：

1. 訪問 [!DNL Admin Console] 對於您的組織，按一下 **[!UICONTROL 產品]** 按一下 **[!UICONTROL AEM Assets精華]**，然後按一下 [!DNL Assets Essentials] 環境。 [!DNL Assets Essentials] 有三個產品配置檔案，它們代表管理員、普通用戶和消費者用戶的訪問權限。

   ![三種用戶的三種配置檔案](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *圖：有三種配置式可用於添加三種類型的用戶。*

1. 要將用戶添加到組，請按一下組，選擇 **[!UICONTROL 添加用戶]**，提供用戶詳細資訊，然後按一下 **[!UICONTROL 保存]**。 添加用戶時，用戶將收到開始使用的電子郵件邀請。 您可以在中的產品配置檔案設定中關閉電子郵件邀請 [!DNL Admin Console]。

   ![將用戶添加到 [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *圖：將用戶添加到 [!DNL Assets Essentials] 從 [!DNL Admin Console]。*

1. 要從組中刪除用戶，請按一下該組，選擇現有用戶，然後選擇 **[!UICONTROL 刪除用戶]**。

>[!TIP]
>
>在 [!DNL Admin Console]，您可以使用CSV檔案批量管理用戶。 要瞭解更多資訊，請參閱 [[!DNL Admin Console] 文檔](https://helpx.adobe.com/enterprise/using/accounts.html)。

## 查看服務狀態和訪問日誌 {#view-logs}

設定後，管理員將部署 [!DNL Assets Essentials] 只有一次。 初始部署後，Adobe將執行服務維護和更新。 管理員可以使用 [!DNL Cloud Manager] 用戶介面，檢查服務狀態並下載最近的訪問日誌。

1. 當用戶報告問題時，檢查 [!DNL Assets Essentials] 的 **[!UICONTROL 計畫概述]** 。 在解決方案的正常工作過程中，狀態為 `Running`。 如果 [!DNL Cloud Manager] 顯示任何其他狀態，在 [!DNL Admin Console] 支援部分。

   ![狀態 [!DNL Assets Essentials] 在 [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *圖：正常狀態 [!DNL Assets Essentials] 在 [!DNL Cloud Manager] 是 `Running`。*

1. 要下載最近的訪問日誌，請按一下 ![選項](assets/do-not-localize/options-ellipses-icon.png)選中 **[!UICONTROL 下載日誌]**，並按照螢幕說明進行操作。 您可以使用日誌審核HTTPS訪問請求。

   ![ 下載訪問日誌的選項](assets/cloudmanager-download-logs.png)

   *圖：下載訪問日誌的選項。*

## 部署 [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>僅當在2022年1月6日之前配置了Assets Essentials時，才執行這些步驟。

預配後， [!DNL Assets Essentials] 權利將添加到您的組織中 [!DNL Admin Console]。 在該解決方案可供用戶使用之前，組織管理員必須部署它。 管理員使用 [!DNL Cloud Manager] 用戶介面。 初始部署後，Adobe將執行服務維護和更新。 設定解決方案後，管理員將收到來自Adobe的電子郵件。 電子郵件包含歡迎郵件和要開始的連結。 要部署，請執行以下步驟：

1. 從電子郵件中的連結，訪問和登錄到 [Admin Console](https://adminconsole.adobe.com)。 如果您擁有對多個組織帳戶的管理員訪問權限，請選擇相應的組織或使用頂欄中的交換機切換到該組織。 產品卡 [!DNL Assets Essentials] 在 [!DNL Admin Console]。

   ![[!DNL Assets Essentials] 卡 [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *圖： [!DNL Assets Essentials] 卡 [!DNL Admin Console]。*

   >[!NOTE]
   >
   >如果可以查看 **[!UICONTROL AEM Assets精華]** 在產品部分而不是 **[!UICONTROL AEM Assets軟體包 — 雲管理器]** 卡，Assets Essentials部署已經完成。 您可以跳過其餘步驟。

1. 將您作為管理員添加到 `AEM Assets Essentials - Cloud Manager` 產品配置檔案 [!DNL Admin Console]。 您可以添加組織的其他成員，也可以添加多個管理員，而不是您自己。

1. 按一下 ![添加表徵圖](assets/do-not-localize/add-icon.svg) 至 [!UICONTROL 選擇產品配置檔案]，然後選擇 [!UICONTROL 部署經理 — Assets Essentials] 的 **[!UICONTROL 產品配置檔案]**。 此步驟中添加的用戶接收來自Adobe的電子郵件，該電子郵件具有 [!DNL Cloud Manager] 並且可以進行部署。

   ![添加管理員並在中選擇產品配置檔案 [!DNL Admin Console]](assets/adminconsole-user1.png)

   *圖：添加管理員並在中選擇產品配置檔案 [!DNL Admin Console]。*

1. 訪問 [!DNL Cloud Manager]，按一下電子郵件中具有訪問權限的連結 [!DNL Cloud Manager]。 或者，訪問 [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) 的子菜單。

1. 在Cloud Manager用戶介面中，按一下 **[!UICONTROL 添加程式]** 從右上角。

1. 提供您選擇的名稱，並可選地上載映像(它表示中的程式 [!DNL Cloud Manager])，然後按一下 **[!UICONTROL 建立]**。 [!DNL Cloud Manager] 設定程式需要幾分鐘。

1. 程式準備好後，將指針懸停在磁貼上，然後按一下 ![添加環境表徵圖](assets/do-not-localize/add-environment-icon.png)。

1. 添加 [!DNL Assets Essentials] 服務到您的組織，按一下 **[!UICONTROL 添加環境]**，選擇名稱和部署區域，然後按一下 **[!UICONTROL 保存]**。 以後不能更改部署區域。 嘗試匹配的部署區域 [!DNL Assets Essentials] 與您要使用的其他解決方案的部署區域 [!DNL Assets Essentials]。 匹配是為了確保盡可能快的網路訪問數字資產和盡可能低的延遲。

   ![在 [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *圖：在 [!DNL Cloud Manager] 開始使用 [!DNL Assets Essentials]。*

1. 幾分鐘後，當環境成功建立時，您可以訪問 [!DNL Admin Console] 並將組織的用戶添加到 [!DNL Assets Essentials] 解決方案。 按一下 ![選項](assets/do-not-localize/options-ellipses-icon.png) 的 **[!UICONTROL 管理訪問]** 的雙曲餘切值。

   ![中的就緒環境 [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *圖：環境 [!DNL Cloud Manager] 已準備好使用。*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] 說明](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] 說明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
>* [Adobe Journey Optimizer文檔](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [發行說明](release-notes.md)
>* [開始使用 [!DNL Assets Essentials]](get-started.md)

