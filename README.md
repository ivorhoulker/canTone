# 啱音字 (canTone)

一款專為桌面電腦設計的高效能 0243 粵語填詞工具。採用離線優先架構，提供極速搜尋體驗，隨時隨地皆可使用。

*請注意：本應用程式目前處於公開測試階段（Public Beta），可能仍存在些許錯誤或不穩定之處。感謝您的包容與試用！*

## 📥 下載與安裝

點擊下方按鈕即可直接下載最新版本：

[![Download for Windows](https://img.shields.io/badge/下載_Windows_版-4682B4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ivorhoulker/11/releases/latest) 
[![Download for macOS](https://img.shields.io/badge/下載_macOS_版-87CEEB?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/ivorhoulker/11/releases/latest)

> 💡 **提示：** 點擊上方按鈕將會帶您前往最新發佈頁面。請在該頁面下載 Windows 的 `canTone-Windows.exe`，或根據您的 Mac 型號下載對應的 `.dmg` 檔案（詳見下方說明）。

---

### 🪟 Windows 用戶

請下載 `canTone-Windows.exe` 安裝程式並執行。

> **⚠️ 關於 Windows SmartScreen 的注意事項：** > 由於此應用程式由我獨立開發，Windows Defender 可能會將安裝程式標記為「無法辨識的應用程式」。如需繼續安裝，請在藍色的彈出視窗中點擊 **其他資訊**，然後選擇 **仍要執行**。

---

### 🍎 macOS 用戶

我為 macOS 提供了兩種不同的安裝檔。如果您不確定您的 Mac 使用哪種晶片，請點擊螢幕左上角的 **蘋果選單 () > 關於這台 Mac** 來查看您的處理器或晶片資訊。

* **🍎 Apple Silicon：** 如果顯示的晶片為 M1、M2、M3、M4 或 M5（包含 Pro、Max 或 Ultra 等型號），請下載 `canTone-AppleSilicon.dmg`。
* **💻 Intel：** 如果顯示的處理器包含「Intel」字樣，請下載 `canTone-IntelMac.dmg`。

**安裝步驟：**
1. 雙擊已下載的 `.dmg` 檔案將其開啟。
2. 將應用程式圖示拖曳至 **應用程式 (Applications)** 資料夾。

> **⚠️ 關於 macOS Gatekeeper 的注意事項：** > 由於此應用程式尚未具備 Apple 開發者帳號的數位簽章，macOS 最初可能會顯示「未識別的開發者」或「檔案已損毀」等警告並攔截應用程式。若要開啟應用程式，請前往 **應用程式 (Applications)** 資料夾，**右鍵點擊（或按住 Control 點擊）** 該應用程式，選擇 **打開**，然後在確認視窗中再次點擊 **打開**。

---

*我計畫在未來的更新版本中，為 Windows 與 macOS 版本正式加入數位簽章，以徹底消除這些安全性警告。*

<figure style="height: 400px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
  <video 
    src="https://github.com/user-attachments/assets/56d72caf-0971-4823-8006-fb016ed4945d" 
    autoplay 
    loop 
    muted 
    playsinline
    style="height: 360px; width: auto; object-fit: contain; border-radius: 12px;"
  ></video>
  <figcaption align="center" style="margin-top: 8px;">
    <i>使用 0243 聲調之搜尋介面演示。</i>
  </figcaption>
</figure>

## 🚀 核心功能

* **深度語音搜尋：** 支援透過精確音節、寬鬆旋律（0243）或嚴格押韻矩陣進行搜尋。
* **語言學標籤：** 可按詞性、地域差異及語體色彩進行篩選。
* **語義關聯圖譜：** 原生支援同義詞與反義詞的關聯映射。
* **離線優先：** 完整的資料庫與搜尋引擎皆在您的本機電腦上離線運行，無需連接網路。

---

## 🐛 錯誤回報與功能建議

遇到錯誤或有新功能建議嗎？我使用這個 GitHub 存放庫來追蹤社群的意見回饋。

1. 請先查看 [Issues 標籤頁](https://github.com/ivorhoulker/canTone/issues)，確認該問題是否已被提出。
2. 若尚未有人提出，請開啟一個新的 Issue，並填寫提供的範本，以便我能妥善調查。

---

## ⚖️ 授權條款

本應用程式屬專有軟體（Proprietary software），保留所有權利。您可以下載並將本軟體用於個人用途。

## 🙏 資料來源與鳴謝

本應用程式整合了來自以下專案的資料：

* **[words.hk (粵典)](https://words.hk)**：根據 [非商業開放資料授權條款](https://words.hk/base/hoifong/) 發佈。
* **[Unicode 與 Unihan](https://www.unicode.org/charts/unihan.html)**：Copyright © 1991-Present Unicode, Inc. 根據 [Unicode 版權使用條款](https://www.unicode.org/copyright.html) 及 [Unicode 資料授權條款](https://www.unicode.org/license.txt) 分發。
* **[Kaifangcidian (開放詞典)](https://kaifangcidian.com/yue/)**：根據 [創用 CC 姓名標示 3.0 未本地化版本](https://creativecommons.org/licenses/by/3.0/deed.en) 授權條款分發。
* **[HSK 3.0](https://github.com/elkmovie/hsk30)**：根據 [MIT](https://github.com/elkmovie/hsk30/blob/main/LICENSE) 授權條款分發。

特別鳴謝 Bill（姚程馭）。若不是他不斷提出各種有趣的技術難題，我根本不會著手製作這款工具。