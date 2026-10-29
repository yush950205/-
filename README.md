# Google Colab 零成本入門實作

本專案參考 [Google Colab——零成本玩轉深度學習](https://www.cnblogs.com/huiwei13/p/11797142.html)，示範如何在 Google Colab 使用 Python、執行 Linux 指令、掛載 Google Drive，以及建立與執行 `.py` 程式。

## 學習目標

- 認識 Google Colab 與 Notebook 操作介面
- 執行 Python 程式碼與 Shell 指令
- 檢查 Python 執行環境
- 掛載 Google Drive 並切換工作目錄
- 建立與執行 Python 腳本

## 操作步驟

1. 開啟 [Google Colab](https://colab.research.google.com/) 並登入 Google 帳號。
2. 上傳本專案的 `Google_Colab_Practice.ipynb`。
3. 依序執行各個儲存格。Google Drive 掛載步驟會要求授權，可自行決定是否執行。
4. 確認輸出結果後，於 Colab 儲存 Notebook。
5. 將執行完成的 `.ipynb` 重新下載並上傳至 GitHub，取代本專案的初始版本。

## 程式內容與預期結果

| 項目 | 範例 | 預期結果 |
| --- | --- | --- |
| Python 基本操作 | `print(1)` | 顯示 `1` |
| Linux 指令 | `!pwd`、`!ls` | 顯示目前目錄及檔案 |
| Python 環境 | `import sys; print(sys.version)` | 顯示 Python 版本 |
| GPU 檢查 | `!nvidia-smi` | 有 GPU 時顯示裝置資訊，否則提示未啟用 |
| Drive 掛載 | `drive.mount('/content/drive')` | 授權後可存取 Drive |
| Python 腳本 | `!python hello.py` | 顯示 `Hello Google Colab!` |

## 執行結果截圖

執行完 Notebook 後，將自己的截圖放到 `images/` 資料夾，並取消下面 Markdown 圖片語法的註解，讓 GitHub 顯示圖片。

<!-- ![Colab 執行結果](images/colab-result.png) -->

> 注意：目前提供的是**可執行的作業初始檔**，尚未在你的 Google 帳號內執行或取得實際截圖。請完成執行後再提交。

## 參考資料

- 原始教學：[Google Colab——零成本玩轉深度學習](https://www.cnblogs.com/huiwei13/p/11797142.html)
- [Google Colab 官方網站](https://colab.research.google.com/)
