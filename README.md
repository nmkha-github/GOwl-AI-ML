
# Golden Owl AI/ML Intern


## Report
My method is described in ```Report.pdf```
## Dataset
- The dataset should be organized like this (make sure name of dataset folder dogs-vs-cats):
 ```
dogs-vs-cats
|--train
|    |------cat.1.jpg
|    |------cat.2.jpg
|    |------cat.3.jpg
|    |------...
|    |------dog.1.jpg
|    |------dog.2.jpg
|    |------dog.3.jpg
|    |------...
|--test
     |------cat.1.jpg
     |------cat.2.jpg
     |------cat.3.jpg
     |------...
     |------dog.1.jpg
     |------dog.2.jpg
     |------dog.3.jpg
     |------...
```
## Train
Train on my dataset:
 - Run all cell with **T4 (or GPU support CUDA)** and mount your google drive in this [train colab](https://colab.research.google.com/drive/1XeQ71whY1xNBBnNEHNeSoAHf7OUs_ajt?authuser=0#scrollTo=qhENu7GAoywC)
 - Pretrained model will be save in your drive with path /GO/saved_model
Train on your dataset (optional):
 - ```ZIP``` your dataset (following above structure) and upload it to ```Google drive```, set its share with everyone and get its ID.
 - Change ID in download dataset cell
```
!gdown <Your dataset ID>
```
 - Run all cell with **T4 (or GPU support CUDA)** and mount your google drive in this [train colab](https://colab.research.google.com/drive/1XeQ71whY1xNBBnNEHNeSoAHf7OUs_ajt?authuser=0#scrollTo=qhENu7GAoywC)
 - Pretrained model will be save in your drive with path /GO/saved_model

## Evaluate 
Evaluate on my dataset:
 - Run all cell with **T4 (or GPU support CUDA)** in this [evaluate colab](https://colab.research.google.com/drive/1KPIpFvXOhGqu_RY81dGkdgmPY5ypDFZt?authuser=2#scrollTo=2ca_pNWQuTfI)
Evaluate on your private dataset:
 - ```ZIP``` your dataset (following above structure) and upload it to ```Google drive```, set its share with everyone and get its ID.
 - Change ID in download dataset cell
 ```
!gdown <Your dataset ID>
```
 - Run all cell with **T4 (or GPU support CUDA)** in this [evaluate colab](https://colab.research.google.com/drive/1KPIpFvXOhGqu_RY81dGkdgmPY5ypDFZt?authuser=2#scrollTo=2ca_pNWQuTfI)

## Inference
 - Try inference by running all cell with **T4 (or GPU support CUDA)** in this [inference colab](https://colab.research.google.com/drive/1EeNjsE-CE5O7qnsI3Oa1exgRK9I9GMVa?authuser=2#scrollTo=AIV0qqAXE-NK)

## Acknowledgements
 - [BLIP paper](https://arxiv.org/pdf/2201.12086)
 - [LAVIS github](https://github.com/salesforce/LAVIS/tree/main)