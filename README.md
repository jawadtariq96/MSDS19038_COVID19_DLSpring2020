# MSDS19038_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.


## DataSet Can be Found Here [COVID Datasets](https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view).

## Weights can be Found Here [Model Weights](https://drive.google.com/drive/folders/1WJ6FaGY4FZUmKL7060vW3gQxTVhqeSo8?usp=sharing).


## VGG16 with Binary Cross Entropy

### Training Data

|  Class  | Infected  | Normal |             |Class     |   Infected  | Normal    |   
|-------- | --------- | -------| ---------   |-------   |  ---------  | -------   |
| Infected|   581     |   34   |             | Infected |     581     |   34      |
| Normal  |   10      |   875  |             | Normal   |     10      |   875     |


<table>
<tr><th> COVID19 Class </th><th> Pneumonia Class</th></tr>
<tr><td>

|Table 1| Middle | Table 2|
| ----  |  ----  | ------ |
|   a   |  not b |  and c |

</td><td>

|b     |1    |2   |3   | 
|--    |--   | -- |--  |
|a     | s   | d  | f  |

</td></tr> </table>




## Experiments Details:

|   Model         |     Loss Functions      |  Focal Loss Parms |  F1 Score: COVID19 | 
| --------------  |     -----------------   | ----------------- | -----------------  |      
|   VGG16         |        BCE              |                   |     0.81           |
|   ResNet18      |        BCE              |                   |     0.76           |     
|   VGG16         |        Focal Loss       |     a =2, g =2    |     0.90           |      
|   ResNet18      |        Focal Los        |     a1 = 1 g=2    |     0.88           |  
