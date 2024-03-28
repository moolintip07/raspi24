# **Human Emotion Recognition with the Raspberry Pi**

Dataset we used + more we did ourselves: [FER2013 dataset](https://www.kaggle.com/ashishpatel26/facial-expression-recognitionferchallenge). - referece machine learning folder

Three scripts/classes, reference ```predictor.py```in the ```machineLearning```folder, and ```photoApp.py``` and ```photoDriver.py```. 

Instructionss:

- create an output folder
cd into the repo, and then install all libraries using: ```pip install -r requirements.txt```. 

After installing all of the libraries: ```python3 photoDriver.py --output [output_folder_name]```. Please note that ```[output_folder_name]``` - name of folder you created btw

Note: When running the application, you may receive Tensorflow-GPU errors - GPU IS NOT NEEDED!!! 


Due to Tkinter's widget placement styles - app must be viewd in full window pls

red button - used to take photo and predict emotion
green button - will give the spotify playlist to listen to
