# agri-image
Image processing for agriculture.  
By Laboratory of Field Phenomics, Graduate School of Agricultural and Life Sciences, The University of Tokyo.  
Lab [homepage](https://lab.fieldphenomics.com/)  
**NOTE:**  


## 事前準備（Preparation）
### [SetupGooglecolab](https://drive.google.com/file/d/1gkNQDE2NYd5b9xj5fNDu5e9pCtc4lIaN/view?usp=sharing)  
なぜGooglecolab？  
Pythonの環境構築不要なGPUも使えるWebサービス（基本無料）
  
## 植物画像データに基づくデータ解析の応用例.  
Applications of Image analysis for agriculture.  
[資料Slides]()

## 植物画像データの画像解析（１）  
Fundamentals of image analysis(Vectors and matrices operation)  
1. Googlecolab_fundamentals_1  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Googlecolab_fundamentals_1_jp.ipynb) <br>
2. Googlecolab_fundamentals_2  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Googlecolab_fundamentals_2_jp.ipynb) <br>

## 植物画像データの画像解析（２）  
Fundamentals of image analysis(Undstand Digital images and Preprossing)
1. Googlecolab_fundamentals_3  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Googlecolab_fundamentals_3_jp.ipynb) <br>
2. Googlecolab_fundamentals_4  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Googlecolab_fundamentals_4_jp.ipynb) <br>  
3. Googlecolab_fundamentals_5  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Googlecolab_fundamentals_5.ipynb) <br>  

## 植物画像データの機械学習  
Image analysis for agriculture: Machine learning  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/Calculate_cc.ipynb) <br> 

## 植物画像データの深層学習  
Image analysis for agriculture: Deep learning  
Demo1:  
[Example:雑草識別モデル (Weed recognization demo)](https://teachablemachine.withgoogle.com/models/1u_hCfzqq/)  
Demo2:  
[Example:ムギ穂検出モデル(wheat head detection)](https://demo.roboflow.com/gwhd2021/2?publishable_key=rf_weZnIlXkTFd6iBv8A6VW4nGUH673)  

1. [Study_CNN_Explainer](https://utokyo-fieldphenomics-lab.github.io/Study_CNN_Explainer/) (modified with weed dataset)  
original version from Here: [Zijie J. Wang et al., 2020](https://github.com/poloclub/cnn-explainer).  
1. [初心者のための TensorFlow 2.0 入門](https://www.tensorflow.org/tutorials/quickstart/beginner)  
2. [畳み込みニューラルネットワーク (Convolutional Neural Networks)](https://www.tensorflow.org/tutorials/images/cnn)
3. TensorFlow2 for beginner  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/TensorFlow2beginner.ipynb) <br>  
1. Image classification  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/weed_classification_01.ipynb) <br>  
1. Object detection  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/YOLOv5withGlovalWheat.ipynb) <br>  
  

## 多次元画像データの解析（三次元点群中心）  
Image analysis for agriculture: Multi-dimensional imaging  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/PointCloudProcess.ipynb) <br>

## 植物画像データの収集.  
Data collection  
[資料Slides]()
1. UAVPP, Breeder-Friendly-Plant-Phenotyping-tools for UAV, [Wiki page](https://github.com/oceam/UAVPP/wiki/).　　
2. UGVPP, field phenotyping rover, [homepage](https://github.com/UTokyo-FieldPhenomics-Lab/UGVPP).　　

## 深層学習を実践する 
1. Dataset  
1.1. [Weed discrimination dataset](https://drive.google.com/drive/folders/1kAKfIyv2DGHnGB0NPSJAJJcDCA8U2dGe?usp=sharing)  
1.2. [roboflowPublickDtaset](https://public.roboflow.com/)
2. Try play with weed discrimination model  
2.1. Use [Google Teachable Machine](https://teachablemachine.withgoogle.com/)   
2.1.1 try to use the model made from google teachable machine  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/test_teachable_machine_model.ipynb) <br>
2.2. Use Google colab  
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/weed_classification_02.ipynb) <br>
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/agri-image/blob/main/codes/weed_classification_04.ipynb) <br>

## Useful information  
1. [Yann LeCun 深層学習コース(多言語資料あり)](https://atcold.github.io/pytorch-Deep-Learning/ja/)
1. [Computer Vision with Deep Learning for Plant Phenotyping in Agriculture: A Survey](https://arxiv.org/pdf/2006.11391.pdf)  
1. [AIセミナー"深層学習を使ったキュウリ選別機つくってみた" (a farmer made his own Cucumber ranking machine)](https://youtu.be/3E3jYjZ9h78)
1. [Youtube: Farmer live camera in　鹿児島](https://www.youtube.com/channel/UCpslgQ4Maq47zDUoHiFWwMQ)
1. [Youtube：おすすめ深層学習入門動画(videos introduce Deep learning in Japanese)](https://www.youtube.com/c/NeuralNetworkConsole)
1. [Youtube：The Future of Farming](https://youtu.be/Qmla9NLFBvU)
1. [Youtube：Drones, robots, and super sperm – the future of farming](https://youtu.be/qwNVNE83Udo)  
1. [農林水産省：スマート農業](https://www.maff.go.jp/j/kanbo/smart/)
1. [農林水産省：農業DX構想](https://www.maff.go.jp/j/press/kanbo/joho/210325.html)
1. [九州大学3Dデジタル生物標本](https://www.kyushu-u.ac.jp/ja/researches/view/802/)

