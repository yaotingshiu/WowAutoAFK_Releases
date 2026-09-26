# WowAutoAFK (魔獸世界輔助工具)

![Version](https://img.shields.io/badge/Version-2.2.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![Framework](https://img.shields.io/badge/.NET-10.0-512BD4.svg)
![Language](https://img.shields.io/badge/Language-C%2B%2B%20%7C%20C%23-00599C.svg)
![Status](https://img.shields.io/badge/Status-Closed_Source-red.svg)<br><br>

### 💻 系統支援度 (Supported OS)
<br>

✅ **Windows 10 及以上版本** (包含 Windows 11)<br>
❌ **macOS**<br>
❌ **Linux**
<br><br>
[**📥 點擊這裡下載：最新 WowAutoAFK (v2.2.1) 安裝檔 / Download Latest Version**](https://github.com/yaotingshiu/WowAutoAFK_Releases/raw/refs/heads/main/WowAutoAFK%20v2.2.1%20installer.exe?download=)<br><br>

---

### 📸 軟體介面截圖 / Screenshots
<details>
<summary>點擊展開查看程式介面 / Click to expand screenshots</summary>
<br>
<img width="410" height="333" alt="2026-08-04_025313" src="https://github.com/user-attachments/assets/862e2326-693c-456b-8086-987103e76db6" />
<br><br>
<img width="510" height="397" alt="2026-08-04_091020" src="https://github.com/user-attachments/assets/70be48f4-026a-4c12-9299-f59994ba563f" />
<br><br>
<img width="509" height="397" alt="2026-08-04_091050" src="https://github.com/user-attachments/assets/088a795c-7d20-4db4-97a7-34c16d6ed09d" />
<br><br>
<img width="508" height="396" alt="2026-08-04_091121" src="https://github.com/user-attachments/assets/427e8bfb-a41c-4075-bd8d-9a79cd182c20" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091155" src="https://github.com/user-attachments/assets/f8191cff-aaa0-42c5-bd39-0273af0e5cdf" />
<br><br>
<img width="508" height="396" alt="2026-08-04_091252" src="https://github.com/user-attachments/assets/1b1fc8cb-bce6-4565-8f3f-367d08b16067" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091317" src="https://github.com/user-attachments/assets/3c6ee0e8-34cb-4546-8475-d71bc48f6f81" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091349" src="https://github.com/user-attachments/assets/4bad01cd-9730-4af7-88aa-672cdd3d6a67" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091415" src="https://github.com/user-attachments/assets/ce4cd748-6dc1-43c9-9aef-f5bd52298ead" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091452" src="https://github.com/user-attachments/assets/a0cff961-8723-4f7e-8fba-3ea584ac8728" />
<br><br>
<img width="508" height="395" alt="2026-08-04_091510" src="https://github.com/user-attachments/assets/655bfe68-3b52-4f7c-ab54-184349a654fa" />
<br><br>
<img width="231" height="438" alt="2026-08-04_091634" src="https://github.com/user-attachments/assets/59c69750-59e4-41d3-9bc5-dec7b2081160" />
<br><br>
<img width="233" height="438" alt="2026-08-04_091658" src="https://github.com/user-attachments/assets/545a6a43-971e-4174-b122-5bc726595315" />
<br><br>
<img width="253" height="113" alt="2026-08-04_091733" src="https://github.com/user-attachments/assets/cafe9492-64e0-4b16-8037-805349f8a9c7" />
</details>

---

### 繁體中文 (Traditional Chinese)
<details>
 <summary>點擊展開介紹 / Click to expand introduction</summary><br>

> 💻 **【系統環境需求】**
> 本程式基於 **.NET 10** 框架開發。若您的電腦尚未安裝此環境，請無須擔心！
> 首次開啟程式時，系統會自動跳出安全提示，並無縫引導您前往微軟官方完成一鍵下載與安裝。
<br>

WowAutoAFK 是一款專為《魔獸世界》玩家設計的自動化輔助工具。本程式旨在協助玩家輕鬆處理自動登入、掛機防斷以及自動釣魚等日常事務，大幅減輕遊戲中的重複性操作。

本專案採用 **C# (WPF/WinForms) 與 C++** 的混合架構設計，兼顧了「高效的介面開發」與「極致的核心運算效能」：
*   **前端 UI 層 (C#)**：利用 .NET UI 框架，建立直覺、流暢且高響應性的使用者介面與資料綁定。
*   **核心運算層 (C++)**：負責處理底層演算法，確保執行效率，同時有效防止程式碼被輕易反編譯。
*   **資安防護**：帳號密碼採用 Windows DPAPI 加密機制，確保您的帳戶資訊安全無虞。

透過極簡的現代化介面與深淺雙色主題，WowAutoAFK 提供最直覺的操作體驗，讓您徹底告別繁瑣的農怪與掛機動作！歡迎下載試玩（**強烈建議不要在官方正服連續使用過長時間，以免增加帳號被凍結的風險**）。

>   **註**：為防止有心人士惡意篡改程式獲利，本專案採閉源 (Closed-Source) 發布。

---

##  核心特色 (Features)

*   **自動登入系統(Auto-login)**：支援帳號密碼加密儲存與多帳號管理，一鍵快速切換角色進入遊戲。
*   **智能掛機多開背景防斷(AFK in background & Multi-boxing)**：內建多種掛機頻率與模式（如原地跳躍、隨機動作），完全模擬真人按鍵操作。
*   **視覺化自動釣魚(Auto-fishing)**：利用精準的圖像識別技術自動偵測浮標咬餌，支援收竿連擊與防呆機制。
*   **無干擾背景執行**：掛機與登入功能全程可於背景運作（不含釣魚），不影響您處理其他電腦作業。支援縮小至系統匣與懸浮迷你視窗。
*   **各國使用者體驗優化**：內建繁體中文、簡體中文及英文三種語系，隨系統語言自動切換，並加入精緻的自繪 UI 動畫特效。

### v2.2.1 更新內容
1.  **新增自訂進程**：可自行加入魔獸世界進程名稱（如 wowb、firestorm 等私服版本），解決部分版本抓不到遊戲視窗的問題。
2.  **極致效能最佳化**：全面優化掛機與視窗掃描的底層邏輯，大幅降低背景運作時的系統 CPU 佔用負擔。
3.  **全新任務視覺特效**：新增按鍵與懸浮窗在執行任務時的科技感動態光暈與掃描特效，狀態辨識更直覺。
4.  **修復掛機連動 Bug**：解決自動掛機時，若遊戲視窗被關閉，任務卻沒有連動停止的問題。
5.  **修復懸浮窗 Bug**：解決懸浮迷你視窗置頂狀態偶發不穩定的問題。

### v2.1.0 更新內容
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
    <img width="83" height="84" alt="2026-07-17_162752" src="https://github.com/user-attachments/assets/6162a579-a530-470b-bf27-82f4b1d3815e" />
3.  調整釣魚時間模式（連續或定時）。
4.  按下「釣魚快捷鍵」（預設 `Ctrl + F8`）正式啟動。
   
>  **釣魚注意事項**：
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

<br>

### 懸浮窗功能
<video src="https://github.com/user-attachments/assets/58fb90f6-7d3d-44ac-b2bb-f9d6f5836a6a"></video>

</details>

---

### 簡體中文 (Simplified Chinese)
<details>
 <summary>点击展开介绍 / Click to expand introduction</summary><br>

> 💻 **【系统环境需求】**
> 本程序基于 **.NET 10** 框架开发。若您的电脑尚未安装此环境，请无须担心！
> 首次开启程序时，系统会自动跳出安全提示，并无缝引导您前往微软官方完成一键下载与安装。
<br>

WowAutoAFK 是一款专为《魔兽世界》玩家设计的自动化辅助工具。本程序旨在协助玩家轻松处理自动登录、挂机防掉线以及自动钓鱼等日常事务，大幅减轻游戏中的重复性操作。

本项目采用 **C# (WPF/WinForms) 与 C++** 的混合架构设计，兼顾了「高效的界面开发」与「极致的核心运算性能」：
*   **前端 UI 层 (C#)**：利用 .NET UI 框架，建立直观、流畅且高响应性的用户界面与数据绑定。
*   **核心运算层 (C++)**：负责处理底层算法，确保执行效率，同时有效防止代码被轻易反编译。
*   **信息安全防护**：账号密码采用 Windows DPAPI 加密机制，确保您的账户信息安全无虞。

透过极简的现代化界面与深浅双色主题，WowAutoAFK 提供最直观的操作体验，让您彻底告别繁琐的刷怪与挂机动作！欢迎下载试玩（**强烈建议不要在官方正式服连续使用过长时间，以免增加封号的风险**）。

>   **注**：为防止有心人士恶意篡改程序获利，本项目采闭源 (Closed-Source) 发布。

---

##  核心特色 (Features)

*   **自动登录系统(Auto-login)**：支持账号密码加密存储与多账号管理，一键快速切换角色进入游戏。
*   **智能挂机多开后台防掉线(AFK in background & Multi-boxing)**：内置多种挂机频率与模式（如原地跳跃、随机动作），完全模拟真人按键操作。
*   **可视化自动钓鱼(Auto-fishing)**：利用精准的图像识别技术自动侦测浮标咬饵，支持收竿连击与防呆机制。
*   **无干扰后台运行**：挂机与登录功能全程可于后台运作（不含钓鱼），不影响您处理其他电脑作业。支持缩小至系统托盘与悬浮迷你窗口。
*   **各国用户体验优化**：内置繁体中文、简体中文及英文三种语系，随系统语言自动切换，并加入精致的自绘 UI 动画特效。

### v2.2.0 更新内容
1.  **新增自定义进程**：可自行加入魔兽世界进程名称（如 wowb、firestorm 等私服版本），解决部分版本抓不到游戏窗口的问题。
2.  **极致性能优化**：全面优化挂机与窗口扫描的底层逻辑，大幅降低后台运行时的系统 CPU 占用负担。
3.  **全新任务视觉特效**：新增按键与悬浮窗在执行任务时的科技感动态光晕与扫描特效，状态辨识更直观。
4.  **修复挂机联动 Bug**：解决自动挂机时，若游戏窗口被关闭，任务却没有联动停止的问题。
5.  **修复悬浮窗 Bug**：解决悬浮迷你窗口置顶状态偶发不稳定的问题。

### v2.1.0 更新内容
1.  **全新自绘 UI**：支持深色（雷蛇电竞风格）与浅色（清爽简约）双模式自由切换。
2.  **悬浮窗功能**：新增迷你悬浮窗口，状态监控更便利。
3.  **多开挂机支持**：挂机功能导入多线程运作，支持多开窗口同时挂机，动作与间隔时间互不冲突。
4.  **拟人化钓鱼操作**：钓鱼功能加入鼠标拟人轨迹，彻底告别容易被侦测的机器人瞬移光标。
5.  **挂机/钓鱼无缝协同**：当有多个挂机任务执行时，可随时指定其中一个窗口进行钓鱼，取消钓鱼后系统将无缝恢复挂机状态。

---

## 📖 详细使用教程 (Tutorial)

### 一、 首次环境设置
1.  **指定游戏路径**：开启程序后，于主界面「主程序路径」栏位，选择您的 `WoW.exe` 执行文件路径。
2.  **调整延迟参数**：在「登录动作延迟」区块，请根据您的电脑加载速度调整延迟秒数。
    > 💡 **提示**：建议设为 10-15 秒以上以确保加载稳定；若电脑配置较旧，请适度调高秒数。

### 二、 自动登录
1.  前往「账号登录」分页，输入游戏账号与密码后点击「保存账号」。
2.  在账号列表中按右键将该账号设为「默认」。
3.  确认游戏尚未开启，点击「自动登录游戏」，程序将自动启动游戏并完成密码输入。

### 三、 自动挂机
1.  前往「自动挂机」分页，在右侧的**游戏窗口列表**中勾选欲挂机的窗口（支持多开勾选）。
2.  设定「动作模式」（如：深度防掉线）与「动作频率」（如：原地跳跃）。
3.  按下设定好的「挂机快捷键」（默认 `Ctrl + F2`）即可快速启动或停止。

### 四、 自动钓鱼 (需保持游戏画面可见)
1.  前往「自动钓鱼」分页，设定对应游戏内的抛竿快捷键。
2.  点击「截取浮标图片」，画面将进入截图模式，请精准框选您的「钓鱼浮标」。
    *(示例图示如下)*<br>
    <img width="83" height="84" alt="2026-07-17_162752" src="https://github.com/user-attachments/assets/6162a579-a530-470b-bf27-82f4b1d3815e" />
3.  调整钓鱼时间模式（连续或定时）。
4.  按下「钓鱼快捷键」（默认 `Ctrl + F8`）正式启动。
   
>  **钓鱼注意事项**：
> * 为确保图像识别顺畅，钓鱼期间请避免操作键盘与鼠标，以免干扰程序判定。
> * 建议避免使用浮动较大或容易变形的特殊外观浮标，以免造成判定失误。

---

## ⚙️ 快捷键自定义 (Hotkeys)

您可以于「设置」分页自由更改挂机与钓鱼的触发快捷键。
*   **支持范围**：`Ctrl + F1` 至 `Ctrl + F9`。
*   **自动互斥机制**：系统内置防冲突保护，挂机与钓鱼无法同时在单一窗口启动（若在挂机中按下钓鱼快捷键，系统会自动中断挂机并切换至钓鱼）。

---

## 🛡️ 安全性、运行原理与免责声明 (Security & Disclaimer)

### ✅ 绝对无修改游戏内存 (Strictly NO Memory Modification)
本程序采用「纯外部视觉分析」与「系统底层硬件模拟」技术，**没有**也不会对游戏客户端进行任何危险的侵入性操作。
*   **❌ 不读写内存**：不会扫描或篡改游戏的 RAM 数据。
*   **❌ 不注入代码**：不会向游戏客户端注入任何外部 DLL 或恶意代码。
*   **❌ 不修改游戏文件**：不会更改任何游戏原始文件或拦截封包。
*   **⭕ 纯视觉识别**：完全依赖 OpenCV 进行屏幕截图与影像色彩分析判断浮标。
*   **⭕ 硬件级输入**：透过 Windows 底层 API 模拟真实键鼠信号，并加入随机延迟与拟人化轨迹。

### ⚠️ 风险提示与声明条款
**当您开启并使用本程序，即代表您已详阅并无条件同意以下所有声明与条款：**

1.  **封号风险**：尽管本程序在技术层面上避开了防作弊系统 (如 Warden) 的内存扫描，但使用任何第三方自动化工具依然违反《魔兽世界》的使用条款 (TOS)。若遭玩家举报或被系统行为分析判定异常，仍有账号被冻结的风险。（**官方正式服打击严格，强烈不建议于正式服长时间使用**）。玩家需自行评估并承担相关风险，开发者概不负责。
2.  **隐私与信息安全保证**：您的账号密码与个人设定仅会加密并存储于您的本机电脑中，本程序绝无且不会有任何回传或收集隐私的行为。
3.  **非商业用途**：本程序为免费工具，仅供个人便利与研究交流使用，严禁任何商业牟利行为。
4.  **软件来源与杀毒误报**：建议仅从此官方渠道下载本程序。本程序未经加壳，仅经过基本的代码混淆，经各大杀毒网站 (如 VirusTotal, Hybrid Analysis) 评测皆为安全，仅有极低概率会遭部分杀毒软件误报。若您从非官方渠道取得遭到恶意植入病毒的文件，开发者概不负责。

---

## 🎬 操作视频 (Demo)

### 界面功能展示
<video src="https://github.com/user-attachments/assets/680fd35b-023b-405b-8f8b-e20dc7274d1b"></video>

<br>

### 悬浮窗功能
<video src="https://github.com/user-attachments/assets/58fb90f6-7d3d-44ac-b2bb-f9d6f5836a6a"></video>

</details>

---

### English
<details>
 <summary>Click to expand introduction</summary><br>

> 💻 **【System Requirements】**
> This program is developed based on the **.NET 10** framework. If your PC doesn't have it installed yet, don't worry!
> Upon launching the program for the first time, a security prompt will appear, seamlessly guiding you to the official Microsoft website for a one-click download and installation.
<br>

WowAutoAFK is an automated assistant tool specifically designed for "World of Warcraft" players. This program aims to help players easily manage daily tasks such as auto-login, anti-AFK, and auto-fishing, significantly reducing repetitive actions in the game.

This project utilizes a **C# (WPF/WinForms) and C++** hybrid architecture, combining "highly efficient UI development" with "ultimate core computing performance":
*   **Frontend UI Layer (C#)**: Utilizes the .NET UI framework to create an intuitive, smooth, and highly responsive user interface with data binding.
*   **Core Computing Layer (C++)**: Handles underlying algorithms to ensure execution efficiency while effectively preventing the code from being easily decompiled.
*   **Security Protection**: Account passwords are encrypted using the Windows DPAPI mechanism, ensuring your account information is completely safe.

With a minimalist modern interface and a dual Dark/Light theme, WowAutoAFK provides the most intuitive user experience, allowing you to say goodbye to tedious grinding and AFK actions! Feel free to download and try it out (**strongly advised not to use it continuously for long periods on official retail servers to avoid the risk of account bans**).

>   **Note**: To prevent malicious tampering for profit, this project is released as Closed-Source.

---

##  Core Features

*   **Auto-login System**: Supports encrypted storage of account passwords and multi-account management, allowing one-click quick character switching and login.
*   **Smart Background Anti-AFK & Multi-boxing**: Built-in multiple AFK frequencies and modes (e.g., jumping in place, random actions), perfectly simulating real human keystrokes.
*   **Visual Auto-fishing**: Utilizes precise image recognition technology to automatically detect when a fish bites the bobber, supporting combo reeling and failsafe mechanisms.
*   **Interference-free Background Execution**: AFK and login functions can run entirely in the background (excluding fishing), without affecting your other computer tasks. Supports minimizing to the system tray and a floating mini-window.
*   **Global User Experience Optimization**: Built-in Traditional Chinese, Simplified Chinese, and English languages, automatically switching based on your system language, featuring exquisite custom-drawn UI animation effects.

### v2.2.0 Updates
1.  **Custom Processes**: Manually add WoW process names (e.g., wowb, firestorm for private servers) to fix window detection issues on specific versions.
2.  **Ultimate Performance Optimization**: Comprehensively optimized the underlying logic for AFK and window scanning, significantly lowering system CPU usage during background operations.
3.  **New Task Visual Effects**: Added sci-fi dynamic glowing and scanning effects to buttons and the floating window during active tasks for more intuitive status recognition.
4.  **AFK Linkage Bug Fix**: Resolved an issue where AFK tasks wouldn't automatically stop if the game window was closed.
5.  **Floating Window Bug Fix**: Fixed occasional instability with the floating mini-window's Always-on-Top status.

### v2.1.0 Updates
1.  **Redesigned UI**: Supports seamless switching between Dark mode (Razer gaming style) and Light mode (clean and simple).
2.  **Floating Window Feature**: Added a mini floating window for more convenient status monitoring.
3.  **Multi-boxing AFK Support**: Introduced multi-threading to the AFK function, supporting simultaneous AFK on multiple windows without conflicts in actions or intervals.
4.  **Humanized Fishing Operations**: Added human-like mouse trajectories to the fishing function, completely eliminating easily detectable robotic instant cursor snaps.
5.  **Seamless AFK/Fishing Synergy**: When multiple AFK tasks are running, you can designate one window for fishing at any time. After canceling fishing, the system seamlessly resumes the AFK state.

---

## 📖 Detailed Tutorial

### I. Initial Environment Setup
1.  **Specify Game Path**: After launching the program, in the "Path" field on the main interface, select the path to your `WoW.exe` executable.
2.  **Adjust Delay Parameters**: In the "Login Delay" section, please adjust the delay seconds according to your computer's loading speed.
    > 💡 **Tip**: Recommended to set above 10-15 seconds to ensure stable loading; slightly increase if you have an older PC.

### II. Auto-login
1.  Go to the "Auto Login" tab, enter your game account and password, and click "Save Account".
2.  Right-click on the account in the list to set it as "Default".
3.  Ensure the game is not running, click "Auto Login", and the program will automatically launch the game and complete the password input.

### III. Auto AFK
1.  Go to the "Auto AFK" tab, and check the window(s) you want to AFK in from the **Game Windows** list on the right (supports multi-boxing selection).
2.  Set the "Action Mode" (e.g., Deep Dive) and "Action Frequency" (e.g., Jump in place).
3.  Press your configured "AFK Hotkey" (Default: `Ctrl + F2`) to quickly start or stop.

### IV. Auto Fishing (Requires game screen to be visible)
1.  Go to the "Auto Fishing" tab and set the corresponding hotkey for your fishing skill in the game.
2.  Click "Capture Bobber", the screen will enter screenshot mode, please accurately box your "fishing bobber".
    *(Example image below)*<br>
    <img width="83" height="84" alt="2026-07-17_162752" src="https://github.com/user-attachments/assets/6162a579-a530-470b-bf27-82f4b1d3815e" />
3.  Adjust the fishing time mode (Continuous or Timed).
4.  Press your "Fishing Hotkey" (Default: `Ctrl + F8`) to start.
   
>  **Fishing Notes**:
> * To ensure smooth image recognition, avoid using the keyboard and mouse while fishing to prevent interfering with the program's detection.
> * It is recommended to avoid using special bobbers with large floating movements or easily deformable appearances to prevent false detections.

---

## ⚙️ Custom Hotkeys

You can freely change the trigger hotkeys for AFK and fishing in the "Settings" tab.
*   **Supported Range**: `Ctrl + F1` to `Ctrl + F9`.
*   **Auto-Mutex Mechanism**: Built-in conflict protection ensures AFK and fishing cannot be started simultaneously in a single window (pressing the fishing hotkey while AFK will automatically interrupt AFK and switch to fishing).

---

## 🛡️ Security, Operating Principles & Disclaimer

### ✅ Strictly NO Memory Modification
This program utilizes "pure external visual analysis" and "system-level hardware simulation" technology. It **does not** and will not perform any dangerous intrusive operations on the game client.
*   **❌ No Memory Reading/Writing**: Will not scan or tamper with the game's RAM data.
*   **❌ No Code Injection**: Will not inject any external DLLs or malicious code into the game client.
*   **❌ No Game File Modification**: Will not alter any original game files or intercept packets.
*   **⭕ Pure Visual Recognition**: Relies entirely on OpenCV for screenshots and image color analysis to detect the bobber.
*   **⭕ Hardware-level Input**: Simulates real keyboard and mouse signals via Windows underlying APIs, incorporating randomized delays and human-like trajectories.

### ⚠️ Risk Warning & Terms of Use
**By launching and using this program, you acknowledge that you have read and unconditionally agree to all the following statements and terms:**

1.  **Account Ban Risk**: Although this program technically bypasses memory scanning from anti-cheat systems (like Warden), using any third-party automation tool still violates the "World of Warcraft" Terms of Service (TOS). If reported by players or flagged by system behavior analysis, there is still a risk of account suspension. (**Official retail servers have strict enforcement; prolonged use on retail servers is strongly discouraged**). Users must evaluate and bear the associated risks themselves; the developer assumes no liability.
2.  **Privacy & Security Guarantee**: Your account passwords and personal settings are only encrypted and stored locally on your machine. This program absolutely does not and will never collect or transmit any privacy data.
3.  **Non-Commercial Use**: This program is a free tool provided solely for personal convenience and research exchange. Any form of commercial profiteering is strictly prohibited.
4.  **Software Source & Antivirus False Positives**: It is recommended to download this program only from this official channel. The program is unpacked and only undergoes basic code obfuscation. It has been tested safe by major virus scanning websites (e.g., VirusTotal, Hybrid Analysis), with only a very low probability of false positives by some antivirus software. The developer is not responsible if you obtain a file maliciously injected with a virus from an unofficial channel.

---

## 🎬 Demo Videos

### Interface Overview
<video src="https://github.com/user-attachments/assets/680fd35b-023b-405b-8f8b-e20dc7274d1b"></video>

<br>

### Floating Window
<video src="https://github.com/user-attachments/assets/58fb90f6-7d3d-44ac-b2bb-f9d6f5836a6a"></video>

</details>

---

## ☕ 贊助與專案資訊 (Support the Developer & Info)

如果您覺得這款軟體為您節省了大量時間，歡迎請開發者喝杯咖啡！您的支持是我們持續更新與優化工具的最大動力。 <br><br>
If this tool has saved you time, consider buying the developer a coffee! Your support is the greatest motivation for continuous updates and bug fixes.

💳 **贊助連結 (Donation Link)**：[點此透過 PayPal 贊助我 (Donate via PayPal)](https://www.paypal.com/ncp/payment/D7GSCCJEHTSFN)

### 專案資訊 (Project Information)：
*   **專案名稱 (Project Name)**：WowAutoAFK
*   **版本 (Version)**：v2.2.0
*   **開發者 (Developer)**：許耀庭 (HsuYaoTing)
*   **聯絡信箱 (Email)**：[speed132454@gmail.com](mailto:speed132454@gmail.com)
*   **微信 (WeChat)**：ting0427mei
*   **QQ**：744268839
*   **GitHub**：[https://github.com/yaotingshiu/WowAutoAFK_Releases](https://github.com/yaotingshiu/WowAutoAFK_Releases)

---
