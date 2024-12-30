# AI4I-2020-Predictive-Maintenance-Dataset
# Machine Predictive Maintenance Classification Dataset

Predictive maintenance datasets are often challenging to obtain, especially in a form suitable for public use. To address this, we provide a synthetic dataset designed to closely reflect the predictive maintenance scenarios commonly encountered in industry.

This dataset contains 10,000 data points, with each row representing an individual observation and 14 features represented as columns.

Features:
1. UID:  A unique identifier ranging from 1 to 10,000

2.ProductID: A combination of a letter (L, M, H) representing low, medium, and high product quality variants (50%, 30%, and 20% distribution respectively), followed by a variant-specific serial number

3.Air temperature [K]: Generated using a random walk process and then normalized to have a standard deviation of 2 K around 300 K

Process temperature [K]: Generated with a random walk process and normalized to a standard deviation of 1 K, then combined with the air temperature plus 10 K
   
5.Rotational speed [rpm]: Derived from a power value of 2860 W, with added normally distributed noise
6.Torque [Nm]: Normally distributed around 40 Nm with a standard deviation of 10 Nm, ensuring no negative values
7.Tool wear [min]: The tool wear for each product quality variant (H/M/L) is added 5/3/2 minutes, respectively, for the used tool during the process
8.Machine failure label: Indicates whether the machine has failed at this particular data point based on one or more failure modes

This dataset aims to offer a realistic, synthetic representation of predictive maintenance data to facilitate research and development in machine learning and predictive maintenance systems.

