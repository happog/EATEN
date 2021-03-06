# EATEN: Entity-aware Attention for Single Shot Visual Text Extraction     
Accepted to ICDAR 2019 [arxiv](https://arxiv.org/abs/1909.09380#)      
Authors: He Guo, Xiameng Qin, Jiaming Liu, Junyu Han, Jingtuo Liu and Errui Ding     

## Abstract
This repository is designed to provide an open-source dataset for Visual Text Extraction.

## Samples
### Train ticket
#### Real images 
![real1](./figures/real1.jpg)
![real2](./figures/real2.jpg)

#### Synthetic images 
##### Some clean images
![synth-easy](./figures/synth-easy.png)
##### Some hard images
![synth-hard](./figures/synth-hard.png)

### Passport
##### Some images
![passport-easy](./figures/passport-easy.png)
##### Some hard images
![passport-hard](./figures/passport-hard.png)

### Business card
![bc1](./figures/bc1.png)
![bc2](./figures/bc2.png)

## Downloads
The dataset can be downloaded through the following link:   
[baiduyun](https://pan.baidu.com/s/1HVMa_bpCeegticZVFOkJ5g), PASSWORD: e4z1 

Some details:         


|scenes| number | size| Google Drive link |
|-------------------|:-------------------:|:---------------------:|:---------------------:|
|train ticket | 300k synth + 1.9 real| 13G|[dataset_trainticket.tar](https://drive.google.com/open?id=1zxu44zSBtBw9CZjIIVPfK0h9YqHfQKID)|  
|passport | 100k synth |5.8G|[dataset_passport.tar](https://drive.google.com/open?id=11XhKsjqzZY6jBakkLDy8lywE3w37kPaC)|  
|business card | 200k synth| 19G|[dataset_business.tar.0   ](https://drive.google.com/open?id=1irnwv8MqK9nCT_NqmnjHfQ8DlwdMwcBs)[dataset_business.tar.1   ](https://drive.google.com/open?id=16Y26c5VCBYx_CD7Mz3UR6rCbVclq7sRP)[dataset_business.tar.2   ](https://drive.google.com/open?id=1ilQC0cmLhW_N9sl6UbGQZHlk5p_H98Q4)[dataset_business.tar.3   ](https://drive.google.com/open?id=1URl4V8Zxgpl0jifkjIDjy-gMa5g3Jtsj)|   
   


## Limitations&&Todo
  - [A large of training data]            
    Todo: 
    1. Use CycleGan or domain adaptation to synth data to train EATEN.
    2. Introduce datasets of STR to EATEN.
  - [Generalization on complex scenes]         
    Todo:
    1. Add bounding box annotations of ToIs to EATEN, such as [2019-ICCV-oral Towards Unconstrained End-to-End Text Spotting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Qin_Towards_Unconstrained_End-to-End_Text_Spotting_ICCV_2019_paper.pdf).
  - [Engineering]         
    1. Merge server decoder to one.
    2. parallel decoding.
