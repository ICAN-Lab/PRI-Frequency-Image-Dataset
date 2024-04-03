# PRI Frequency Image Dataset

The PRI frequency features of the radar pulse sequence could be represented by an image and we achieve pixel classification by a semantic segmentation network. The paper has been prepared to submit.
We're sharing them here for developers and researchers to explore, study, and learn from.

#### Novelty  
![preview](preview.jpg)
Given received signal strength (RSS) measurements of the commodity WiFi receiver at the UAV, UH-Sense can **detect** and **localize** moving human targets in the monitored area.
- A combination of neural network-based classifier and radio tomography imaging technique (RTI) is utilized to determine the presence of targets and their relative positions, respectively.

#### Dataset type
The data set format is VOC and the content is as follows:

VOC Dataset Structure
##### ├── VOCdevkit
##### │   ├── VOC2012
##### │   │   ├── ImageSets
##### │   │   │   ├── Segmentation
##### │   │   │   │   ├── train.txt
##### │   │   │   │   ├── val.txt
##### │   │   │   │   ├── trainval.txt
##### │   │   ├── JPEGImages
##### │   │   │   ├── *.jpg    # All images
##### │   │   ├── SegmentationClass
##### │   │   │   ├── *.png    # All label images

```javascript
##### ├── VOCdevkit
##### │   ├── VOC2012
##### │   │   ├── ImageSets
##### │   │   │   ├── Segmentation
##### │   │   │   │   ├── train.txt
##### │   │   │   │   ├── val.txt
##### │   │   │   │   ├── trainval.txt
##### │   │   ├── JPEGImages
##### │   │   │   ├── *.jpg    # All images
##### │   │   ├── SegmentationClass
##### │   │   │   ├── *.png    # All label images
```

Among them, train.txt, val.txt, trainval.txt only need the picture name, no suffix or path is required.

## Authors & Contributors
TO-ADE is authored by
[WeiYi Wang],
[YuJia Chen],
from National Central University.
The code is developed by
[WeiYi Wang].
Currently, it is being maintained by
[WeiYi Wang].
