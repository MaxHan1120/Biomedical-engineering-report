# 實驗三：數位濾波實作實驗（EEG 訊號處理）

本資料夾為「生醫訊號處理實驗三－數位濾波」的原始資料與程式碼，內容包含 EEG 原始資料（睜眼/閉眼）、Biopac 測得資料，並使用 MATLAB 進行頻譜分析與數位濾波處理。

## 📁 檔案說明

| 檔案名稱 | 說明 |
|----------|------|
| `biopac_data_close.xlsx` | Biopac 測得之閉眼 EEG 數據 |
| `biopac_data_open.xlsx`  | Biopac 測得之睜眼 EEG 數據 |
| `EEG raw data.xlsx`      | 原始 EEG 訊號（非 Biopac） |
| `close_eye_raw_data.xlsx` | 自擷取的閉眼 EEG |
| `open_eye_raw_data.xlsx`  | 自擷取的睜眼 EEG |
| `G2 raw data.xlsx`        | 額外通道 G2 的訊號資料 |
| `eeg_biopac_data_analysis.m` | Biopac 與自擷取資料的對照分析 |
| `eeg_raw_data_analysis.m`    | 數位濾波主程式，處理 raw EEG |
| `raw_data_vs_biopac_data.m`  | 原始資料 vs Biopac 波形對比 |

