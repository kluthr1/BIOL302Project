# Karan Luthria and Aris Stovall BIOL302L Project

## Instructions:

Use this  [Google Collab Notebook](https://colab.research.google.com/drive/1JN-zKgyJDfU3Q2AMg_rzQ7QpT8Zyzrne?usp=sharing) to try to predict your phage's genome size.

`AnnotatedPhageList.csv` contains a .csv file of all the annotated phages. This includes the 95 phages whose phage capsid length, capsid width, and tail length were measured. 

`UnannotatedPhageList.csv` contains a list of TEM images and phages whose genome size is known based on data avalible on PhagesDB. This list is later annotated in AnnotatedPhageList.csv

`PhageDB Search of Siphoviruses.ipynb` contains the python code used to generate `UnannotatedPhageList.csv` through searching phagesDB. Click here to see how we collected the 94 phages used to train the model

`Linear Regression Model Code.ipynb` contains the python code used to generate figures and compute the genome size of phagesDB after annotating the phages in `AnnotatedPhageList.csv` Click here to learn more about how we trained our model and generated the figures you see on our poster.
