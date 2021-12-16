# Detecting-face-emotion-using-CNN
A Deep Learning based end to end project of detecting emotion of human face using Facial expression detection dataset from kaggle. Here I used a CNN model and trained it to predict the facial expression. And to make this preject interactive i followed two strategy. First i made a web app using Flask(backend) and basic html(frontend). And Secondly use computer vision to make it real time.

## Web app running in the local host.
![Web app](https://github.com/Sudhakordas/Detecting-face-emotion-using-CNN/blob/master/Image/Web-1.JPG)
![Web app](https://github.com/Sudhakordas/Detecting-face-emotion-using-CNN/blob/master/Image/Web-2.JPG)

## Real time facial emotion detection using the Computer Vision.
![real time](https://github.com/Sudhakordas/Detecting-face-emotion-using-CNN/blob/master/Image/3-2.JPG)
![real time](https://github.com/Sudhakordas/Detecting-face-emotion-using-CNN/blob/master/Image/3idiot1.JPG)

## Step by step workflow 
1. First i download the [dataset](https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset) from kaggle.
2. Load and preprocess the data.
3. Made my CNN model.
4. Train and evaluate the model.

## How to run this project in your system.
1. Down load or clone the repository
$ git clone https://github.com/Sudhakordas/Detecting-face-emotion-using-CNN.git
2. Create a new environment.
3. Activate that environment 
 ```python
conda activate environment_name
```
4. Install all the denpendencies.
```python
pip install  -r requirements.txt
```
5. Now run the project.
 ### To run the web app.
 Go to the directory where you have clone the repository.
 Type python app.py .
    
### To run it real time.
  just run the Emotion detection using Computer Vision.ipynb file in your Jupyter Notebook ide.
 
