# Music-Genre-Classification-using-KNN
The project uses K-Nearest Neighbor for music genre classification

# Dataset
The dataset used for training and testing purpose is the [GTZAN](http://marsyas.info/downloads/datasets.html) Audio dataset. It consists of a total of 1000 audio samples pre-classified into 10 main categories, as:-
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

Each of these category folder contains 100 audio sample in it. And the size of dataset is about 1.2 GigaBytes. 

The Project file "KNN.ipynb" is a jupyter notebook originally created on google colab. The colab notebook has a sequence of code cells for defining the KNN functions, train test dataset split and storing the data model in a binary data file. Currently we are able to achieve about 72% accuracy with 5 neighbors.
