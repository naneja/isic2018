# ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection

This repository presents results of our work to detect Melanoma by Skin Lesion Analysis.

## About ISIC
The International Skin Imaging Collaboration (ISIC) is an international effort to improve melanoma diagnosis, sponsored by the International Society for Digital Imaging of the Skin (ISDIS). The ISIC Archive contains the largest publicly available collection of quality controlled dermoscopic images of skin lesions.

The goal of this [challenge](https://challenge2018.isic-archive.com) is to help participants develop image analysis tools to enable the automated diagnosis of melanoma from dermoscopic images.

This challenge is broken into three separate tasks:
Task 1: Lesion Segmentation  
Task 2: Lesion Attribute Detection
Task 3: Disease Classification

Ours results are for Task 3: Disease Classification

Possible disease categories are:

| Sr.No. | Disease |
|:-------------:|:-------------:|
| 1   | Melanoma |
| 2   | Melanocytic nevus |
| 3   | Basal cell carcinoma |
| 4   | Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) |
| 5   | Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) |
| 6   | Dermatofibroma |
| 7   | Vascular lesion |

 
## Results
Following Graphs show Model Accuracy for Training and Testing Phase; Model Loss for Training and Testing Phase; and Computation Time for Training the model and Training plus Tresting the model.

![model](https://github.com/naneja/isic2018/blob/master/figs/model.png)

Model Accuracy, Model Loss, and Training Time is available at [model](https://github.com/naneja/isic2018/blob/master/log/results.csv)

Class wise probabilities for each valid image is available at [Valid Results](https://github.com/naneja/isic2018/blob/master/log/results-valid.csv)  

Class wise probabilities for each test image is available at [Test Results](https://github.com/naneja/isic2018/blob/master/log/results-test.csv)  

Our position at [ISIC Live Challenge Leaderboards](https://challenge2018.isic-archive.com/live-leaderboards/) at the time of uploading the results for Task 3 is 23 and we are working to improve the results.

## Sanity Check
Following are five random images that were picked and detected one of the disease categories by our model

![Pred1](https://github.com/naneja/isic2018/blob/master/figs/pred1.png)
![Pred2](https://github.com/naneja/isic2018/blob/master/figs/pred2.png)
![Pred3](https://github.com/naneja/isic2018/blob/master/figs/pred3.png)
![Pred4](https://github.com/naneja/isic2018/blob/master/figs/pred4.png)
![Pred5](https://github.com/naneja/isic2018/blob/master/figs/pred5.png)

## Dataset Size
Below is the Training Dataset consisting of 10,015 images for different disease categories

| Sr.No. | Disease | Training Files |
|:-------------:|:-------------:|:-------------:|
| 1   | Melanoma | 1113 |
| 2   | Melanocytic nevus | 6705 |
| 3   | Basal cell carcinoma | 514 |
| 4   | Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) | 327 |
| 5   | Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) | 1099 |
| 6   | Dermatofibroma | 115 |
| 7   | Vascular lesion | 142 |


## Feedback
Please submit your feedback to [Dr. Nagender Aneja, http://ResearchID.co/naneja ](http://ResearchID.co/naneja). 

Please write an email (nanejaATgmail or nanejaATieee.org) if you are interested to collaborate further. 
