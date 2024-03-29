# UV-ABLM
Ubiquitous Vision of Transformers for Person Re-identification: A self-attention and aligned batch layoff module based novel person re-id approach

Pytorch based library "[torchreid](https://github.com/KaiyangZhou/deep-person-reid)" is used for this work, which provides a unified interface for 03 public person re-id datasets. 

# Datasets

Person Re-id datasets can be downloaded from the links given below. Extract the datasets and place in the respective sub-folders in the "reid-data" folder i.e. reid-data/market, reid-data/msmt17 etc.

## Market1501
Market 1501 dataset is an open-access dataset and can be downloaded from [Openlink](http://zheng-lab.cecs.anu.edu.au/Project/project_reid.html)

## DukeMTMC-reID
DukeMTMC-reID dataset is an open-access dataset, the dataset can be downloaded via GoogleDriver and BaiduYun, the [download links](https://github.com/sxzrt/DukeMTMC-reID_evaluation#download-dataset) are shared by the authors of DukeMTMC-ReID dataset via their [github repository](https://github.com/sxzrt/DukeMTMC-reID_evaluation). The authors of the dataset are very generous to handle the queries regarding dataset download links as mentioned [here](https://github.com/sxzrt/DukeMTMC-reID_evaluation#download-dataset).

## MSMT17
MSMT17 dataset can be downloaded by following the detailed instructions available [here](https://www.pkuvmc.com/dataset.html)

# Evaluation
UV re-id trained models can be downloaded from [GoogleDriver](https://drive.google.com/drive/folders/1uHLHLJwf5NfvzZL9AwemCmsY6334DWPy?usp=sharing).

Copy the trained weights in the directory of "models/market" before running the evaluation script: python eval.py 


# Citations
If you find this code useful to your research, please cite the following papers.

Alexey Dosovitskiy, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, and Sylvain Gelly. An image is worth 16x16 words: Transformers for image recognition at scale. journal: arXiv preprint arXiv:2010.11929, 2020.

Zhou, Kaiyang and Xiang, Tao. Torchreid: A Library for Deep Learning Person Re-Identification in Pytorch. journal: arXiv preprint arXiv:1910.10093, 2019

Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N Gomez, Lukasz Kaiser, and Illia Polosukhin. Attention is all you need. Advances in neural information processing systems, 30:5998–6008, 2017.
