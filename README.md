# PChome Product Scraper

使用 Python 與 Streamlit 建立的 PChome 商品資料蒐集與價格分析系統，可依照關鍵字或商品類別取得商品資料，並進行價格統計、折扣分析、資料視覺化及商品比較。

## 專案功能

- 依照關鍵字搜尋 PChome 商品
- 支援 PChome 特設商品分類
- 自訂商品資料抓取數量
- 顯示商品名稱、品牌與價格
- 計算平均價格、最高價格與最低價格
- 計算價格中位數與標準差
- 商品價格區間分類
- 原價與特價比較
- 折扣商品排行榜
- 商品自選與價格比較
- 商品價格篩選與排序
- 匯出 CSV 資料
- Streamlit 互動式網頁介面

## 資料處理流程

```text
輸入商品關鍵字或選擇分類
          ↓
呼叫 PChome 商品搜尋資料
          ↓
解析商品名稱、價格與品牌
          ↓
使用 pandas 清洗與整理資料
          ↓
計算價格統計與折扣資訊
          ↓
使用 Plotly 建立互動式圖表
          ↓
使用 Streamlit 顯示分析結果
```

## 使用技術

- Python
- Streamlit
- requests
- pandas
- Plotly
- PChome 商品搜尋資料
- 資料清洗
- 資料視覺化
- CSV 匯出

## 視覺化功能

- 商品價格趨勢折線圖
- 價格區間長條圖
- 價格區間圓餅圖
- 價格旭日圖
- 商品價格散佈圖
- 原價與特價比較圖
- 折扣幅度分布圖
- 自選商品價格比較圖

## 專案檔案

```text
pchome-product-scraper/
├── requirements.txt
├── streamlit_app.py
└── README.md
```

## 執行方式

### 1. 下載專案

```bash
git clone https://github.com/st3325228228-cpu/pchome-product-scraper.git
cd pchome-product-scraper
```

### 2. 安裝套件

```bash
pip install -r requirements.txt
```

### 3. 啟動程式

```bash
streamlit run streamlit_app.py
```

## 線上展示

線上展示網址整理中。

## 專案目的

本專案用於練習與展示：

- Python 網路資料存取
- 電商商品資料蒐集
- API 資料解析
- pandas 資料處理
- 商品價格分析
- Plotly 資料視覺化
- Streamlit Web App 開發
- CSV 資料匯出

## 注意事項

- 商品資料可能因 PChome 網站結構或資料格式變動而無法正常取得。
- 請勿短時間內進行大量或高頻率請求。
- 商品價格與折扣資訊應以 PChome 官方頁面為準。
- 本專案僅供程式設計與資料分析學習使用。

## 未來改進方向

- 增加商品歷史價格紀錄
- 加入價格變化通知
- 加入 SQLite 或 PostgreSQL 資料庫
- 增加定時資料蒐集功能
- 加入不同購物網站的商品比較
- 使用 Docker 建立部署環境
