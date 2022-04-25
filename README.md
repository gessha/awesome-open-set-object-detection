# Open Set Object Recognition

## Topic definitions
- open set object detection
- open world object detection
- open world tracking
- open set segmentation
- open set panoptic segmentation

## List of all publications

### 2017
- [Dropout sampling for robust object detection in open-set conditions](https://arxiv.org/pdf/1710.06677.pdf), Dimity Miller, Lachlan Nicholson, Feras Dayoub, Niko Sunderhauf

### 2018
### 2019
### 2020
- [The Overlooked Elephant of Object Detection: Open Set](https://openaccess.thecvf.com/content_WACV_2020/papers/Dhamija_The_Overlooked_Elephant_of_Object_Detection_Open_Set_WACV_2020_paper.pdf), Akshay Raj Dhamija, Manuel G ̈unther, Jonathan Ventura, and Terrance E. Boult

### 2021
- [Exemplar-Based Open-Set Panoptic Segmentation Network](https://openaccess.thecvf.com/content/CVPR2021/papers/Hwang_Exemplar-Based_Open-Set_Panoptic_Segmentation_Network_CVPR_2021_paper.pdf), Jaedong Hwang, Seoung Wug Oh, Joon-Young Lee, Bohyung Han [CVPR 2021]
- [OW-DETR: Open-world Detection Transformer](https://arxiv.org/pdf/2112.01513.pdf) Akshita Gupta, Sanath Narayan, K. J. Joseph, S. Khan, F. Khan, M. Shah
- [Towards open world object detection](https://openaccess.thecvf.com/content/CVPR2021/papers/Joseph_Towards_Open_World_Object_Detection_CVPR_2021_paper.pdf), K J Joseph, Salman Khan, Fahad Shahbaz Khan, Vineeth N Balasubramanian
- [Deep Metric Learning for Open World Semantic Segmentation](https://openaccess.thecvf.com/content/ICCV2021/papers/Cen_Deep_Metric_Learning_for_Open_World_Semantic_Segmentation_ICCV_2021_paper.pdf), Jun Cen Peng Yun Junhao Cai Michael Yu Wang Ming Liu
- [Learning open-world object proposals without learning to classify](https://arxiv.org/pdf/2108.06753.pdf), Dahun Kim, Tsung-Yi Lin, Anelia Angelova, In So Kweon, Weicheng Kuo

### 2022
- [Uncertainty for Identifying Open-Set Errors in Visual Object Detection](http://arxiv.org/pdf/2104.01328) Dimity Miller, N. Sunderhauf, Michael Milford, Feras Dayoub
- [Learning to Detect Every Thing in an Open World](https://arxiv.org/pdf/2112.01698.pdf), Kuniaki Saito, Ping Hu, Trevor Darrell, Kate Saenko

## Breakdown by topic

### Open Set Object Detection

### Open World Object Detection

### Open Set Segmentation

### Open Set Panoptic Segmentation

## Related topics

### Uncertainty estimation

## Benchmarks

### Evaluation metrics
- Precision and Recall - 
- Absolute Open Set Error - total number of observations that pass the Entropy test, fall on unknown objects (there are no overlapping groud truth objects with an IoU >= 0.5 )and do not have a winning class label of unknown. In the case all observations are known objects, open set error is 0. - definition from Miller et al


### Datasets
- Scene RGB-D
- QUT Campus Dataset