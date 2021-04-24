# Music-Genre-Classification-using-KNN
The project uses K-Nearest Neighbor for music genre classification

# Dataset
The dataset used for training and testing purpose is the [GTZAN](http://marsyas.info/downloads/datasets.html) Audio dataset.The dataset consists of 1000 audio tracks each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format. The genres in dataset are:-
1. Blues
2. Classical
3. Country
4. Disco
5. Hip-Hop
6. Jazz
7. Metal 
8. Pop
9. Reggae
10. Rock

The size of the dataset is about 1.2 GigaBytes. 

# Jupyter Notebook
The Project file "KNN.ipynb" is a jupyter notebook originally created on google colab. The colab notebook has a sequence of code cells for defining the KNN functions, train test dataset split and storing the data model in a binary data file. Currently we are able to achieve about 72% accuracy with 5 neighbors. More details and explanations to each function are commented in the notebook itself.

# Code Execution:-
Before executing the code , make sure you have the following python packages installed:-
* Numpy
* Scipy
* Pandas
* Scikit-learn
* Librosa
* Matplotlib
* Pydub

1. Download the zip file -> extract its content -> run jupyter notebook in Anaconda environment or [Google Colab](https://colab.research.google.com/)
2. Or else run the following code in terminal to download the project folder to your system. Or in a colab notebook cell to copy the folder to google drive:-
``` 
git clone https://github.com/HetGalia/Music-Genre-Classification-using-KNN.git 
```

