# Unsupervised-Topic-Modeling

### Data Analysis
Dataset : [Click here to view the dataset](https://github.com/praatibhsurana/Unsupervised-Topic-Modeling/blob/main/data.csv) \
The dataset provided consists of roughly 10,000 unlabeled garage reviews. You can check out the [Data Analysis notebook](https://github.com/praatibhsurana/Unsupervised-Topic-Modeling/blob/main/Data%20Analysis_1.ipynb) for a basic analysis of the data.

### Approach
The dataset provided has unlabeled data. The task at hand is to classify this data into different topics. Now the first thing that needs to be done is to segregate the data into various topic clusters. This is an unsupervised topic modeling problem and we will make use of the Latent Dirichlet Allocation (LDA) algorithm to generate topic clusters for our data. \
The LDA algorithm has been implemented in the [LDA Model notebook](https://github.com/praatibhsurana/Unsupervised-Topic-Modeling/blob/main/LDA_Model_2.ipynb).

### Predictions 
Predictions were made by carefully mapping the topics from the evaluation_labels.MD file to the LDA generated topics. The [Prediction notebook](https://github.com/praatibhsurana/Unsupervised-Topic-Modeling/blob/main/Predictions_3.ipynb) consists of a brief explanation regarding the prediction and ideas employed.

### Setup
**Clone the repo and navigate to it**
```bash
git clone https://github.com/praatibhsurana/Unsupervised-Topic-Modeling.git
cd Unsupervised-Topic-Modeling
```

### Installing requirements
**Install all requirements using pip and open up Jupyter notebook**
```bash
pip install -r requirements.txt
jupyter notebook
```


