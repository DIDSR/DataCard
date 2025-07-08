# DataCard
Regulatory Science Tool for Evaluating and Reporting the Quality of Patient Datasets

> [!NOTE]
> **This code is work-in-progress.**

## Overview

Datacard Examines submitted images for artifacts and provides a scorecard with descriptive and quantitative measures of dataset quality including image quality, metadata, and annotation quality for both mammography and histopathology whole slide images.
![DataCard Output](./imgs/DataCardOutput.png)


## DataCard Generation

An outline of Datacard pipeline is given below.
![DataCard Pipeline](./imgs/DataCardGeneration.png)


## DataCard is based on 4C dimmentione shown below 

### Dimentions
There are 4 main dimentions in the DataCard
1.	Correctness: Correctness refers to the accuracy of the recorded data, including the medical images, the disease labels, and patient metadata.​.
2.	Completeness: Completeness refers to the proportion of samples that contains all associated data and metadata values.
3.	Coverage: Coverage refers to the amount and variety of data along different factors of variation.
4.	Consistency: Consistency refers to the uniformity of data quality across different subgroups and collection sites.

An outline of Datacard 4C is given below.
![DataCard 4C](./imgs/DataCard4C.png)
