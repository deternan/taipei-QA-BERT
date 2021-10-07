# 台北QA問答機器人(with BERT)
問一個問題，告訴你應該去哪個單位處理這些問題

## 檔案說明
- train.py : 模型訓練(BERT fine-tune)
- predict.py : 提問預測
- [tutorial](https://github.com/p208p2002/taipei-QA-BERT/tree/master/tutorial) : 投影片檔案

## 中文Albert
- 預設使用bert-base-chinese
- 欲切換至albert-zh-tiny請將`train.py`與`predict.py`對應註解拿掉

## 環境需求
- python 3.6+
- pytorch 1.3+
