[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/y1027940727-gif/PR_surgical_instrument_yolo/blob/main/ai_hawk.ipynb
)


# Surgical Instrument Detection with YOLOv8  
手術器械盤物件偵測與清點專題

> Pattern Recognition 課程作業／專題  
> Student ID: 113C51513  
> Author: Joanne Liao

---

## 🎯 專題簡介

本專題利用 **YOLOv8** 建立手術器械偵測模型，目標場景為手術室，希望能偵測並清點手術器械，未來可延伸應用於：

- 手術前後器械清點與數量核對  
- 防止器械／紗布遺留於病人體內  
- 形成「AI 器械盤巡檢」工具，減少人工反覆點算負擔  

本 repo 主要紀錄：

- YOLOv8 訓練與推論的 Colab Notebook
- 資料設定檔（`data_instruments.yaml`）
- 專題說明與實驗結果摘要

> ⚠️ 完整影像資料集未隨 repo 一併釋出（容量較大且來源為 Roboflow），使用者需自行下載後放置於指定位置。

---

## 📂 專案結構建議

```text
PR_surgical_instrument_yolo/
├─ notebooks/
│  └─ PR_yolo_instrument_detection.ipynb   # 主要 Colab Notebook
├─ config/
│  └─ data_instruments.yaml               # YOLO 資料設定檔
└─ README.md


