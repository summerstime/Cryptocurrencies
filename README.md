# Cryptocurrencies

## Objective
* Cryptocurrency is analyzed using unsupervised machine learning. The results of this analysis are to be shared with the board of Accountability Accounting by Martha, a senior manager.


## Results
* The data was not ideal and required scaling and transforming in order to process it.
* Only those cryptocurrencies that are currently traded were included in the data.
* Get_dummies was utilized to clearly identify different aspects of the data, such as different algorithms.
* StandardScaler and MinMaxScaler were also used to scale the data so that comparisons could be made more easily.
* KMeans was utilized to determine the number of clusters (class) for the data to be grouped.
* Several iterrations were completed and principal components were determined. There were 3 in total. 
* 3D Scatter Plot
![3D Scatter Plot](https://github.com/summerstime/Cryptocurrencies/blob/main/images/PCAplot.png)


* The 2D scatter plot shows the number of coins mined to number of coins supplied. Both values have been scaled using MinMaxScaler.
* 2D Scatter Plot
![2D Scatter Plot](https://github.com/summerstime/Cryptocurrencies/blob/main/images/PlotSupply-Mined.png) 

## Summary
* Further investigation/research is needed to provide a more rounded look at cryptocurrencies. This initial analysis helps start that process.