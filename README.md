Short project containing example of using PCA on dataset including informations about Premier League players in 19/20 season.</br>
To check PCA outcome in case of classification task, 2 classification models were made - using weighted nearest neighbor and random forest algorithms.</br>
Simple and short comparison between this models based on 'pca data' and unchanged data with 7 variables chosen via SelectKBest function showed that models trained on 'pca data' was a  worse than those trained on unchanged data, the difference was significant, especially for random forest model.</br> 
Although PCA didn't turn out as a good solution in case of classification task for this dataset, it is still powerful tool when it comes to dimensionality reduction. One of it's most common application is high-dimensionality datasets visualization. At the end, 3D visualization of dataset after using PCA was included.
</br></br>
Data set source: https://fbref.com/en/
