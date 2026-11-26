# ADM02_Data_Science_Lab_Experiments
M. Tech Artificial Intelligence &amp; Data Science - SIMATS (ADM02 Data Science using Python Lab)


Python implementations of Data Science experiments, organized by unit. All experiments are written as Python scripts (`.py`) and run offline using synthetic datasets or datasets built into scikit-learn.

## Unit I (Lab 1)
- Experiment 1: Data Collection, Storage and Retrieval from Files
- Experiment 2: Working with Relational Databases and NoSQL Documents
- Experiment 3: Exploratory Data Analysis and Graphical Presentation
- Experiment 4: Data Cleaning and Sampling for Modeling and Validation

## Unit II (Lab 2)
- Experiment 5: Linear Regression for House Price Prediction
- Experiment 6: Logistic Regression for Customer Churn Prediction
- Experiment 7: Naive Bayes and Memorization Methods for Classification
- Experiment 8: K-Means Clustering for Customer Segmentation

## Unit III (Lab 3)
- Experiment 9: Python Data Types, Variables, Expressions, Objects and Functions
- Experiment 10: String and Array Operations
- Experiment 11: List and Tuple Operations
- Experiment 12: Set and Dictionary Operations

## Unit IV (Lab 4)
- Experiment 13: Distributed File System and Loading Data into HDFS
- Experiment 14: Word Count using MapReduce (Map, Shuffle-Sort and Reduce Phases)
- Experiment 15: Matrix-Vector Multiplication using MapReduce
- Experiment 16: Relational Join and Aggregation using MapReduce

## Unit V (Lab 5)
- Experiment 17: Line Plots, Formatting and Time-Series Trends
- Experiment 18: Choosing the Right Graph: Pie, Bar, Histogram and Box Plots
- Experiment 19: Scatterplots, Correlations and Geographic Data using Basemap
- Experiment 20: Visualizing Undirected and Directed Graphs

## Requirements
```
pip install pandas "numpy==1.26.4" scikit-learn matplotlib seaborn networkx openpyxl "basemap==1.4.1"
```

## Usage
1. Install the required libraries listed above.
2. Run the required experiment, e.g. `python exp01.py`, to view the execution and output.
3. Unit IV experiments (13–16) run in plain Python without Hadoop. They can also be run as Hadoop Streaming jobs, e.g. `type input.txt | python exp14.py map | sort | python exp14.py reduce`.
