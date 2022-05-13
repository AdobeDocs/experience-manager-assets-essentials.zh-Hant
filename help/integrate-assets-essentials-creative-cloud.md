---
title: 將Assets Essentials與Creative Cloud應用程式整合
description: 將Assets Essentials與Creative Cloud應用程式整合，以便您可以使用Adobe資產連結應用程式內面板連接到 [!DNL Assets Essentials] 支援的儲存庫 [!DNL Adobe Creative Cloud] 案頭應用程式。
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# 將Assets Essentials與Creative Cloud應用程式整合 {#integrate-assets-essentials-creative-cloud-applications}

![切換深色和淺色主題的偏好設定](assets/cce-creative-cloud.png)

## 到目前為止

之後 [配置Experience Manager Assets軟體包](adminster-aem-assets-essentials.md) 在本教程中，您可以利用經驗將Creative Cloud應用程式與Assets Essentials整合。

## 目標

* **觀眾**:Creative Cloud管理員

* **目標**:將Assets Essentials與Creative Cloud應用程式整合，以便您的創意用戶可以使用Adobe資產連結應用程式內面板連接到 [!DNL Assets Essentials] 支援的儲存庫 [!DNL Adobe Creative Cloud] 案頭應用程式。

## 概覽

[Adobe資產連結應用內面板](https://www.adobe.com/tw/creativecloud/business/enterprise/adobe-asset-link.html) 讓創意專業人員 [!DNL Assets Essentials] 支援的儲存庫 [!DNL Adobe Creative Cloud] 案頭應用。 面板可供 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD] 使用。 它簡化了對資產的訪問，進而有助於提高內容速度。

Creative Cloud應用程式用戶只有在將Adobe應用程式與Experience Manager Assets軟體包儲存庫整合時，才能使用Creative Cloud資產連結應用程式內面板。

執行以下任務以將Assets Essentials與Creative Cloud應用程式整合：

* [在Creative Cloud和Experience CloudAdmin Console之間建立目錄信任](#directory-trusting-cc-assets-essentials-consoles)

* [將Creative Cloud用戶添加到Assets Essentials產品配置檔案](#add-cc-users-assets-essentials-product-profiles)

* [安裝Adobe資產連結](#install-asset-link)

* [使用Adobe資產連結](#use-asset-link)

## 建立Creative Cloud和Experience CloudAdmin Console之間的目錄信任 {#directory-trusting-cc-assets-essentials-consoles}

如果您的Creative Cloud部署在單獨的Adobe管理控制台中，而不是與Assets Essentials(Experience Cloud解決方案)一起部署的控制台，則您需要在兩個控制台之間添加信任關係。

要整合Creative Cloud和Assets Essentials應用程式，必須使Admin Console中可用於Creative Cloud的用戶以Admin Console進行Experience Cloud。 如果將Creative Cloud和Assets Essentials部署到單獨的Admin Console中，則需要它們之間的信任關係才能啟用此功能。

在Experience CloudAdmin Console上，按一下 **[!UICONTROL 設定]** 並使用 **[!UICONTROL 目錄]** 頁籤，建立要建立的目錄 [目錄信任](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) 兩個Admin Console。

## 將Creative Cloud用戶添加到Assets Essentials產品配置檔案 {#add-cc-users-assets-essentials-product-profiles}

在Admin ConsoleCreative Cloud和Admin ConsoleExperience Cloud之間建立目錄信任後，將Creative Cloud用戶分配給 **[!DNL Assets Essentials]用戶** 產品配置檔案 [!DNL Assets Essentials] 產品卡在Experience CloudAdmin Console中。 它將允許Creative Cloud用戶從其Adobe資產連結插件面板訪問Assets Essentials;此外，它還將允許他們訪問Assets Essentials的完整網路用戶介面，用網路瀏覽器上傳，組織，標籤和查找數字資產。

其他Assets Essentials產品配置檔案 —  **[!DNL Assets Essentials]管理員** 和 **[!DNL Assets Essentials]消費者用戶**  — 用於不同的用戶權利(應用程式管理員和用戶通過Experience Cloud整合訪問Assets Essentials)。

有關如何將用戶分配給Assets Essentials產品配置檔案的詳細資訊，請參閱 [將用戶分配到Assets Essentials產品配置檔案](adminster-aem-assets-essentials.md#add-users-to-product-profiles)。

## 安裝Adobe資產連結 {#install-asset-link}

[!DNL Adobe Asset Link] 插件可以通過兩種方式安裝並提供給創意用戶：

* Creative用戶可以從他們的 [!DNL Creative Cloud Desktop] 應用
* Creative Cloud管理員可以將資產連結插件添加到Admin Console中的Creative Cloud包

選擇取決於組織IT策略。

**安裝使用 [!DNL Creative Cloud Desktop] 應用** 描述 [這裡](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html)。 有兩個插件可用並承載在 [AdobeExchange](https://exchange.adobe.com/) 市場，具體取決於Creative Cloud應用程式：

* 對於 [!DNL Adobe Photoshop]。 [!DNL Adobe Illustrator], [!DNL Adobe InDesign]: [Adobe資產連結CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* 對於 [!DNL Adobe XD]: [Adobe資產連結](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**安裝Creative Cloud包** 由Creative Cloud管理員在Admin Console中完成，方法是在構建部署包時包括「資產連結」插件，這些插件稍後可以部署到用戶電腦。 在托管的「選擇插件」螢幕中，搜索 **Adobe資產連結** 的 **特色業務插件** 的子菜單。 有關詳細資訊，請參見 [通過Admin Console打包應用](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html)。

## 使用Adobe資產連結 {#use-asset-link}

創意用戶現在可以與Photoshop、Illustrator、InDesign或Adobe使用資產鏈XD接。 要在InDesign或Illustrator中開啟面板，請轉至Windows >擴展>Adobe資產連結。 在Photoshop，轉至「窗口」>「擴展（舊版）」>「Adobe資產連結」。

有關如何為Adobe XD設定Adobe資產連結的資訊，請按一下 [這裡](https://helpx.adobe.com/tw/enterprise/using/adobe-asset-link-for-xd.html)。

>[!NOTE]
>
>在使用Apple硅/M1硬體時，Adobe Photoshop需要使用Rosetta相容模式啟動，以確保創意用戶能夠訪問Adobe資產連結面板，因為該面板是使用CEP擴展技術構建的。 有關詳細資訊，請參見 [Photoshop為Apple硅](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html)。


使用Adobe資產連結可以處理和修改儲存在Assets Essentials儲存庫中的資產。 您可以執行各種任務，例如：

* 搜索和瀏覽資產

* 上傳資產

* 排序和篩選資產

* 放置、下載和拖動資產

* 簽出和簽入資產

* 查看版本歷史記錄和檔案詳細資訊

有關如何執行這些任務的說明，請參見 [使用Adobe資產連結管理資產](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html)。

## 下一步是什麼

現在您已將Creative Cloud應用程式與Assets Essentials整合， [將Adobe Workfront與Experience Manager Assets軟體包整合](integrate-assets-essentials-workfront.md)。
