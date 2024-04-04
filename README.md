# WeightData 
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## About The Project

This project is a personal journey into health data analytics, focusing on weight and body composition metrics. By harnessing the power of the Renpho scale API, I've developed a system that uses an LSTM model to predict future weight trends based on historical data. This endeavor not only showcases the potential of machine learning in personal health management but also provides a blueprint for similar applications.

### Features

- **Data Collection**: Automatic retrieval of weight and body fat percentage data from the Renpho scale API.
- **Data Analysis**: Utilizes LSTM models to analyze and predict weight trends.
- **Visualization**: Includes a Jupyter notebook for visualizing data trends and prediction results.

![image](https://github.com/antoinebou12/WeightData/assets/13888068/46dfc7c0-173d-4be7-b348-dadfd0d42a8c)
![image](https://github.com/antoinebou12/WeightData/assets/13888068/5df1d580-2759-4cc3-9d6e-64c1aa2bfffc)


### Built With

This project is built with a focus on Python and its powerful libraries, facilitating efficient data processing and machine learning model development.

- Python 3.8+
- FastAPI
- TensorFlow/Keras for LSTM model
- Pandas for data manipulation
- Matplotlib for data visualization

## Getting Started

To explore this project and perhaps adapt it to your personal health data analytics, follow the instructions below.

### Prerequisites

Ensure you have the following installed on your machine:
- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/antoinebou12/WeightData.git
   ```

2. **Navigate to the project directory:**
   ```
   cd WeightData
   ```

3. **Install the required Python libraries:**
   ```
   pip install -r requirements.txt
   ```

## Usage

To start analyzing your weight data:

1. **Collect your data** using the Renpho scale and ensure it's accessible via their API.

2. **Run the Jupyter notebook** `weight.ipynb` to process your data through the LSTM model and visualize your weight trends and predictions.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions to enhance this project or extend its capabilities are **greatly appreciated**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
