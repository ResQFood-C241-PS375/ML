
# **ResQFood Project (Machine Learning)**

### Author


|Name                               |Student ID          | Universitas               |
| ----------------------------------|---------------------|----------------------------|
| Fatimah Fatma Syifa               | M008D4KX2809		  | Universitas Gadjah Mada    |
| Saprina Saputri                   | M008D4KX3152		  | Universitas Gadjah Mada    |
| Raditya Arviandana                | M008D4KY3146		  | Universitas Gadjah Mada    |


### Dataset Description
The data we used consists of image datasets with 10 different objects [1]. We grouped two of these objects, Sandwich and Donut, into a new category called "Roti" The other eight objects—Baked Potato, Burger, Crispy Chicken, Fries, Hot Dog, Pizza, Taco, and Taquito—were grouped into a new category called "Bukan Roti." Here is an overview of the data distribution our team used for this project.

|No |Object Name        | Number of Training Set |Number of Test Set|
| --|-------------------|------------------------|------------------|
| 1 | Sandwich		      | 1500                   | 500              |
| 2 | Donut		          | 1500                   | 500              |
| 3 | Baked Potato		  | 375                    | 125              |
| 4 | Burger		        | 375                    | 125              |
| 5 | Crispy Chicken	  | 375                    | 125              |
| 6 | Fries		          | 375                    | 125              |
| 7 | Hot Dog		        | 375                    | 125              |
| 8 | Pizza		          | 375                    | 125              |
| 9 | Taco		          | 375                    | 125              |
| 10| Taquito		        | 375                    | 125              |

### Features and Model
The model that we used are 3 different kind of model architectures with different accuracy. We used sequential, InceptionV3, and MobileNetV2. So here the comparisons:
|No |Model Name   | Size (MB)| Accuracy |
| --|-------------|----------|----------|
| 1 | Sequential  |   96     | 71%      |
| 2 | MobileNetV2 |   126    |  76%     |
| 3 | InceptionV3 |   108    | 87.17%   |

We used InceptionV3 model because It has highest accuracy model.
### References
[1] https://www.kaggle.com/datasets/utkarshsaxenadn/fast-food-classification-dataset/discussion?sort=hotness
