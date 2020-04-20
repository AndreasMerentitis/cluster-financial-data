# Clustering for financial data demo

The goal is to get, cluster and visualize stock market data. The initial version
is a small adaptation of the classic example from the first source, adding visualization
with UMAP embeddings. 

The dataset is derived using yfinance. The example is tested using python 3.8. 
You can run the demo either directly (natively) or use repo2docker to configure 
and run in docker.

```bash
# Example usage (natively): 
$ pip install -r requirements.txt
$ jupyter notebook 
```

```bash
# Example usage (in docker): 
$ sudo service docker restart
$ jupyter-repo2docker https://github.com/AndreasMerentitis/cluster-financial-data
```
After this step copy the link that will be produced to your web browser and run the example from there

![relative path 1](/Clustering_2001_2008.jpeg?raw=true "Clustering_2001_2008.jpeg")
![relative path 1](/UMAP_embedding.jpeg?raw=true "UMAP_embedding.jpeg")

# Using data and extending the basic idea from these sources:
* Gael Varoquaux's agglomerative clustering example from previous versions of scikit learn 
* https://github.com/erykml/medium_articles/blob/master/Quantitative%20Finance/downloading_stock_prices.ipynb

