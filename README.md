# Deep Learning Application

本專案結合兩個不同領域的深度學習應用任務，分別針對：
1. 多分類瑕疵影像分類（NEU Surface Defect Database）
2. 時序資料預測（Bike Sharing Demand）

使用 TensorFlow 與 Keras 完成模型設計、訓練與測試，展現影像分類與時間序列預測的實作能力與資料處理技巧。

---

## 任務與模型說明

### 任務一：瑕疵影像分類（Image Classification）

**資料集**：[NEU Surface Defect Database]
**任務目標**：將鋼材表面影像進行六種瑕疵類別分類
**模型架構**：自建 CNN 卷積神經網路模型
**處理步驟**：
  - 圖像預處理與增強（Data Augmentation）
  - 模型訓練與驗證
  - 測試集分類效果輸出

---

### 任務二：腳踏車租借人數預測（Time Series Forecasting）

**資料集**：[Bike Sharing Demand]
**任務目標**：根據歷史天氣與時間資料預測每日腳踏車租借數量
**模型架構**：使用 LSTM（長短期記憶）模型處理時間序列資料
**處理步驟**：
  - 特徵選擇與資料標準化
  - 時序分段輸入處理
  - LSTM 模型建構與訓練
  - 預測曲線可視化

---

## 軟體環境

| 套件 | 版本 |
|------|------|
| Python | 3.7.16 |
| TensorFlow (GPU) | 2.0.0 |
| NumPy | 1.21.6 |
| OpenCV | 4.6.0 |
