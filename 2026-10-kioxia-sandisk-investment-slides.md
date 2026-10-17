---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #f8fafc
color: #0f172a
style: |
  section {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang TC", "Noto Sans TC", sans-serif;
    font-size: 26px;
    line-height: 1.6;
    padding: 50px 70px;
  }
  h1 {
    color: #1e3a8a;
    font-size: 44px;
    font-weight: 800;
    margin-bottom: 20px;
  }
  h2 {
    color: #2563eb;
    font-size: 36px;
    font-weight: 700;
    margin-bottom: 24px;
  }
  .stat-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    margin-top: 20px;
  }
  .stat-card {
    background: #ffffff;
    border: 2px solid #e2e8f0;
    border-radius: 16px;
    padding: 24px 16px;
    text-align: center;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
  }
  .stat-label {
    font-size: 18px;
    font-weight: 700;
    color: #2563eb;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  .stat-num {
    font-size: 42px;
    font-weight: 900;
    color: #0f172a;
    margin: 10px 0;
  }
  .stat-desc {
    font-size: 17px;
    color: #64748b;
  }
  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
  }
  .card {
    background: #ffffff;
    border: 2px solid #e2e8f0;
    border-radius: 14px;
    padding: 22px 24px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.04);
  }
  .card strong {
    font-size: 24px;
    color: #0f172a;
    display: block;
    margin-bottom: 8px;
  }
  .card p {
    font-size: 21px;
    color: #334155;
    margin: 0;
    line-height: 1.5;
  }
  .callout {
    background: #eff6ff;
    border-left: 6px solid #2563eb;
    padding: 18px 24px;
    border-radius: 0 12px 12px 0;
    font-size: 22px;
    color: #1e3a8a;
    margin-top: 24px;
  }
  .badge {
    display: inline-block;
    padding: 4px 12px;
    border-radius: 999px;
    font-size: 18px;
    font-weight: 700;
  }
---

# 鎧俠 × 閃迪：5 兆日圓超級擴產
## 未來 6 年 NAND Flash 增產與 AI 儲存布局

**Brief 獨立產業調查** · 新聞事件日期：2026-08-27

<!-- 
講者筆記：
大家好，今天為大家解析美日記憶體雙雄鎧俠與閃迪公布的 5 兆日圓超級增產計畫。
-->

---

## 核心數據速覽 (Key Figures)

雙方宣布至 **2032 財年**（約 6 年內）共同投資逾 **5 兆日圓**。

<div class="stat-grid">
  <div class="stat-card">
    <div class="stat-label">總投資額</div>
    <div class="stat-num">¥5 兆</div>
    <div class="stat-desc">約 310~330 億美元</div>
  </div>
  <div class="stat-card">
    <div class="stat-label">投資跨度</div>
    <div class="stat-num">6 年</div>
    <div class="stat-desc">至 2032 財年止</div>
  </div>
  <div class="stat-card">
    <div class="stat-label">出資比例</div>
    <div class="stat-num">60 : 40</div>
    <div class="stat-desc">鎧俠 60% · 閃迪 40%</div>
  </div>
  <div class="stat-card">
    <div class="stat-label">北上 K3 廠</div>
    <div class="stat-num">¥1.8 兆</div>
    <div class="stat-desc">專攻 AI 3D NAND</div>
  </div>
</div>

<div class="callout">
  💡 <strong>先決條件：</strong>此項天價投資<strong>高度取決於日本政府（經產省 METI）之財政補貼到位情況</strong>。
</div>

---

## 5W1H 新聞核心要素

<div class="grid-2">
  <div class="card">
    <strong style="color:#2563eb;">What · 核心事件</strong>
    <p>美日雙雄聯手啟動 5 兆日圓超級擴產，全面拉升先進 3D NAND Flash 晶圓產能。</p>
  </div>
  <div class="card">
    <strong style="color:#2563eb;">Who · 主導者</strong>
    <p>鎧俠 (Kioxia) ＋ 閃迪 (SanDisk)，合作逾 25 年的合資盟友，協議已延至 2034 年。</p>
  </div>
  <div class="card">
    <strong style="color:#2563eb;">Where · 兩大基地</strong>
    <p>岩手縣北上市（專攻 AI 資料中心） ＆ 三重縣四日市（全球產能基石）。</p>
  </div>
  <div class="card">
    <strong style="color:#2563eb;">Why · 投資動機</strong>
    <p>生成式 AI 爆發，推論與雲端快取對低延遲、高容量企業級 SSD 需求激增。</p>
  </div>
