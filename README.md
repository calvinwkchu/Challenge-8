# ETL for Amazing Prime on Movies Datasets

## Overview

The purpose of this exercise is to perform ETL on movies data obtained from Wikipedia, Kaggle and MovieLens, where we will merge all three data sets together. Upon success, we will then create an automated function where we can update the aggregated dataset on SQL.

## Brief Description of Exercises

On the first deliverable, we created a test function to load the various datasets as dataframes.

The second deliverable builds upon the first, where we perform data cleaning on the Wikipedia dataset i.e. cleaning/merging various columns, extracting string ID values as foreign keys for joining, changing/extracting & converting various data values to proper formats.

Third deliverable continues cleaning data on the Kaggle & MovieLens datasets. On the Kaggle dataset, we perform similar tasks of cleaning e.g. converting strings to proper data values, merging columns etc. We then merge the Kaggle & Wikipedia dataset using the IMBd ID's to merge and perform additional data cleaning where we remove duplicate/similar columns existing on both datasets i.e. mostly removed or merged Wikipedia columns similar to Kaggle dataset. Lastly, we perform a group/pivot on the MovieLens ratings dataset to aggregate/count all the ratings that exist for each individual movie and merge the dataset with the previous one.

Our last deliverable uploads the movies dataset we've created and also the original MovieLens dataset onto Postgres.

