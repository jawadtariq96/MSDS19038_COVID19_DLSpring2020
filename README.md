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


|  Class  | Infected  | Normal |
|-------- | --------- | -------|
| Infected|   562     |   53   |
| Normal  |   40      |   845  |

## Fine Tuning All Layers

### VGG16: Confusion Matrix

|  Class  | Infected  | Normal |
|-------- | --------- | -------|
| Infected|   581     |   34   |
| Normal  |   10      |   875  |

### ResNet18: Confusion Matrix


|  Class  | Infected  | Normal |
|-------- | --------- | -------|
| Infected|   600     |   15   |
| Normal  |   34      |   851  |


## Best OverAll Accuracy 

|   Model     | Testing Accuracy | Training Accuracy | Validation Accuracy |
| ---------   | -----------------| ----------------- | ------------------- |
|   VGG16     |     0.9733       |     0.9595        |        0.9167       |   

## Experiments Details:

|   Model         |     Layers Fine Tuned   |  Testing Accuracy | Training Accuracy | Validation Accuracy |
| --------------  |     -----------------   | ----------------- | ----------------- | ------------------- |
|   VGG16         |        Only FC Layers   |     0.9733        |     0.9595        |        0.9167       | 
|   VGG16         |        All Layers       |     0.9707        |     0.95917       |        0.9187       | 
|   ResNet18      |        FC Layers        |     0.93          |     0.8745        |        0.874        | 
|   ResNet18      |       FC + 9 Layers     |     0.9647        |     0.9625        |        0.9167       |
|   ResNet18      |       All Layers        |     0.967         |     0.9625        |        0.9167       |


