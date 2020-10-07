#
```
[1]Python開發環境:Google Colab
Google Colab的Python開發環境暨使用技術
[1]登入 註冊與使用
[2]認識Colab環境

[3]執行別人github上的XX.ipynb檔
[4]儲存到你的GITHUB
[5]下載程式(XX.py   XX.ipynb)到本地端

[6]上傳程式到GOOGLE drive, 從Google drive 開啟xxx.ipynb

[7]上傳檔案到colab
[8]執行colab上的xxx.py程式

[9]把整個別人分享的github  git clone到你的colab
[10]載入你的google drive 到colab

```
### Numpy實戰 使用Google Colab學習Python與人工智慧
```
使用Google Colab平台學習Python程式設計
使用Google Colab平台學習Python資料分析技術
使用Google Colab平台學習機器學習(machine Learning)
使用Google Colab平台學習深度學習(deep Learning)
使用Google Colab平台學習強化學習(reinforcement Learning)
```
# Google Colab
```
https://colab.research.google.com/
```
```
Google Colab is a free cloud service and now it supports free GPU!

You can;
improve your Python programming language coding skills.
develop deep learning applications using popular libraries such as Keras,
TensorFlow, PyTorch, OpenAI gymand OpenCV.
The most important feature that distinguishes Colab from other free cloud services is;
Colab provides GPU and is totally free.
```
# 確認Google Colab上的套件使用版本
```
import pandas as pd
print("pandas version: %s" % pd.__version__)

import matplotlib
print("matplotlib version: %s" % matplotlib.__version__)

import numpy as np
print("numpy version: %s" % np.__version__)

import sklearn
print("scikit-learn version: %s" % sklearn.__version__)

import tensorflow as tf
print("tensorflow version: %s" % tf.__version__)

import torch
print("PyTorch version: %s" %torch.__version__)
print("2020年3月PyTorch version最新版本 是1.4 請參閱https://pytorch.org/")
```

### 切換不同版本的Tensorflow
```
Google Colab預設使用版本:1.15.0[20200314]
import tensorflow as tf
print("tensorflow version: %s" % tf.__version__)
```
```
新開一個Notebook

%tensorflow_version 2.x
import tensorflow as tf
print("tensorflow version: %s" % tf.__version__)

Google Colab使用版本:2.1.0[20200314]
```
