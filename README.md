# Music-Classification_Machine_Learning_BR
For this project I will build a machine learning pipeline that will predict the genre of a music file ('.wav'). My project
begins by downloading the dataset from Kaggle to my AWS s3 bucket however due to difficulties I could not access the dataset 
through my s3 bucket. Some difficulties I faced were properly unzipping the files, accessing the correct files and also getting 
the python code to correctly work on the EC2 instance. For the main parts of my project, I have completed them in Jupyter Notebook
using Python3. 

Included are 2 Jupyter Notebook files. Music_Project_2 was the first iteration of my project and attempted to use the classification
method of K Nearest Neighbors to make predictions of the genre label. I was able to build a pipeline through Python3 however I was not
able to implement Pyspark to this model and therefore needed to use a different classification method.

The second Jupyter Notebook file, Final_Librosa_Project uses different python packages dedicated to extracting features from audio files such as 
librosa. By using RandomForest classification, I was able to implement Pyspark to the model. Although the final pipeline was not very accurate, 
I was able to build a pipeline that used extracted features to make predictions

From the visualizations we can see how effective the final model was with the confusion matrix. The final visuals displayed mfcc, the main extracted 
features from the audio files. From this project I learned alot of building machine learning pipeline and the many difficulties that come with it but
also had lots of fun working on this project.
