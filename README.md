# MSDS19038_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.


## DataSet Can be Found Here [COVID Datasets](https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view).

## Fine Tuning Fully Connected Layers

### VGG16: Confusion Matrix


|  Class  | Infected  | Normal |
|-------- | --------- | -------|
| Infected|   589     |   26   |
| Normal  |   14      |   871  |

### ResNet18: Confusion Matrix


| Infected  | Normal |
| --------- | -------|
|   562     |   53   |
|   40      |   845  |

## Fine Tuning All Layers

### VGG16: Confusion Matrix

| Infected  | Normal |
| --------- | -------|
|   581     |   34   |
|   10      |   875  |

### ResNet18: Confusion Matrix


| Infected  | Normal |
| --------- | -------|
|   600     |   15   |
|   34      |   851  |


## Best OverAll Accuracy 

|   Model     | Testing Accuracy | Training Accuracy | Validation Accuracy |
| ---------   | -----------------| ----------------- | ------------------- |
|   VGG16     |     0.9733       |     0.9595        |        0.9167       |

