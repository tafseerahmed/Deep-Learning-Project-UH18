# Deep-Learning-Project-UH18
Repository for Deep Learning Class Project/Competition 2018

We decided to use Google Colab, guide https://jovianlin.io/pytorch-with-gpu-in-google-colab/

# Key Components

fast.ai                    |  Google Colab             | PyTorch                    | Azure Custom Vision
:-------------------------:|:-------------------------:|:-------------------------: |:-------------------------:
![image](https://user-images.githubusercontent.com/12884292/50740212-a7b6a200-11f3-11e9-9596-74e7700ff6b0.png)  |  ![image](https://user-images.githubusercontent.com/12884292/50740222-c1f08000-11f3-11e9-9aae-c7900ac2f98d.png) | ![image](https://user-images.githubusercontent.com/12884292/50740226-ccab1500-11f3-11e9-8555-7bf46aadc51c.png) | ![image](https://user-images.githubusercontent.com/12884292/50740452-4b558180-11f7-11e9-9287-059c479ff1e5.png)


This Project was made for University of Helsinki's Deep Learning (2018) Course's Competition.

Our solution has been detailed in the report alongside all the models used and their accuracy and micro-averaged F1 scores.
The report also contains the challenges faced while data pre-processing, training and evaluations.

## Models used
* [Custom version of InceptionV1] 
* [Custom version of Resnet50]
* [Resnet18]
* [Resnet50 (pretrained)]
* [Resnet152]
* [Azure's Custom Vision] - It's a blackbox and which model is used or how the training is performed in the backend is unknown.


## Tool's used
* [Jupyter Notebook]
* [Python 3.6]
* [Numpy]
* [Pandas] 
* [Sci-Kit Learn] 
* [CUDA]
* [PyTorch]
* [Google Colab]
* [Azure Custom Vision]

And of course a lot of:
* [Coffee and Energy Drinks]

### Results

Models                |  F1 Score  | Accuracy    
:--------------------:|:----------:|:----------:
Custom Inception V1   |            |           
Custom Resnet50       |            |             
Resnet18              |    .742385 |    94.91        
Resnet50 (Pretrained) |    .697895 |             
Resnet152             |    .724525 |    94.81         

* [Graphs] 
> Resnet18

> ![image](https://user-images.githubusercontent.com/12884292/50740672-81e0cb80-11fa-11e9-94d9-b8bee54339d1.png)

> Resnet152

> ![image](https://user-images.githubusercontent.com/12884292/50740659-6d043800-11fa-11e9-80a3-9927563948a0.png)

### Azure's Custom Vision
> Results:
![image](https://user-images.githubusercontent.com/12884292/50740690-cb311b00-11fa-11e9-87d6-c88ef328e104.png)
![image](https://user-images.githubusercontent.com/12884292/50740701-15b29780-11fb-11e9-8176-7f80df59ded4.png)

Since Azure's Custom Vision provides a prediction URL, it would be used in our Future Work.



### Future Work
 - Deploy Web-based GUI for Custom Vision trained model (API's are live)
 - Add Code Comments

## Creators
1. [Stefano Lia](https://github.com/StefanoLia)
2. [Riccardo Menoli](https://github.com/rmenoli)
3. [Tafseer Ahmed](https://github.com/tafseerahmed)



