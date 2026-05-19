# Bioinformatics Interactive Tutorial

**🌐 Live demo / 線上瀏覽**: <https://charlene717.github.io/bioinformatics-interactive-tutorial/>


互動式生物資訊教學站，涵蓋 5 大體學分析主題，共 25 章 + 1 個主入口頁。

## 主題與架構

```
bioinformatics-interactive-tutorial/
├── index.html              # 主入口（Hub）
├── styles.css              # 共用樣式（含 5 種 track 主題色）
├── i18n.js                 # 中英雙語切換邏輯
├── README.md
│
├── bulk-rnaseq/            # Track 1：Bulk RNA-seq（7 章）
│   ├── index.html
│   ├── qc-trim.html        # 1. QC 與 Trimming
│   ├── alignment.html      # 2. Alignment
│   ├── quantification.html # 3. Quantification
│   ├── normalization.html  # 4. Normalization
│   ├── de.html             # 5. DE 分析
│   ├── visualization.html  # 6. 視覺化
│   └── gsea.html           # 7. GSEA / 功能富集
│
├── spatial/                # Track 2：Spatial Transcriptomics（5 章）
│   ├── index.html
│   ├── platforms.html      # 1. 平台與技術
│   ├── preprocessing.html  # 2. Loading & QC
│   ├── spatial-analysis.html # 3. 聚類與 SVG
│   ├── deconvolution.html  # 4. Deconvolution
│   └── interactions.html   # 5. 細胞通訊
│
├── atac-seq/               # Track 3：ATAC-seq / Epigenomics（4 章）
│   ├── index.html
│   ├── principles.html     # 1. 原理與片段分佈
│   ├── alignment-peaks.html # 2. Alignment & Peaks
│   ├── motif.html          # 3. Motif & Footprinting
│   └── integration.html    # 4. 多體學整合
│
├── variant/                # Track 4：Variant Calling（5 章）
│   ├── index.html
│   ├── preprocessing.html  # 1. Read 預處理
│   ├── calling.html        # 2. Variant Calling
│   ├── filtering.html      # 3. Filtering
│   ├── annotation.html     # 4. Annotation
│   └── sv-cnv.html         # 5. SV / CNV
│
└── microbiome/             # Track 5：Microbiome（3 章）
    ├── index.html
    ├── amplicon.html       # 1. 16S Amplicon
    ├── metagenomics.html   # 2. Shotgun Metagenomics
    └── function.html       # 3. Functional Profiling
```

## 功能

- **中英雙語切換**：右上角「中文 / EN」按鈕，偏好記錄於 localStorage
- **R / Python 雙程式碼分頁**：每章皆附對應實作範例
- **互動模擬（Chart.js）**：滑桿即時更新統計與視覺化
- **決策樹**：實務情境下的工具選擇引導
- **Quiz 自我檢測**：每章附 1-2 題即時回饋
- **進度條**：閱讀進度顯示

## 使用方式

1. 用瀏覽器開啟 `index.html` 進入主入口
2. 選擇感興趣的 Track 進入主題章節
3. 章節內以「上一步 / 下一步」串聯閱讀

## 設計

- **配色**：每個 Track 有獨特主題色
  - Bulk RNA-seq：藍 `#1a5e8a`
  - Spatial：紫 `#7a4eb5`
  - ATAC-seq：橙 `#c66a1e`
  - Variant：紅褐 `#a33c34`
  - Microbiome：青綠 `#2d8b6e`
- **字體**：Crimson Pro（標題）、DM Sans（內文）、JetBrains Mono（程式碼）
- **沿用** scRNA-seq Interactive Tutorial 的整體設計語彙

## 關聯站台

姊妹站：scRNA-seq Interactive Tutorial — 單細胞 RNA-seq 完整流程。
