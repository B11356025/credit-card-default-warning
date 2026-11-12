# credit-card-default-warning
「人工智慧期中報告（第   組）：台灣信用卡違約預警」

## 內容
- `AI期中_信用卡違約預警_可行性測試.ipynb`：可行性測試筆記本（建議用 Google Colab 開啟，執行階段 → 全部執行），含補充分析（公平性指標、門檻與預警名單成本、SHAP 可解釋性、穩定性檢驗）
- `feasibility_outputs/results/`：數字表格
- `feasibility_outputs/figures/`：圖表

## 資料來源
UCI Machine Learning Repository「Default of Credit Card Clients」，CC BY 4.0。
網址：https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
筆記本會自動下載資料，本儲存庫不另外存放原始資料。

## 環境
Python 3.13.18、scikit-learn 1.6.1、XGBoost 3.4.1、pandas 2.2.3、NumPy 2.4.6；隨機種子：基準實驗為 42，穩定性檢驗為 42 至 46。
