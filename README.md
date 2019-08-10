# Binary classification
Basic knowledge required is C,C++ and Python 
If we have Problem like Yes/No, white/Black, Cat/Dog...etc. while you have only two options at that time you can use this Binary classification 

Architecture: LeNet5
Framework: Keras (Tensor flow Background)

How to Train your Own Neural Network. Means when you give any image to model that give output as a Probability. Let’s take an example:
I take very famous example that classify weather it's a Cat or Dog. so while you give an image of Dog or cat to trained model that time model give Output as a Probability of cat and Probability of dog. 

Required things:

  1) A good Dataset (With Label)
  2) A Good CPU or you can use Google co-lab
  4) If you use CPU than you need to install bellow mention library
                
                python3.5
                numpy 
                tensorflow 
                opencv2
                keras.preprocessing.image 
                keras.models 

Note:
I prefer to use Spider IDE (for that you need to install Anaconda to your system) and Google Colab (but take care if you cloase colab for more than some time than google will erase everything from the CPU(Not from google drive) )

Let’s start 

Step 1: (Make Dataset strong)

	Let’s take a look at Dataset
  
      1)	You have cat images and Dog images booth should in Different folder i.e. Cat and Dog 
      2)	Both folders have Minimum 100 images. If we have more Dataset than we can make strong Model. For that we need to augment data (Rotate, flip, Blur…etc.) because of that we can make strong model so let’s start augmentation. Here I use Google colab for that 
           1)	1st you need to Upload this image folder.rar on google drive and augumentation.ipynb on colab           
           2)	Open augumentation.ipynb on GoogleColab and your path of fail there and run it it about code how its work I mention in code as a comment 
           3)	Download augment images and  store in same way 
  
Step 2: (Train your model)

	Let’s Train and Test our model
  
      1)	Upload image-classification-keras.rar file on google Drive it must contain images folder which you have made and Upload Binary Classification.ipynb also. Give path of your image-classification-keras.rar file and run it 
      2)	For test you have to upload one more folder which have dog and cat mixed images (image name can be anything )  give name as a test and make it rar and upload it  and again run that test part 
      3)	My suggestion is if you getting good probability than download it to your local system from google colab 

