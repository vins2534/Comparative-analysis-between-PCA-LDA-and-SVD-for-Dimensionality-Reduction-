# Forest Cover Type Prediction with Dimensionality Reduction

This repository contains code and resources for predicting forest cover types based on cartographic variables, with a primary focus on dimensionality reduction techniques such as Principal Component Analysis (PCA), Singular Value Decomposition (SVD), and Linear Discriminant Analysis (LDA).

## Dataset Description

The dataset used in this project consists of various cartographic variables derived from US Geological Survey (USGS) and US Forest Service (USFS) data. It includes attributes such as elevation, aspect, slope, distances to hydrology and roadways, hillshade indices, as well as binary indicators for wilderness areas and soil types. The dataset covers four wilderness areas located in the Roosevelt National Forest of northern Colorado.

## Problem Statement

The goal of the project is to predict the forest cover type based on the provided cartographic variables. The forest cover types are determined from USFS Region 2 Resource Information System (RIS) data and are influenced by ecological processes within each wilderness area, such as elevation, species composition, and human-caused disturbances.

## Dimensionality Reduction Techniques

### Principal Component Analysis (PCA)

PCA is a dimensionality reduction technique used to reduce the number of features in a dataset while preserving most of its variance. It works by transforming the original features into a new set of orthogonal components called principal components. In this project, PCA will be applied to reduce the dimensionality of the dataset and extract the most informative features.

### Singular Value Decomposition (SVD)

SVD is another dimensionality reduction technique that decomposes a matrix into three matrices, which can be used to approximate the original matrix with reduced rank. It has applications in various fields, including image processing, recommendation systems, and data compression. In this project, SVD will be explored as an alternative method for dimensionality reduction.

### Linear Discriminant Analysis (LDA)

LDA is a supervised dimensionality reduction technique commonly used for classification tasks. It works by finding the linear combinations of features that best separate the classes in the dataset. Unlike PCA, which focuses on maximizing variance, LDA aims to maximize class separability. In this project, LDA will be evaluated for its effectiveness in reducing the dimensionality of the dataset while preserving class discriminative information.