</div>

---

## 雙基地產能分工與技術藍圖

<div class="grid-2">
  <div class="card" style="border-color:#2563eb;">
    <strong style="color:#1e3a8a;">🏭 岩手縣北上廠 (Kitakami)</strong>
    <p>
      • <strong>投資 1.8 兆日圓</strong>興建全新 K3 廠房（Fab 3）<br>
      • 預計於 <strong>2029 財年</strong>正式商用量產<br>
      • 生產第十代及次世代 <strong>BiCS FLASH™</strong>（高堆疊）<br>
      • 專攻 AI 訓練/推論資料中心與企業級 SSD
    </p>
  </div>

  <div class="card" style="border-color:#64748b;">
    <strong style="color:#334155;">🏭 三重縣四日市廠 (Yokkaichi)</strong>
    <p>
      • 全球最大規模 NAND 快閃記憶體製造聚落之一<br>
      • 持續進行既有巨型廠區之製程升級與設備更新<br>
      • 成熟與先進並進，主力供應智慧手機與 PC<br>
      • 提供龐大基底產能，平衡消費性市場週期
    </p>
  </div>
</div>

---

## 為什麼現在砸 5 兆？三大核心戰略

1. **AI 儲存典範轉移**
   大模型不僅需要昂貴的 HBM，訓練資料載入與推論快取更需要**巨量高速快閃記憶體**。

2. **美日半導體同盟與政策補貼**
   借力日本經產省（METI）將記憶體列為「特定高度情報技術」之戰略補貼，大幅降低建廠成本。

3. **全球寡佔三強保衛戰**
   對抗南韓三星電子與 SK 海力士，並在 3D 堆疊層數（300+ 層）上拉開與中國長江存儲（YMTC）之技術差距。

---

## 潛在挑戰與四大風險

<div class="grid-2">
  <div class="card" style="border-left: 6px solid #ef4444;">
    <strong>⚠️ 景氣循環劇烈波動</strong>
    <p>若 AI 資料中心支出於 2027~2028 年放緩，2029 年開出之新產能恐面臨降價與供過於求風險。</p>
  </div>
  <div class="card" style="border-left: 6px solid #f59e0b;">
    <strong>🏛️ 政府財政補貼變數</strong>
    <p>官方註明「視政府補貼而定」。面對 Rapidus 與台積電熊本廠分食預算，最終核撥金額仍有變數。</p>
  </div>
  <div class="card" style="border-left: 6px solid #3b82f6;">
    <strong>📈 鎧俠財務槓桿與 IPO</strong>
    <p>鎧俠負債比率較高，60% 資本支出高度考驗其東京證交所（TSE）IPO 進度與融資能力。</p>
  </div>
  <div class="card" style="border-left: 6px solid #64748b;">
    <strong>🤝 合資架構與分拆整合</strong>
    <p>威騰電子推動閃迪分拆獨立，雙方在經營自主權與產能分配上需維持長遠協調。</p>
  </div>
</div>

---

## 後續產業觀察指標

- [ ] **北上 K3 廠房動土與環評**：預計 2026 下半年 ~ 2027 年啟動
- [ ] **日本經產省（METI）補貼核定**：關注官方審批補助具體金額
- [ ] **次世代 BiCS FLASH™ 技術認證**：關注 300+ 層技術進展
- [ ] **鎧俠 IPO 上市申請**：攸關 3 兆日圓自籌款項落實

---

<!-- _class: lead -->

# Q & A

**Brief 獨立產業事實梳理**

[📄 閱讀完整調查報告](2026-10-kioxia-sandisk-investment.html) · [📋 返回 Brief 首頁](index.html)
