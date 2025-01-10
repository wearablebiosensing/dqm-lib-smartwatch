
# DQM Library for Smartwatch
## How to deploy:

1. ``` python3 -m build  ```

2. ``` python3 -m twine upload dist/* -u __token__ -p $PYPI_TOKEN ```
## Overview

The DQM (Data Quality Monitoring) library for smartwatches is designed to monitor and ensure the quality of biosensing data collected from wearable devices. This library provides tools and algorithms to assess and enhance the reliability and accuracy of the data collected from smartwatch sensors.

## Features

- **Real-time Data Quality Assessment**: Continuously monitor the quality of biosensing data in real-time.
- **Anomaly Detection**: Detect anomalies and irregularities in the data to ensure accuracy.
- **Data Cleaning**: Automatically clean and preprocess data to remove noise and artifacts.
- **Compatibility**: Compatible with various smartwatch models and sensor types.

## Installation

To install the DQM library, you can use pip:

```pip install --upgrade dqm```
## Usage 
Here is a basic example of how to use the DQM library for monitoring data quality:


from dqm_lib_smartwatch import DQM

# Initialize the DQM object
```
import dqm
# Load your smartwatch data
data = load_smartwatch_data('path_to_data_file')
# Assess data quality
 sample_rate_consistency = dqm.calculate_src(data)
# Print the quality report
print(sample_rate_consistency)
```

## Contribution
For detailed documentation and API reference, please visit the official documentation.


We welcome contributions from the community. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
Create a pull request.

