# Anomaly-Activity-Detection---MILR

## Abstract
Abnormal activity detection is one of the most challenging tasks in the field of computer vision. This study is motivated by the recent state-of-art work of abnormal activity detection, which utilizes both abnormal and normal videos in learning abnormalities with the help of multiple instance learning by providing the data with video-level information. In the absence of temporal-annotations, such a model is prone to give a false alarm while detecting the abnormalities. For this reason, in this paper, we focus on the task of minimizing the false alarm rate while performing an abnormal activity detection task. The mitigation of these false alarms and recent advancement of 3D deep neural network in video action recognition task collectively give us motivation to exploit the 3D ResNet in our proposed method, which helps to extract spatial-temporal features from the videos. Afterwards, using these features and deep multiple instance learning along with the proposed ranking loss, our model learns to predict the abnormality score at the video segment level. Therefore, our proposed method 3D deep Multiple Instance Learning with ResNet (MILR) along with the new proposed ranking loss function achieves the best performance on the UCF-Crime benchmark dataset, as compared to other state-of-art methods. The effectiveness of our proposed method is demonstrated on the UCF-Crime dataset.

![alt text](https://github.com/shikha-gist/Anomaly-Activity-Detection---MILR/blob/main/arch.png)

## MILR Frame-level AUC (in %) Evaluation on UCF-Crime Dataset
Model | UCF-Crime 
--- | --- 
MILR | 76.67 




[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-resnet-with-ranking-loss-function-for/anomaly-detection-in-surveillance-videos-on)](https://paperswithcode.com/sota/anomaly-detection-in-surveillance-videos-on?p=3d-resnet-with-ranking-loss-function-for)


## Citation
Please cite the following BibTex: 
<pre>
@inproceedings{dubey20193d,
  title={3d resnet with ranking loss function for abnormal activity detection in videos},
  author={Dubey, Shikha and Boragule, Abhijeet and Jeon, Moongu},
  booktitle={2019 International Conference on Control, Automation and Information Sciences (ICCAIS)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}
</pre>

If you find the paper and this repository helpful, please consider citing our paper [MILR](https://ieeexplore.ieee.org/abstract/document/9074586). Thank you!


## License
This project is licensed under Machine Learning & Vision Laboratory (MLV Lab), GIST. 
