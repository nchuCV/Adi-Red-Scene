# Adaptive Discriminative Region Discovery for Scene Recognition

By [Zhengyu Zhao](https://zhengyuzhao.github.io/).

Radboud University (RU).

### Introduction

This repository contains the codes for Adi-Red approach described in the paper "From Volcano to Toyshop: Adaptive Discriminative Region
Discovery for Scene Recognition" (). This approach achieved state-of-the-art performance in terms of Top-1 classification accuracy on the scene benchmark SUN397 (https://groups.csail.mit.edu/vision/SUN/), by discovering discriminative local image patches efficiently. 

### Citation

If you use this approach in your research, please cite:

	@article{Zhao2018,
		author = {Zhengyu Zhao and Martha Larson},
		title = {From Volcano to Toyshop: Adaptive Discriminative Region Discovery for Scene Recognition},
		Booktitle={ACM Multimedia},
		Year={2018}
	}


### Results
1. We used the multi-scale deep features generated by our approach to train a linear SVM classifier with parameter C fixed for all the     implementations.





2. We used the multi-scale deep features generated by our approach to train a linear SVM classifier with parameter C fixed for all the     implementations.
Top-1 accuracy on SUN397: 

	Networks|Baseline|Adi-Red
	:---:|:---:|:---:
	AlexNet|54.17%|61.01%
	ResNet-18|66.96%|70.58%
	ResNet-50|71.38%|73.59%
	

	

