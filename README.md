# MSc_Project_1
## Project Title 
<div align="justify">
  
**Dynamic Analysis of Reserve Money Components and Sources: Evaluating RBI's Monetary Policy Impact through Time Series Modeling!** <br>

This study aims to analyze the components and sources of Reserve Money in India, focusing on data provided by the Reserve Bank of India (RBI).

</div>

## Table of Contents
- [Introduction](#introduction)
- [Purpose](#purpose)
- [Methodology](#methodology)
- [Data Overview](#data-overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)


### Data Overview

<div align="justify">
  
  The dataset utilized in this study originates from the Reserve Bank of India's (RBI) weekly financial statements, capturing a detailed breakdown of Reserve Money and its various components. Reserve Money, often referred to as high-powered money, serves as the foundation of the monetary supply in an economy, and understanding its components is vital for analyzing monetary policy impacts.

</div>

## Project Structure
.
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks for analysis
├── src/                    # Source code for time series modeling
├── results/                # Output files such as plots, models, etc.
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
└── LICENSE                 # License for the project


### Methodology

<div align="justify">
  
  *i)* The study uses time series analysis to investigate the dynamics of Reserve Money components, including currency in circulation, bankers' deposits with RBI, and other deposits with RBI.<br>
  *ii)* ARIMA (Auto Regressive Integrated Moving Average) modeling is employed to forecast future values of Reserve Money components.<br>
  *iii)* STL (Seasonal Decomposition of Time Series) is used to decompose the time series data to identify and analyze seasonal patterns within the Reserve Money components.<br>
  *iv)* VAR (Vector Autoregression) is applied to explore causal relationships between the RBI's claims on the government, banks, and the commercial sector.<br>
  *v)* PCA is used to identify the key factors driving changes in Reserve Money, helping to reduce dimensionality and focus on the most significant components.

</div>
