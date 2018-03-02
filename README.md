# Deeplearning notebook

## YOLO

| 目錄                                                  | 說明                                             |
| ----------------------------------------------------- | ------------------------------------------------ |
| [YOLOv1](./YOLOv1_book.ipynb)                         | YOLOv1 的介紹與說明                              |
| [yad2k](./yad2k_test.ipynb)                           | YOLOv2 to keras 的開源專案實現                   |
| [YOLOv2 raccoon](./YOLOv2_train_raccoon.ipynb)：訓練  | 載入YOLOv2權重，並修改網絡為浣熊辨識，並重新訓練 |
| [YOLOv2 raccoon](./demo_racoon_detection.ipynb)：驗證 | 載入訓練好的網絡，預測浣熊位置                   |
| [YOLOv2 hand](./YOLOv2_train_hand.ipynb)              | 載入YOLOv2權重，並修改網絡為手部辨識，並重新訓練 |

## Face Recognition

| 目錄                                                         | 說明                                       |
| ------------------------------------------------------------ | ------------------------------------------ |
| 1. [face-detect-align-and-crop](./01-face-detect-align-and-crop.ipynb) | MTCNN Model 臉部偵測、裁剪、對齊           |
| 2. [face-embedding-and-recognition-classifier ](./02-face-embedding-and-recognition-classifier.ipynb) | FaceNet 臉部特徵擷取、LinearSVC 訓練分類器 |
| 3. [face-recognition-woody-face](./03-face-recognition-woody-face.ipynb) | 載入模型進行及照片臉便辨識                 |