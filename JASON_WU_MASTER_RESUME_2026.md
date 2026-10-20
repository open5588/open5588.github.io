# 吳昀融 (Jason Wu / Yun-Rong Wu) — 10+ 年資深企業級 ERP / WMS 架構師、跨平台 App / Windows 系統與全端 AI 工程師履歷

![Jason Wu — Principal ERP, WMS & Full-Stack Systems Architect](/Users/jasonwu/.gemini/antigravity/brain/d7a0cee3-1cd2-46ad-abd4-08601a575f57/jason_wu_retouched_headshot_1792405096010.jpg)

- **聯絡信箱**：`open5588@gmail.com`
- **GitHub**：[`github.com/open5588`](https://github.com/open5588) ‧ `jasonw5588`
- **Upwork 國際認證履歷**：[`upwork.com/freelancers/~0159c00273dd3bd644`](https://www.upwork.com/freelancers/~0159c00273dd3bd644)
- **Freelancer 國際接案檔案**：[`freelancer.com/u/jasonwu5588`](https://www.freelancer.com/u/jasonwu5588)
- **線上互動作品集與架構展示站**：[`portfolio.html`](https://utils-keno-instrument-involved.trycloudflare.com/portfolio.html) ‧ [`retainer.html`](https://utils-keno-instrument-involved.trycloudflare.com/retainer.html)
- **自營電商與軟體品牌官網群**：
  - **昀美好批 / 超級好批發商城**：[`https://ezp.com.tw`](https://ezp.com.tw)
  - **昀美生活電商**：[`https://ymshop.com.tw`](https://ymshop.com.tw)
  - **禮你客製禮品商城**：[`https://giftyou.com.tw`](https://giftyou.com.tw)
  - **優爾商城多租戶電商 SaaS**：[`https://urstore.tw`](https://urstore.tw)
  - **自營品牌與 App 應用總站**：[`https://urhand.net`](https://urhand.net)
  - **CelerCam 低延遲 OBS 攝影機系統**：[`https://celercam.com`](https://celercam.com)
  - **CelerCast 教室/區網即時廣播系統**：[`https://celercast.celercam.com`](https://celercast.celercam.com)
  - **Skywave 跨平台遠端桌面系統**：[`https://skywavedesk.com`](https://skywavedesk.com)

---

## 🇬🇧 PART 1: ENGLISH MASTER RESUME (For US / UK / EU / Global Clients & Contracts)

### Executive Summary
**Principal Enterprise ERP / WMS Architect, Cross-Platform App Developer & Full-Stack AI Systems Engineer** with **10+ years of hands-on production experience**. Career grounded in architecting and maintaining mission-critical North American and APAC supply-chain **ERP systems (`CAP ERP`, `PBSC`, `T2 / Trucking2000`)**, multi-warehouse **WMS platforms (`TransloadWMS`, `YMSaas`, `YMSystem`)**, **published iOS App Store & Google Play enterprise apps** (T2 Fleet Driver App & Warehouse Barcode PDA Scanner Apps), **native Windows (`.dll` / `.msi` / C# / C++) & macOS desktop engines (`CelerCam`, `CelerCast`, `Skywave`, `PunchHub`)**, and **5 live revenue-generating B2B/B2C e-commerce platforms (`ezp.com.tw`, `ymshop.com.tw`, `giftyou.com.tw`, `urstore.tw`, `urhand.net`)**.

### Core Technical Stack
- **Enterprise ERP, Backend & Windows Systems**: C# / .NET Framework / .NET 8 / .NET 10, ASP.NET, WinForms/WPF, Windows Native DLLs & MSI Packaging, T-SQL / Microsoft SQL Server, PostgreSQL, EDI (810 / 820 / 846 / 856), Node.js (NestJS / Express), Python (FastAPI / Playwright), Go, Rust, Elixir.
- **Frontend & E-Commerce**: React 19, Next.js 15, TypeScript, Material UI (`@mui/x-data-grid`), PHP 8, Laravel, OpenCart 3 (Journal3), Shopify Plus, WooCommerce, REST & GraphQL APIs.
- **Mobile Apps (iOS App Store & Google Play Published)**: React Native (Bare & Expo, TypeScript), Native iOS (Swift / Xcode), Native Android (Kotlin / Java), Flutter, Capacitor, PDA Hardware Barcode/QR Scanners & Custom Camera OCR Overlays.
- **Streaming, Remote Desktop & AI Automation**: WebRTC, Custom Binary Wire Protocols (`FVEA`), OBS Studio Native Plugins (Windows/macOS), WebSockets (`wss://` Relay), n8n, Google Gemini / Anthropic Claude / OpenAI Agents, Microsoft Graph Teams Bots, Docker Swarm & Azure/AWS/Cloudflare.

---

### Professional Experience & Flagship Production Systems

#### 1. Enterprise ERP & Supply Chain Systems (10+ Years — `CAP`, `PBSC`, `T2`)
- **CAP Enterprise ERP (`CAP 2.0` & `CAP 2.5` — C# / .NET Enterprise ERP)**:
  - **Sales & Retail Order Management**: Developed and maintained `SalesOrder` (2.5), `SalesGPMaintenance`, `GPProposal`, `PricePreference`, `InternalQuoteSheet4Amazon`, `RetailOrder`, Walmart Fill-Rate reporting (`WmtFillRateReport`), `OrderExpeditor`, and `OrderTrackingII`.
  - **Procurement & Factory Management**: Built and maintained `PoFlow`, `PoStatusII` (linked with US WMS Receiving Scans), Factory PO (`FpoStatusII`), automated replenishment (`AutoPO` / `WDP`), `PurchaseOrder` (2.5), and `FactoryContract` / `EstimateLandingCost`.
  - **Inventory & Warehouse Allocation**: Maintained `InventoryMgmt` (2.0 & 2.5), `InventoryFeeder`, `InventorySales` allocation/inbound tracking, `SlowMovingItemMgr`, and `ContainerUnload`.
  - **Finance, AP/AR & EDI Integration**: Developed `ARSummary` (2.5), Cash Receipt & Claim Logs, Export/Factory/Trading Invoicing (`BOLAutoInvoice`), **EDI 810 / 820 / 846 / 856** document integration, `TaxRebateRateMgmt`, `RoyaltyFee`, and `ChartOfAccount`.
  - **Logistics, Customs & Barcode Labeling**: Built `BolStatus` (2.0 & 2.5), `ShippingLabel` (Amazon Direct Import Labels & Carton SSCC Barcode Labels for US distribution centers), `PackingList`, `PickingTicket`, `TruckLoad`, `OceanFreight`, and `CustomClearance`.
  - **Enterprise Middleware & Internal Tools**: Built **`CapSso`** (TypeScript Enterprise Single Sign-On), **`YAEP.TeamsBot.Core`** (.NET 8/10 Microsoft Graph Teams Bot on Docker), **`AmazonFulfillmentPerformanceReport`**, and **`AmazonBestSeller`** tracking tools.
- **PBSC Supply-Chain ERP Modernization (`PBSC_Rebuild`)**:
  - Re-architected core enterprise **Sales Agreement (`SA`)**, **Inventory**, and **Sales Order (`SO`)** workflows from legacy architecture into a high-performance **React + .NET 8 + T-SQL (SQL Server)** platform serving multi-state US distribution centers (GA, TX, NJ, MN).
- **T2 Intermodal & Drayage Trucking ERP (`Trucking2000` / `Heptarun` / `HeptarunPortal`)**:
  - Architected and maintained full-lifecycle US container drayage and trucking dispatch ERP (C#/.NET, SQL Server, EDI, GPS telemetry, and automated ocean carrier container tracking via `ContainerTrackerAPI`).
  - Integrated **n8n + Google Gemini AI** automated email ingestion (`T2 Email ImportOrder`) that parses customer PDF Delivery Orders (`DO`) and Bills of Lading (`BOL`) directly into structured T2 dispatch orders every hour.

#### 2. WMS (Warehouse Management Systems) & Published T2 / WMS Mobile Apps
- **Published Enterprise T2 & WMS Mobile Apps (iOS App Store & Google Play)**:
  - **WMS Warehouse PDA & Barcode Scanner App (`WmsApp` / `YMWMS` & US DC WMS App — React Native + TypeScript)**: Designed and shipped the production mobile warehouse app used on the warehouse floor for **Inbound Receiving (`入庫收貨`)**, **QC Inspection (`驗貨`)**, **Bin Putaway (`歸位`)**, **Real-Time Stock Lookup (`庫存查詢`)**, **Wave Picking (`揀貨`)**, and **Outbound Shipping (`出貨`)**.
  - **T2 Fleet & Driver Dispatch App (`DriverTasker` / T2 Mobile App — Native iOS Swift & Android)**: Built and published the mobile driver app featuring real-time dispatch tasking, custom camera overlay (`CameraOverlayController`) for container/chassis/seal OCR scanning, GPS route telemetry, and electronic Proof of Delivery (POD).
- **YMSaas & YMSystem (`open5588/YMSaas`, `open5588/YMSystem`)**:
  - Architected a multi-tenant Cloud WMS & ERP SaaS platform (**NestJS + Next.js + React Native + C#/.NET**) enabling 3PLs and wholesale merchants to manage multi-warehouse inventory, barcode slotting, and automated order fulfillment.
- **T2 Transload WMS (`TransloadWMS` / `t2-wms-transload-ui`) & Windows C# Warehouse Suite**:
  - Built the React 19 + MUI X DataGrid v8 cross-docking & container transloading web portal (`_apiin`, `_apiputaway`, `_apiout`, `_apicheck`).
  - Developed Windows C#/.NET desktop utilities **`WMSLocationImporter`** (bulk Excel-to-WMS database Area/Bin/Slot provisioning, Distribution Center creation wizard, and warehouse layout cloner) and **`WMSQrBook`** (end-to-end warehouse Rack & OpenArea QR Code Book generator).

#### 3. Windows Native Systems (`.dll` / `.msi`), Cross-Platform Desktop & Published Apps
- **[CelerCam (`https://celercam.com`)](https://celercam.com)** — **Published on Google Play (`app.celercam`) & iOS App Store Connect**:
  - Engineered an ultra-low-latency smartphone-to-OBS Studio camera system combining a mobile streaming app with a custom native **Windows (`celercam.dll`) & macOS OBS Studio Plugin** over a proprietary `FVEA` binary wire protocol.
- **[CelerCast (`https://celercast.celercam.com`)](https://celercast.celercam.com)** — **Windows (`.msi`) & macOS (`.dmg`) Broadcast Suite**:
  - Built a real-time classroom and LAN multi-room audio/video broadcast system in Go & WebRTC/FVEA with signed macOS `.dmg` and Windows x64 `.msi` installers and a browser-based group matrix console.
- **[Skywave & HeptaDesk (`https://skywavedesk.com`)](https://skywavedesk.com)** — **Cross-Platform Remote Desktop Engine**:
  - Developed a low-latency remote desktop client and host across **Windows, macOS, iOS, and Android** backed by custom `wss://` relay infrastructure (`relay.skywavedesk.com`).
- **PunchHub (`jasonw5588/punchhub`) — Windows/Web Hardware Attendance Gateway**:
  - Built a modern replacement for legacy C# Chiyu card-reader SDKs to ingest real-time biometric/RFID employee clock-in events across offices and warehouses.
- **[Osprey SMS Gateway (`https://osprey-sms.pages.dev`)](https://osprey-sms.pages.dev)** — **Android Enterprise SMS Gateway & AI Router**.
- **TripleK & Taiwan Quant Swing (`open5588/TripleK`, `TripleK_iOS`, `taiwan-quant-swing`)**:
  - All-in-one US & Taiwan stock institutional chip and K-Line quantitative analysis app (Python FastAPI + SQLite + ML Ensemble + iOS/Android).
- **Published iOS App Store & Google Play Games (`urhand.net`)**:
  - **[Spirit Island Defense 靈島守望 (`https://spiritisland.urhand.net`)](https://spiritisland.urhand.net)** — Published on iOS App Store (`id6800583840`) & Google Play.
  - **[Cat Move 喵屋搬搬樂 (`https://catmove.urhand.net`)](https://catmove.urhand.net)** & **[BrainBridge 腦力旅伴 (`https://brainbridge.urhand.net`)](https://brainbridge.urhand.net)** (Flutter).

#### 4. YunMei (昀美國際) Live E-Commerce & AI Live-Commerce Ecosystem (5 Production Sites)
- **[昀美好批 / 超級好批發商城 (`https://ezp.com.tw`)](https://ezp.com.tw)**:
  - Architected and operate the flagship B2B/B2C wholesale and group-buying platform (`ezp.com.tw` / `ezp_new`), integrated with **`ezp-live-ai`** (end-to-end AI product background removal, lifestyle poster generation, Taiwanese-accent TTS voice cloning, AI digital-human livestream host & OBS/Shopee Live RTMP automation) and **`auto-inquiry` / `auto-outreach`** automated vendor/buyer pipelines.
- **[昀美生活 (`https://ymshop.com.tw`)](https://ymshop.com.tw)**:
  - Full-stack B2C lifestyle retail e-commerce platform (PHP / OpenCart 3.0.6 / MySQL) synchronized with YMSaas WMS inventory, Taiwan payment gateways, and convenience-store/home-delivery logistics.
- **[禮你客製禮品 (`https://giftyou.com.tw`)](https://giftyou.com.tw)**:
  - Custom corporate gifting and promotional merchandise e-commerce platform (`giftyou.com.tw` + `giftyou-mkt`) featuring B2B volume pricing tiers and automated quote generation.
- **[優爾商城 SaaS (`https://urstore.tw`)](https://urstore.tw)**:
  - Multi-tenant e-commerce SaaS platform (`urstore-saas` backend + `urstore-shop` storefront) with automated Shopee catalog import (`SHOPEE_IMPORT_PLAN`), multi-vendor order routing, and cloud deployment.
- **[自營品牌與應用總站 (`https://urhand.net`)](https://urhand.net)**:
  - Unified brand and digital product portal hosting official product websites, support centers, and store compliance portals.

---

## 🇹🇼 PART 2: 中文完整履歷（10+ 年 ERP / WMS / 雙平台 App / Windows 系統 / 昀美電商生態系）

### 個人簡介
擁有 **10 年以上企業級大型系統研發與架構實戰經驗**。由跨國供應鏈與物流 **ERP 系統（`CAP ERP`、`PBSC`、`T2 / Trucking2000`）** 及 **WMS 倉儲管理系統** 起家，具備從底層資料庫（SQL Server / T-SQL / PostgreSQL）、Windows 原生桌面端與硬體串接（C# / .NET / C++ `.dll` / `.msi`）、Web 前後端（React / Next.js / NestJS / PHP / Python FastAPI），到 **iOS App Store 與 Google Play 雙平台實際上架 App**（T2 司機派車 App、WMS 條碼掃描倉儲 App、CelerCam 等 10+ 款應用）的一條龍獨立開發與架構能力；同時獨立打造並營運 **昀美國際旗下 5 大線上電商與 SaaS 平台（昀美好批 `ezp.com.tw`、昀美生活 `ymshop.com.tw`、禮你 `giftyou.com.tw`、優爾商城 `urstore.tw`、`urhand.net`）**。

### 四大核心實戰領域總覽

1. **10+ 年企業級 ERP 與跨國物流系統開發（`CAP` ‧ `PBSC` ‧ `T2`）**
   - **CAP 企業級 ERP 系統（`CAP 2.0` / `CAP 2.5`，C# / .NET 企業核心模組）**：
     - 參與開發與維護銷售（批發/零售訂單、GP 報價、Walmart FillRate 達成率報表、訂單催辦與追蹤）、採購（PO/FPO 工廠採購流、AutoPO 自動採購、到岸成本估算）、庫存（多倉調撥、供料政策、貨櫃卸貨）、財務與 EDI（AR/AP、出口/工廠發票、**EDI 810/820/846/856** 串接、退稅與權利金）、物流出貨（BOL 提單狀態、Amazon DI 出貨標籤與 Carton SSCC 條碼標籤、海運費、報關管理）等核心模組。
     - 開發企業週邊系統：**`CapSso`**（企業單一登入系統）、**`YAEP.TeamsBot.Core`**（.NET 8/10 Microsoft Graph Teams 自動推播服務）、**`AmazonFulfillmentPerformanceReport`** 與 **`AmazonBestSeller`** 數據分析工具。
   - **PBSC 核心 ERP 現代化重構（`PBSC_Rebuild`）**：
     - 以 **React + .NET 8 + T-SQL (SQL Server)** 重新打造企業級 SA（Sales Agreement）、Inventory（庫存）與 SO（Sales Order）核心系統，支援美國多州物流中心（GA、TX、NJ、MN）高併發作業。
   - **T2 美國貨櫃運輸與車隊派遣 ERP（`Trucking2000` / `Heptarun` / `HeptarunPortal`）**：
     - 負責美國內陸貨櫃拖車（Drayage）、車隊派工、EDI 交換、船公司貨櫃追蹤（`ContainerTrackerAPI`），並整合 **n8n + Google Gemini AI** 自動解析客戶 Email 中的 DO（提貨單）/ BOL PDF 自動建單。

2. **WMS 倉儲管理系統與雙平台實際上架 App（`T2` ‧ `WMS` ‧ `YMSaas`）**
   - **實際上架之 T2 與 WMS 企業行動 App（iOS App Store & Google Play）**：
     - **WMS 倉儲條碼掃描 App（`WmsApp` / `YMWMS` 及美國倉 WMS App — React Native + TypeScript）**：支援 PDA 與手機端硬體掃碼，完整涵蓋 **入庫收貨、驗貨、儲位歸位（Putaway）、即時庫存查詢、波次揀貨（Picking）與出貨作業**。
     - **T2 司機派工與車隊管理 App（`DriverTasker` / T2 Driver App — iOS Swift 原生 & Android）**：提供司機即時接單派工、自訂相機疊層（`CameraOverlayController`）掃描貨櫃號/封條/提單 OCR、GPS 軌跡回傳與電子簽收（POD）。
   - **YMSaas / YMSystem 多租戶雲端倉儲平台**：以 **NestJS + Next.js + React Native + C#/.NET** 打造之多租戶 SaaS 倉儲管理系統。
   - **T2 轉運倉儲系統（`TransloadWMS` / `t2-wms-transload-ui`）與 Windows 倉儲工具群**：
     - 以 React 19 + MUI X DataGrid 打造跨倉轉運（Transload）作業介面；並以 C# 開發 Windows 桌面工具 **`WMSLocationImporter`**（Excel 批次匯入 Area/Bin/Slot 儲位資料庫、新建 DC 精靈、倉庫複製工具）與 **`WMSQrBook`**（貨架 Rack / 開放區 OpenArea QR Code 清冊自動產生器）。

3. **Windows 桌面原生系統（`.dll` / `.msi`）、跨平台遠端桌面與上架 App 產品群**
   - **[CelerCam (`celercam.com`)](https://celercam.com)**：Google Play 已正式上架（`app.celercam`）＋ iOS 版，搭配自研 **Windows (`celercam.dll`) 與 macOS 原生 OBS Studio 插件**（採用自訂 `FVEA` 低延遲通訊協定），將手機變為專業導播攝影機。
   - **[CelerCast (`celercast.celercam.com`)](https://celercast.celercam.com)**：跨平台教室/區網低延遲影音廣播與中控矩陣系統（Go + **Windows x64 `.msi` 與 macOS `.dmg` 安裝包**）。
   - **[Skywave / HeptaDesk (`skywavedesk.com`)](https://skywavedesk.com)**：跨平台（Windows / macOS / iOS / Android）高速遠端桌面系統與自建 `wss://` 中繼伺服器。
   - **PunchHub (`punchhub`)**：取代舊版 C# SDK 之 Chiyu 門禁卡機打卡接收與考勤中台系統。
   - **[Osprey 魚鷹 (`osprey-sms.pages.dev`)](https://osprey-sms.pages.dev)**（Android 企業簡訊閘道）、**TripleK 三合一台美股籌碼 K 線 App**（FastAPI + SQLite + iOS/Android）、**台股波段量化交易系統 v11 (`taiwan-quant-swing`)**。
   - **iOS App Store / Google Play 自研遊戲與益智應用**：**[靈島守望 (`spiritisland.urhand.net`)](https://spiritisland.urhand.net)**（iOS App Store 已正式上架 `id6800583840`）、**[喵屋搬搬樂 (`catmove.urhand.net`)](https://catmove.urhand.net)**、**[腦力旅伴 BrainBridge (`brainbridge.urhand.net`)](https://brainbridge.urhand.net)**。

4. **昀美國際（YunMei）5 大線上電商平台與 AI 自動直播帶貨生態系**
   - **[昀美好批 / 超級好批發商城 (`https://ezp.com.tw`)](https://ezp.com.tw)**：B2B/B2C 禮品百貨批發商城，整合自研 **`ezp-live-ai`**（AI 商品去背、情境海報生成、台灣口音 TTS、AI 真人數位分身主播與 OBS/蝦皮直播自動化推流）及 **`auto-inquiry` / `auto-outreach`** 自動化詢價開發系統。
   - **[昀美生活 (`https://ymshop.com.tw`)](https://ymshop.com.tw)**：B2C 品牌零售電商網站（串接金流、超商/宅配物流與 WMS 庫存同步）。
   - **[禮你客製禮品 (`https://giftyou.com.tw`)](https://giftyou.com.tw)**：企業客製化禮贈品電商平台与自動化階梯報價系統。
   - **[優爾商城 SaaS (`https://urstore.tw`)](https://urstore.tw)**：多租戶電商開店 SaaS 平台（`urstore-saas` 後台 + `urstore-shop` 前台，支援蝦皮賣場商品一鍵匯入）。
   - **[自營品牌與應用總站 (`https://urhand.net`)](https://urhand.net)**：旗下數位產品、App 與手遊官方入口網站。
