---
title: 將 Assets Essentials 與 Creative Cloud 應用程式整合
description: 將 Assets Essentials 與 Creative Cloud 應用程式整合，以便您可以使用 Adobe Asset Link 應用程式內面板，從受支援的  [!DNL Adobe Creative Cloud]  桌面應用程式中連接到  [!DNL Assets Essentials]  存放庫。
exl-id: 817bc955-0074-435e-83a8-3fd5f7f2505a
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '719'
ht-degree: 100%

---

# 將 Assets Essentials 與 Creative Cloud 應用程式整合 {#integrate-assets-essentials-creative-cloud-applications}

[Adobe Asset Link 應用程式內面板](https://www.adobe.com/tw/creativecloud/business/enterprise/adobe-asset-link.html)可讓專業創意人員從支援的 [!DNL Adobe Creative Cloud] 桌面應用程式內連線到 [!DNL Assets Essentials] 存放庫。面板可供 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD] 使用。 它會簡化資產的存取，進而協助提高內容速度。

只有在您將 Creative Cloud 應用程式與 Experience Manager Assets Essentials 存放庫整合時，Creative Cloud 應用程式使用者才能使用 Adobe Asset Link 應用程式內面板。

執行以下工作，將 Assets Essentials 與 Creative Cloud 應用程式整合：

* [在 Creative Cloud 和 Experience Cloud Admin Console 之間建立目錄託管](#directory-trusting-cc-assets-essentials-consoles)

* [將 Creative Cloud 使用者新增到 Assets Essentials 產品設定檔](#add-cc-users-assets-essentials-product-profiles)

* [安裝 Adobe Asset Link](#install-asset-link)

* [使用 Adobe Asset Link](#use-asset-link)

## 在 Creative Cloud 和 Experience Cloud Admin Console 之間建立目錄託管 {#directory-trusting-cc-assets-essentials-consoles}

如果您的 Creative Cloud 與 Assets Essentials (Experience Cloud 解決方案) 是在不同的 Adobe Admin Console 中進行部署，則必須在兩個主控台之間增加信任關係。

若要整合 Creative Cloud 與 Assets Essentials 應用程式，適用於 Creative Cloud 的 Admin Console 中可用的使用者也必須在適用於 Experience Cloud 的 Admin Console 中設為可用。如果將 Creative Cloud 和 Assets Essentials 部署到單獨的 Admin Console 中，則需要它們之間的信任關係才能啟用此功能。

在 Experience Cloud Admin Console 上，按一下「**[!UICONTROL 設定]**」並使用「**[!UICONTROL 目錄]**」索引標籤建立目錄，以在兩個 Admin Console 之間建立[目錄託管](https://helpx.adobe.com/tw/enterprise/using/set-up-identity.html#directory-trusting)。

## 將 Creative Cloud 使用者新增到 Assets Essentials 產品設定檔 {#add-cc-users-assets-essentials-product-profiles}

在適用於 Creative Cloud 的 Admin Console 和適用於 Experience Cloud 的 Admin Console 之間建立目錄託管後，將 Creative Cloud 使用者指派到 Experience Cloud Admin Console 中 [!DNL Assets Essentials] 產品卡下的「**[!DNL Assets Essentials]使用者**」產品設定檔。它可讓 Creative Cloud 使用者從其 Adobe Asset Link 外掛程式面板存取 Assets Essentials；此外，也可讓他們存取完整的 Assets Essentials 網頁使用者介面，以使用網頁瀏覽器上傳、組織、標記和尋找數位資產。

其他 Assets Essentials 產品設定檔 - **[!DNL Assets Essentials]管理員**&#x200B;和 **[!DNL Assets Essentials]取用者使用者** - 用於不同的使用者權益 (應用程式管理員和透過 Experience Cloud 整合存取 Assets Essentials 的使用者)。

如需如何將使用者指派到 Assets Essentials 產品設定檔的更多資訊，請參閱[將使用者指派到 Assets Essentials 產品設定檔](deploy-administer.md#add-users-to-product-profiles)。

## 安裝 Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] 外掛程式可以透過兩個方式安裝並提供給創意使用者：

* 創意使用者可以從他們的 [!DNL Creative Cloud Desktop] 應用程式安裝外掛程式
* Creative Cloud 管理員可以在 Admin Console 中將 Asset Link 外掛程式新增到 Creative Cloud 套件

選擇取決於組織的 IT 政策。

**使用 [!DNL Creative Cloud Desktop] 應用程式進行安裝**&#x200B;的說明請參閱[這裡](https://helpx.adobe.com/tw/creative-cloud/kb/installingextensionsandaddons.html)。根據 Creative Cloud 應用程式，[Adobe Exchange](https://exchange.adobe.com/) Marketplace 上有兩個可用和託管的外掛程式：

* 對於 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator] 和 [!DNL Adobe InDesign]：[Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* 對於 [!DNL Adobe XD]：[Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**使用 Creative Cloud 套件進行安裝**&#x200B;由 Creative Cloud 管理員在 Admin Console 中完成，方法是在建置部署套件時加入 Asset Link 外掛程式，以便稍後將其部署到使用者電腦。在託管的選擇外掛程式畫面中，在「**功能業務外掛程式**」區段搜尋 **Adobe Asset Link**。如需詳細資訊，請參閱[透過 Admin Console 封裝應用程式](https://helpx.adobe.com/tw/enterprise/using/package-apps-admin-console.html)。

## 使用 Adobe Asset Link {#use-asset-link}

創意使用者現在可將 Adobe Asset Link 搭配 Photoshop、Illustrator、InDesign 或 XD 使用。若要在 InDesign 或 Illustrator 中開啟面板，請至「Windows > 擴充功能 > Adobe Asset Link」。在 Photoshop 中，請移至「視窗 > 擴充功能 (舊版) > Adobe Asset Link」。

如需有關設定 Adobe Asset Link for Adobe XD 的詳細資訊，請按一下[這裡](https://helpx.adobe.com/tw/enterprise/using/adobe-asset-link-for-xd.html)。

>[!NOTE]
>
>使用 Apple Silicon/M1 硬體時，Adobe Photoshop 需要使用 Rosetta 相容性模式啟動，以確保創意使用者可以存取 Adobe Asset Link 面板，因為它是使用 CEP 擴充功能技術建置的。如需詳細資訊，請參閱[適用於 Apple Silicon 的 Photoshop](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html)。


使用 Adobe Asset Link 來處理和修改儲存在Assets Essentials 存放庫內的資產。您可以執行各種工作，例如：

* 搜尋和瀏覽資產

* 上傳資產

* 排序和篩選資產

* 放置、下載和拖曳資產

* 取出和存回資產

* 檢視版本記錄和檔案詳細資料

如需如何執行這些工作的說明，請參閱[使用 Adobe Asset Link 管理資產](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html)。
