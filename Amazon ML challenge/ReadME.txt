Readme File for Product Browse Node Classification ML Model

Approach:
We Overall built Four Models which predict target for each column individually. Upon on 
concating predicted values in desired way, we caluclate Mode of each row of array which 
gives accurate predicted value.

Feature Engineering:
Starting with reading the data file, we assigned each column values to a new variables 
so we could preprocess them without any errors to dataframe. After dividing ech column 
we performed "CountVectorization" along with removal of stopwords which depleat the 
accuracy rate followed by "TFIDF Vectorization".So by this step we have converted our 
big data of strings into sparse matrices more precisely called as csr_matricies.

Model Training:
As we have converted our raw data into some numbers which are analyzable by 
machine learning algorithm. We choose K-NearestNeighbors Algorithm to predict 
Browse_Node_Id for the items.We trained the algorithm with "train.csv" file
which is provided for us and predicted the output for "test.csv" file.

Tools Used:
Jupyter Notebook, Google CoLab

Libraries Used:
Scikit-learn, Pandas, csv, numpy, scipy

NOTE: All Source Files Attached With The Rar File.

