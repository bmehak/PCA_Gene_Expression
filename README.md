# PCA on Gene Expression

## Objective

To analyze gene expression data and visualize patterns using PCA.

## Tasks

1. Scatter plot of XBP1 vs GATA3
2. PCA projection onto PC1

## Dataset

* 105 breast cancer samples
* Labels: ER+ (1), ER- (0)

The dataset used is from GEO: GSE5325.

Files used:

* filtered.tsv.gz
* columns.tsv.gz
* class.tsv

Due to large size, dataset is not included in this repository.


## Results

* Scatter plot shows separation between classes
* PCA captures main variance in PC1

## Key Challenge

The dataset required preprocessing due to inconsistent formatting (extra spaces and metadata rows).

## Tools

* Python
* Pandas
* Matplotlib
* Scikit-learn
