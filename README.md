# 🧠 Biomedical Signal Processing – Experiment 3  
### Digital Filtering and EEG Signal Analysis

This repository contains the final report and source files for **Experiment 3: Digital Filtering of EEG Signals**, completed as part of the Biomedical Engineering Lab (Spring 2025).

## 📄 Final Report  
- [`BME_Exp3_final_version.pdf`](./BME_Exp3_final_version.pdf)  
  → Includes circuit design (ECG/EMG), digital EEG processing, Bluetooth transmission, and system integration.

## 📦 Source Files & Code  
- [`實驗三-數位濾波.zip`](./%E5%AF%A6%E9%A9%97%E4%B8%89-%E6%95%B8%E4%BD%8D%E6%BF%BE%E6%B3%A2.zip)  
  → Contains EEG data files and MATLAB scripts for filtering and spectral analysis.

### File Contents:
| File | Description |
|------|-------------|
| `biopac_data_close.xlsx` | Biopac EEG data (eyes closed) |
| `biopac_data_open.xlsx`  | Biopac EEG data (eyes open)  |
| `close_eye_raw_data.xlsx` | Raw EEG data (eyes closed) |
| `open_eye_raw_data.xlsx`  | Raw EEG data (eyes open)  |
| `EEG raw data.xlsx`       | Combined raw EEG file |
| `G2 raw data.xlsx`        | Extra EEG channel |
| `eeg_biopac_data_analysis.m` | Biopac signal FFT |
| `eeg_raw_data_analysis.m`    | Bandpass filtering + FFT |
| `raw_data_vs_biopac_data.m`  | Comparison plots |

## 🔧 Features
- EEG signal band filtering using IIR filters (Delta, Theta, Alpha, Beta)
- Spectral analysis via FFT
- MATLAB code with clear filtering structure
- Validation against Biopac system output

## 👥 Authors  
- Max Han（韓裕民）— Circuit Design, EEG Processing  
- Amy Chen（陳郁玲）— App Development, UI, Report Writing  
- Tzu-Chi Wei（魏子旂）— Arduino Integration, Code Debugging  

## 📎 Reference  
- Digital filter design inspired by [Changpuak Filter Calculator](https://www.changpuak.ch/electronics/index.php)  
- 60Hz noise reference: [StrongPi Lab – PSTN Phone Humming](https://www.strongpilab.com/pstn-phone-reduce-60hz-humming/)

---
