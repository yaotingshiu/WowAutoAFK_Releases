# 🎣 WowAutoAFK (暫未開放下載)

![Version](https://img.shields.io/badge/Version-2.1.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![Framework](https://img.shields.io/badge/.NET-10.0-512BD4.svg)
![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C.svg)
![Status](https://img.shields.io/badge/Status-Closed_Source-red.svg)

WowAutoAFK 是一款專為《魔獸世界》玩家設計的自動化輔助工具。本程式旨在協助玩家輕鬆處理自動登入、掛機防斷以及自動釣魚等日常事務，大幅減輕遊戲中的重複性操作。

本專案採用 **C# (WPF/WinForms) 與 C++** 的混合架構設計，兼顧了「高效的介面開發」與「極致的核心運算效能」：
*   **前端 UI 層 (C#)**：利用 .NET UI 框架，建立直覺、流暢且高響應性的使用者介面與資料綁定。
*   **核心運算層 (C++)**：負責處理底層演算法，確保執行效率，同時有效防止程式碼被輕易反編譯。
*   **資安防護**：帳號密碼採用 Windows DPAPI 加密機制，確保您的帳戶資訊安全無虞。

透過極簡的現代化介面與深淺雙色主題，WowAutoAFK 提供最直覺的操作體驗，讓您徹底告別繁瑣的農怪與掛機動作！歡迎下載試玩（**強烈建議不要在官方正服連續使用過長時間，以免增加帳號被凍結的風險**）。

> 💡 **註**：為防止有心人士惡意篡改程式獲利，本專案採閉源 (Closed-Source) 發布。

---

## ✨ 核心特色 (Features)

*   **自動登入系統**：支援帳號密碼加密儲存與多帳號管理，一鍵快速切換角色進入遊戲。
*   **智能掛機防斷**：內建多種掛機頻率與模式（如原地跳躍、隨機動作），完全模擬真人按鍵操作。
*   **視覺化自動釣魚**：利用精準的圖像識別技術自動偵測浮標咬餌，支援收竿連擊與防呆機制。
*   **無干擾背景執行**：掛機與登入功能全程可於背景運作（不含釣魚），不影響您處理其他電腦作業。支援縮小至系統匣與懸浮迷你視窗。
*   **各國使用者體驗優化**：內建繁體中文、簡體中文及英文三種語系，隨系統語言自動切換，並加入精緻的自繪 UI 動畫特效。

### 🚀 v2.1.0 最新更新內容
1.  **全新自繪 UI**：支援深色（雷蛇電競風格）與淺色（清爽簡約）雙模式自由切換。
2.  **懸浮窗功能**：新增迷你懸浮視窗，狀態監控更便利。
3.  **多開掛機支援**：掛機功能導入多執行緒運作，支援多開視窗同時掛機，動作與間隔時間互不衝突。
4.  **擬人化釣魚操作**：釣魚功能加入滑鼠擬人軌跡，徹底告別容易被偵測的機器人瞬移游標。
5.  **掛機/釣魚無縫協同**：當有多個掛機任務執行時，可隨時指定其中一個視窗進行釣魚，取消釣魚後系統將無縫恢復掛機狀態。

---

## 📖 詳細使用教學 (Tutorial)

### 一、 初次環境設定
1.  **指定遊戲路徑**：開啟程式後，於主介面「主程式路徑」欄位，選擇您的 `WoW.exe` 執行檔路徑。
2.  **調整延遲參數**：在「登入動作延遲」區塊，請依據您的電腦載入速度調整延遲秒數。
    > 💡 **提示**：建議設為 10-15 秒以上以確保載入穩定；若電腦配備較舊，請適度調高秒數。

### 二、 自動登入
1.  前往「帳號登入」分頁，輸入遊戲帳號與密碼後點擊「儲存帳號」。
2.  在帳號清單中按右鍵將該帳號設為「預設」。
3.  確認遊戲尚未開啟，點擊「自動登入遊戲」，程式將自動啟動遊戲並完成密碼輸入。

### 三、 自動掛機
1.  前往「自動掛機」分頁，在右側的**遊戲視窗列表**中勾選欲掛機的視窗（支援多開勾選）。
2.  設定「動作模式」（如：深度潛水）與「動作頻率」（如：原地跳躍）。
3.  按下設定好的「掛機快捷鍵」（預設 `Ctrl + F2`）即可快速啟動或停止。

### 四、 自動釣魚 (需保持遊戲畫面可見)
1.  前往「自動釣魚」分頁，設定對應遊戲內的拋竿快捷鍵。
2.  點擊「截取浮標圖片」，畫面將進入截圖模式，請精準框選您的「釣魚浮標」。
    *(範例圖示如下)*<br>
    <img width="83" height="84" alt="2026-07-17_162752" src="https://github.com/user-attachments/assets/75c26d5c-5c10-4055-8f77-8ffda55d092b" />
3.  調整釣魚時間模式（連續或定時）。
4.  按下「釣魚快捷鍵」（預設 `Ctrl + F8`）正式啟動。
   
> ⚠️ **釣魚注意事項**：
> * 為確保影像辨識順暢，釣魚期間請避免操作鍵盤與滑鼠，以免干擾程式判定。
> * 建議避免使用浮動較大或容易變形的特殊外觀浮標，以免造成判定失誤。

---

## ⚙️ 快捷鍵自定義 (Hotkeys)

您可以於「設定」分頁自由更改掛機與釣魚的觸發快捷鍵。
*   **支援範圍**：`Ctrl + F1` 至 `Ctrl + F9`。
*   **自動互斥機制**：系統內建防衝突保護，掛機與釣魚無法同時在單一視窗啟動（若在掛機中按下釣魚快捷鍵，系統會自動中斷掛機並切換至釣魚）。

---

## 🛡️ 安全性、運作原理與免責聲明 (Security & Disclaimer)

### ✅ 絕對無修改遊戲記憶體 (Strictly NO Memory Modification)
本程式採用「純外部視覺分析」與「系統底層硬體模擬」技術，**沒有**也不會對遊戲客戶端進行任何危險的侵入性操作。
*   **❌ 不讀寫記憶體**：不會掃描或竄改遊戲的 RAM 數據。
*   **❌ 不注入程式碼**：不會向遊戲客戶端注入任何外部 DLL 或惡意程式碼。
*   **❌ 不修改遊戲檔案**：不會更改任何遊戲原始檔案或攔截封包。
*   **⭕ 純視覺辨識**：完全依賴 OpenCV 進行螢幕截圖與影像色彩分析判斷浮標。
*   **⭕ 硬體級輸入**：透過 Windows 底層 API 模擬真實鍵鼠訊號，並加入亂數延遲與擬人化軌跡。

### ⚠️ 風險提示與聲明條款
**當您開啟並使用本程式，即代表您已詳閱並無條件同意以下所有聲明與條款：**

1.  **帳號凍結風險**：儘管本程式在技術層面上避開了防作弊系統 (如 Warden) 的記憶體掃描，但使用任何第三方自動化工具依然違反《魔獸世界》的使用條款 (TOS)。若遭玩家檢舉或被系統行為分析判定異常，仍有帳號被凍結的風險。（**官方正服取締嚴格，強烈不建議於正服長時間使用**）。玩家需自行評估並承擔相關風險，開發者概不負責。
2.  **隱私與資安保證**：您的帳號密碼與個人設定僅會加密並儲存於您的本機電腦中，本程式絕無且不會有任何回傳或收集隱私之行為。
3.  **非商業用途**：本程式為免費工具，僅供個人便利與研究交流使用，嚴禁任何商業營利行為。
4.  **軟體來源與防毒誤判**：建議僅從此官方管道下載本程式。本程式未經加殼，僅經過基本的程式碼混淆，經各大測毒網站 (如 VirusTotal, Hybrid Analysis) 評測皆為安全，僅有極低機率會遭部分防毒軟體誤判。若您從非官方管道取得遭到惡意植入病毒的檔案，開發者概不負責。

---

## 🎬 操作影片 (Demo)

### 介面功能展示
<video src="https://github.com/user-attachments/assets/680fd35b-023b-405b-8f8b-e20dc7274d1b"></video>

<br><br>
### 懸浮窗功能
<video src="https://github.com/user-attachments/assets/58fb90f6-7d3d-44ac-b2bb-f9d6f5836a6a"></video>

<br><br>
*(因容量限制無法上傳更多高畫質內容，歡迎直接下載親自體驗！)*

## ☕ 贊助開發者 (Donate & Contact)

如果您覺得這款軟體對您有幫助，歡迎請我喝杯咖啡！您的支持是我持續更新與修復 Bug 的最大動力。

*   💳 [**點此透過 PayPal 贊助我**](https://www.paypal.com/ncp/payment/D7GSCCJEHTSFN)

如果您有任何 Bug 回報、功能建議或是使用上的疑問，歡迎透過以下方式聯繫我：
*   📧 **Email:** [speed132454@gmail.com](mailto:speed132454@gmail.com)

---

## 📸 軟體介面截圖 (Screenshots)

<details>
<summary>點擊展開查看程式介面</summary>
<br>

<img width="507" height="395" alt="2026-08-04_025313" src="https://github.com/user-attachments/assets/37a16259-0e4f-4f77-9e95-fc30f99b9824" />

<br><br>
<img width="508" height="395" alt="2026-08-04_025657" src="https://github.com/user-attachments/assets/92c67147-38b0-4f08-aeb7-fc306e256bdd" />

<br><br>
<img width="508" height="397" alt="2026-08-04_025731" src="https://github.com/user-attachments/assets/48f2c148-a6b7-459e-8d8d-60a9ab86c546" />

<br><br>
<img width="510" height="397" alt="2026-08-04_025827" src="https://github.com/user-attachments/assets/3d82a58e-d3cd-4657-8f78-24ab29c0bb09" />
<br><br>
<img width="509" height="396" alt="2026-08-04_025937" src="https://github.com/user-attachments/assets/244c4d32-5ab8-49d4-b59a-9e730d333de7" />

<br><br>
<img width="387" height="314" alt="2026-08-04_030002" src="https://github.com/user-attachments/assets/c3c7bb61-0e62-4f0b-abe5-ca2dc048427b" />

<br><br>
<img width="508" height="395" alt="2026-08-04_030049" src="https://github.com/user-attachments/assets/76c33531-2b88-4eb4-a9c9-22fb6cc6445a" />

<br><br>
<img width="508" height="395" alt="2026-08-04_030107" src="https://github.com/user-attachments/assets/f3c8d909-ed50-44db-a4f5-e74a80ae4cb9" />

<br><br>
<img width="248" height="436" alt="2026-08-04_030204" src="https://github.com/user-attachments/assets/e4af4b07-d918-404d-ac93-b9e3917e1f6c" />

<br><br>
<img width="510" height="397" alt="2026-08-04_030249" src="https://github.com/user-attachments/assets/b62a3f24-fdaf-4ebf-aaac-c7afbd4d8dba" />

<br><br>
<img width="510" height="397" alt="2026-08-04_030333" src="https://github.com/user-attachments/assets/e34f9ae9-cb9d-4cb2-9475-834573fe4e21" />

<br><br>
<img width="234" height="438" alt="2026-08-04_030427" src="https://github.com/user-attachments/assets/9e59c22b-e817-4c5b-82f8-6cdd5d1ebecc" />

</details>
