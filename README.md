# Lisence Plate detection and storage system

# Abstract 
 (Sam insert)
 
# Tech Stack
 
# How to run?

Train the model in your system 

Switch directory using cd command in your command prompt and switch to the directory of the project 

Then paste the following command and run, the model will take a while to train 

python Tensorflow\models\research\object_detection\model_main_tf2.py --model_dir=Tensorflow\workspace\models\my_ssd_mobnet --pipeline_config_path=Tensorflow\workspace\models\my_ssd_mobnet\pipeline.config --num_train_steps=10000

Run all the cells of the main.ipynb and tweak with the test set image number to try out on different outputs. Test with the camera ourput as well by running the "Real time testing" 

# Results

![image](https://user-images.githubusercontent.com/73779567/138905258-74307c4b-1f75-40cf-ae32-62a32d0f3302.png)

The OCR text is obtained from the plate. The cropped Images of the number plate are stored in a separate folder and the registration number is stored in a csv file along with a unique identification number 

![image](https://user-images.githubusercontent.com/73779567/138908602-b55e3f01-c65b-42c0-a3b9-ff1f2c97233a.png)

