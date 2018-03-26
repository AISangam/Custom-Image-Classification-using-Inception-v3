# tensorflow-image-classifier
<img src="https://github.com/koflerm/tensorflow-image-classifier/blob/master/image.png?raw=true" />
Image Classification using google pretrained model inception v3 


Please follow the following steps to train your own images with google inception model
To get some technical details of this model, model is build using tensorflow library. To get knowledge about the tensorflow feel free to visit this link
https://www.tensorflow.org/
Steps to run this Program

1.) Download all the files placed under this repository.

2.) Since the size of model is more than 100 MB, so for ease I am placing here google drive link to download the inception model.https://drive.google.com/drive/folders/1VYtm25TAxT1P-YVud2n5GGSAYs8IdKWn?usp=sharing. When you will download the model using this link you will get two folder named as tf_files and training_dataset. Please place your customized images inside training_dataset 

3.) To check the working of the model with model testing image (cropped_panda.jpg) please run the python pre_model_test.py

4.) To train the model with your own images, please place the images in the training_dataset folder and run the python file python train_data.py

5.) To perform the real time testing, Please open the file test_data_pred.py and place the path of real time image you want to test as image_path = "xxxxxx"

6.) You wil get the score as the output.


Thanks for reading the instruction.

