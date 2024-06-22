# Quantitative Evaluation of ChatGPT's Impact on NVIDIA Stock Prices

This project analyzes the impact of the introduction of ChatGPT on NVIDIA's stock prices using the Regression Discontinuity Design (RDD) method. The analysis spans from July 11, 2010, to May 26, 2024, and incorporates data on NVIDIA's stock prices, Bitcoin price, and NASDAQ index price.

## Table of Contents

-   [Introduction](#introduction)
-   [Data](#data)
-   [Methodology](#methodology)
-   [Results](#results)
-   [Conclusion](#conclusion)
-   [Limitations](#limitations)
-   [Future Work](#future-work)
-   [Contributors](#contributors)
-   [References](#references)

## Introduction {#introduction}

NVIDIA's graphics chips are used in various sectors including gaming, scientific research, and professional graphics. The rise of AI technologies, especially ChatGPT, which relies on NVIDIA hardware, could have significantly impacted NVIDIA's stock prices. This project aims to analyze this relationship.

## Data {#data}

The data used in this project comes from the Stooq database and includes:

-   **NVIDIA stock prices**: Weekly time series data from July 11, 2010, to May 26, 2024.
-   **Bitcoin price**: Weekly opening prices from the same period.
-   **NASDAQ index price**: Weekly opening prices from the same period.

## Methodology {#methodology}

We employed the Regression Discontinuity Design (RDD) method to analyze the impact of ChatGPT's introduction on NVIDIA's stock prices. The analysis includes the following steps:

1.  **Data Cleaning**: Merging datasets from Stooq into a single table.
2.  **Descriptive Analysis**: Examining the distribution and correlation of variables.
3.  **ARIMA Models**: Implementing ARIMA models to eliminate the influence of past values.
4.  **Robustness Checks**: Ensuring the validity of results.

## Results {#results}

-   **Initial Impact**: ChatGPT initially negatively impacted NVIDIA's stock prices.
-   **Long-term Impact**: Positive impact on NVIDIA's stock prices after an adaptation period.
-   **Bitcoin Influence**: Not statistically significant.
-   **NASDAQ Influence**: Significantly affects NVIDIA's stock prices.

## Conclusion {#conclusion}

The introduction of ChatGPT had a notable impact on NVIDIA's stock prices, demonstrating the influence of emerging AI technologies on the tech market. The NASDAQ index also plays a crucial role in NVIDIA's stock performance, highlighting the importance of overall market conditions.

## Limitations {#limitations}

-   The analysis focuses narrowly on NVIDIA and does not consider competitors like AMD or Intel.
-   Weekly data may not capture short-term market fluctuations.

## Future Work {#future-work}

-   Examine ChatGPT's long-term impact on NVIDIA.
-   Compare the impact on NVIDIA with its competitors.
-   Predict how emerging technologies like augmented reality (AR) and virtual reality (VR) may impact NVIDIA.

## Contributors {#contributors}

-   Gabriel Chrostowski
-   Aleksandra Patelska
-   Aleksandra Szydłowska
-   Patryk Hytry
-   Klaudia Badzyńska
-   Weronika Forszpaniak

## References {#references}

-   NVIDIA Corporation (2021)
-   Deloitte (2022)
-   Brown et al. (2020)
-   Jouppi et al. (2017)
-   NVIDIA Corporation (2020)
