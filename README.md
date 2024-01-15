# Cycle Capture Function Code

## Instructions for Using the Cycle Capture Function in Time Series Data:

### Overview:

This function is designed to efficiently capture cycle information in time series data. It's particularly useful for analyzing patterns and periodicity in datasets represented as a Series in Python.

![alt text]([image-url](https://github.com/Zion-tunan/Capture-Cycle-in-Time-Series-Data/blob/main/Figure/Figure%20S01.png))

### Steps for Usage:

#### Data Preparation:

##### Ensure your data is in a Series format. 
This format is essential for the function to process the data correctly.

##### Normalize your time series data before applying the function. 
Normalization helps in reducing biases due to scale differences and enhances the accuracy of cycle detection.

#### Setting Parameters:

##### Filtering Threshold: 
The default threshold is set to filter out 0.02% of the data points. You can adjust this threshold based on your specific requirements to either include more data or apply stricter filtering.

##### Cycle Limits: 
You have the flexibility to set the upper and lower limits for cycle capture. This feature allows you to tailor the cycle detection to specific ranges, making it more relevant for your analysis.

### Advantages of Using this Function:

#### Customization: 
The ability to adjust filtering thresholds and cycle limits provides a high degree of customization to suit various datasets and analytical needs.

#### Efficiency: 
Designed to handle Series format data efficiently, ensuring fast and accurate cycle detection.

#### Enhanced Analysis: 
By capturing cycles accurately, this function aids in better understanding the underlying patterns and trends in your time series data, leading to more informed decision-making.

### Note: 

It's important to understand your data thoroughly before applying these settings, as different datasets might require unique adjustments for optimal results.
