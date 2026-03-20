# Early pest prediction system

This project focuses on the development of a predictive model for **early pest detection** in the **Patlachique Highlands**, located in the Teotihuacán Valley. Unlike traditional monitoring methods that only trigger actions once damage is visible, this system leverages climatic variables and vegetation indices to anticipate risks and optimize agricultural decision-making for maize, bean, alfalfa, and oat crops.

## 🚀 Tech Stack

To ensure reproducibility and high-quality analysis, the project utilizes a modern, high-performance toolset. Environment and dependency management are handled exclusively with **uv**, enabling extremely fast and consistent package installation. 

The visualization and reporting component relies on **Plotly**, providing the interactive charts necessary to explore correlations between weather patterns and pest outbreaks. Finally, the documentation and presentation of results are generated through **Quarto**, allowing this repository to serve as both a development environment and a professional Data Science technical report.

## 📊 Methodology and Data

The model integrates various information sources to generate its predictions. On one hand, critical environmental variables such as temperature, relative humidity, and precipitation are analyzed. These are complemented by the use of satellite-based vegetation indices (**NDVI**) to remotely monitor plant vigor and health trends.

A fundamental pillar of this project is field validation, which is supported by historical data and empirical knowledge shared by local farmers in the region. This ensures that the model is not just a theoretical exercise, but a tool finely tuned to the specific soil and climate realities of the Teotihuacán Valley.

## 🛠️ Project Setup

If you wish to replicate this analysis, the process is straightforward thanks to the use of `uv`. First, clone the repository to your local machine. Once inside the project folder, you can synchronize all dependencies and automatically create the virtual environment by running the `uv sync` command.

To view the interactive report and model results, ensure you have Quarto installed and run `quarto preview analysis.qmd` in your terminal. This will launch a local server where you can view the final document with all Plotly charts rendered in real-time.

## 📈 Next Steps

* Refine the predictive model by implementing specialized data analysis algorithms.
* Automate NDVI data retrieval through satellite imagery APIs.
* Expand the database with more detailed seasonal records and local climate sensor data.