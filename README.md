# Attentive Pattern

Code for ACM MM 2022 Paper "Image Inpainting Detection via Enriched Attentive Pattern with Near Original Image Augmentation"

Author: Wenhan Yang, Rizhao Cai, Alex C. Kot

Paper Link: <https://www.dropbox.com/s/6xl8oheeioz7vjn/MM_att_pattern_final.pdf?dl=0>

Project Page: <https://github.com/flyywh/Attentive_Pattern/>

Dataset: 

## Abstract

As deep learning-based inpainting methods have achieved increasingly better results, its malicious use, e.g. removing objects to report fake news or to provide fake evidence, is becoming threatening. Previous works have provided rich discussions on network architectures, e.g. even performing Neural Architecture Search to obtain the optimal model architecture. However, there are rooms in other aspects. In our work, we provide comprehensive efforts from data and feature aspects. From the data aspect, as harder samples in the training data usually lead to stronger detection models, we propose near original image augmentation that pushes the inpainted images closer to the original ones (without distortion and inpainting) as the input images, which is proved to improve the detection accuracy. From the feature aspect, we propose to extract the attentive pattern. With the designed attentive pattern, the knowledge of different inpainting methods can be better exploited during the training phase. Finally, extensive experiments are conducted. In our evaluation, we consider the scenarios where the inpainting masks, which are used to generate the testing set, have a distribution gap from those masks used to produce the training set. Thus, the comparisons are conducted on a newly proposed dataset, where testing masks are inconsistent with the training ones. The experimental results show the superiority of the proposed method and the effectiveness of each component.

## Framework

<p align='center'>  
<img src='https://github.com/flyywh/Attentive_Pattern/blob/main/imgs/framework.png' width='870'/>
</p>

## Result

<p align='center'>  
<img src='https://github.com/flyywh/Attentive_Pattern/blob/main/imgs/result.png' width='870'/>
</p>

<p align='center'>  
<img src='https://github.com/flyywh/Attentive_Pattern/blob/main/imgs/result2.png' width='870'/>
</p>

## Evaluation
1. Download the testing data and revise the testing data path in the code.
2. Run sh val.sh

## Training
Comming Soon!

## Demo
Comming Soon!

## Acknowledgement
Code borrows heavily from [[IID-Net](https://github.com/HighwayWu/InpaintingForensics)]. Thanks for the sharing.

## Contact
If you have questions, please contact `yangwh@pcl.ac.cn`.
