# Cryptocurrencies

## Table of Contents
- [Overview of Project](#OverviewProject)
- [Results](#Results)
- [Summary](#Summary)
- [Resources](#Resources)

## <a name="OverviewProject"></a>Overview of Project

We will be using unsupervised learning to create a model for cryptocurrency data [[2]](#2)[[3]](#3). The main purpose is to clean the data, ensure they are all trading in the market, and group them into clusters. We used Kmeans and PCA for our analysis [[1]](#1)

## <a name="Results"></a>Results

Reference [[1]](#1) to see the results of our data analysis.

<p align="center"> <img src="Resources/PCA.png" width ="50%" alt="PCA"> </p>
<p align="center"> Figure 1: PCA Table</p> 

<p align="center"> <img src="Resources/ElbowCurve.png" width ="50%" alt="ElbowCurve"> </p>
<p align="center"> Figure 2: Elbow Curve</p> 

<p align="center"> <img src="Resources/3D.png" width ="50%" alt="3D"> </p>
<p align="center"> Figure 3: 3D Plotting with 3 Most Important Features from PCA</p> 

<p align="center"> <img src="Resources/ScatterPlot.png" width ="50%" alt="ScatterPlot"> </p>
<p align="center"> Figure 4: Total Coul Supply vs Total Coins Mined Scaled Values</p> 

## <a name="Summary"></a> Summary

We grouped the data into 4 clusters, based on our Elbow Curve results. There doesn't seem to be a clear relationship between the TotalCoinSupply and the TotalCoinsMined for the different cryptoc currencies.  

## <a name="Resources"></a>Resources

<a name="1">[1]</a> [Cryptocurrency Code](https://github.com/tamiespinosa/Cryptocurrencies/blob/main/crypto_clustering.ipynb)

<a name="2">[2]</a> [Cryptocurrency Data CSV](https://github.com/tamiespinosa/Cryptocurrencies/blob/56324a0e25bc3ad9c95cb3f569fa8aedd12a539d/Resources/crypto_data.csv)

<a name="3">[3]</a> [Data Source](https://min-api.cryptocompare.com/data/all/coinlist)

[4] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
