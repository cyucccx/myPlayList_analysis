# Apple Music 播放清單分析

本專案是一份使用 Jupyter Notebook 撰寫的 Apple Music 播放清單分析工具，透過匯入你從 iTunes 或音樂 App 匯出的 `.csv` 播放清單，進行資料整理與視覺化。

## 🔍 分析功能

* 播放次數前 10 名藝人長條圖
* 年份分布直方圖
* 分類（genre）比例圓餅圖
* 播放次數分布圖（可自訂）

## 📁 使用方式

### 1. 匯出 Apple Music 播放清單

* 開啟 iTunes 或音樂 App
* 點選你的播放清單 > `檔案 > 資料庫 > 匯出播放清單`
* 格式選擇為「文字檔 (.txt)」
* 匯出後可用 Excel / Google Sheets 開啟並儲存為 `.csv`

### 2. 執行分析

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook
```

打開 `apple_music_analysis_template.ipynb`，修改程式中匯入的檔名為你的 CSV，即可產出圖表。

## 📊 使用工具

* Python 3.x
* pandas（資料處理）
* matplotlib / seaborn（圖表繪製）

## 🧪 延伸應用

你可以自訂分析內容，例如：

* 按年份/分類分組的最愛歌手分析
* 播放次數 vs 收藏次數關聯性
* 分析最近播放時間分布（若資料有提供）

## 📝 授權

MIT License
