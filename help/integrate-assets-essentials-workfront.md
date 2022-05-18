---
title: 整合Assets Essentials與Adobe Workfront
description: 將Assets Essentials與Adobe Workfront應用程式整合，以便您能夠訪問Workfront應用程式中的Assets Essentials儲存庫。
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 507d5de0fad337f5c84dab28bc396dbfa7c5afe1
workflow-type: tm+mt
source-wordcount: '619'
ht-degree: 16%

---

# 整合Assets Essentials與Adobe Workfront {#integrate-assets-essentials-workfront}

![切換深色和淺色主題的偏好設定](assets/cce-workfront.png)

## 到目前為止

之後 [配置Experience Manager Assets軟體包](adminster-aem-assets-essentials.md) 和 [將Creative Cloud應用程式與Assets Essentials整合](integrate-assets-essentials-creative-cloud.md)您可以繼續將Adobe Workfront應用程式與Assets Essentials整合。

## 目標

* **觀眾**:Adobe Workfront管理員

* **目標**:將Assets Essentials與Adobe Workfront應用程式整合，以便您能夠訪問Workfront應用程式中的Assets Essentials儲存庫。

## 概覽

[[!DNL Adobe Workfront]](https://www.workfront.com/) 是一種工作管理應用程式，可幫助您在一個位置管理整個工作生命週期。 本機整合 [!DNL Adobe Workfront] 和 [!DNL Assets Essentials] 使公司能夠通過將工作和資產管理內在地聯繫起來，提高內容的速度和上市時間。 就管理其工作而言，使用者可以存取在同一解決方案中的所需文件和影像。

執行以下任務以將Workfront與Experience Manager Assets軟體包整合：

* [將用戶添加到Workfront產品配置檔案](#add-users-to-product-profiles)

* [將用戶添加到Assets Essentials產品配置檔案](#add-workfront-users-assets-essentials-product-profiles)

* [配置Experience Manager Assets軟體包整合](#configure-assets-essentials-integration)

## 將用戶添加到Workfront產品配置檔案 {#add-users-to-product-profiles}

要將用戶添加到Workfront產品配置檔案：

1. 訪問 [Admin Console](https://adminconsole.adobe.com) 對於您的組織，按一下 **[!UICONTROL 產品]** 按一下 **[!UICONTROL Workfront]**，然後按一下清單中的第一個實例。 請勿按滑鼠清單中的第二個實例和第三個實例。

   ![Admin Console 管理員設定檔](assets/workfront-instances.png)

   Admin Console顯示唯一可用的產品配置檔案。

1. 要將用戶添加到產品配置檔案，請按一下配置檔案，按一下 **[!UICONTROL 添加用戶]**，提供用戶詳細資訊，然後按一下 **[!UICONTROL 保存]**。

   ![新增使用者管理員設定檔](assets/add-users-workfront.png)

   新增使用者時，使用者會收到開始使用的電子郵件邀請。您可以在 [!DNL Admin Console] 中的產品設定檔設定中關閉電子郵件邀請。

1. 若要從群組移除使用者，請按一下該群組、選取現有使用者，然後選取&#x200B;**[!UICONTROL 移除使用者]**。

有關如何在Workfront與Adobe Admin Console一起建立用戶和系統管理員的詳細資訊，請參見 [管理Adobe Admin Console用戶](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus)。

## 將用戶添加到Assets Essentials產品配置檔案 {#add-workfront-users-assets-essentials-product-profiles}

將Workfront用戶分配給以下Assets Essentials產品配置檔案之一：

* **[!DNL Assets Essentials]用戶** 可以訪問完整的Assets Essentials用戶介面。 這些用戶可以在Assets Essentials應用程式中上傳、組織、標籤和查找數字資產。 此外，用戶可於Windows Server上獲得嵌入式資產選擇 [!DNL Adobe Workfront] 的子菜單。
* **[!DNL Assets Essentials]消費者用戶**:有權在Oracle Group獲得 [!DNL Adobe Workfront] 的子菜單。

有關如何將用戶分配給Assets Essentials產品配置檔案的詳細資訊，請參閱 [將用戶分配到Assets Essentials產品配置檔案](adminster-aem-assets-essentials.md#add-users-to-product-profiles)。

## 配置Experience Manager Assets軟體包整合 {#configure-assets-essentials-integration}

使用Admin Console將用戶添加到Workfront和Assets Essentials產品配置檔案後，您可以 [配置與Adobe Workfront的Experience Manager Assets軟體包整合](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm)。

設定整合後，您可以：

* [連結來自Experience Manager Assets軟體包的資產和資料夾](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [將文檔發送到Experience Manager Assets軟體包](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [證明Experience Manager Assets軟體包的連結資產](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [查看或下載從Experience Manager Assets軟體包連結的資產](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
