![Logo](https://github.com/bycnfz/weather2k/blob/main/logo.png)

# Weather2K: A Multivariate Spatio-Temporal Benchmark Dataset for Meteorological Forecasting Based on Real-Time Observation Data from Ground Weather Stations

【Accepted】by **the 26th International Conference on Artificial Intelligence and Statistics (AISTATS) 2023**

<a href='[https://arxiv.org/abs/2409.17508](https://arxiv.org/abs/2302.10493)'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>  [![GitHub repo](https://img.shields.io/badge/github-repo-green)](https://github.com/Xun-Zhu/weather2k/)  [![Hugging Face](https://img.shields.io/badge/HuggingFace-Dataset-yellow)](https://huggingface.co/datasets/BUPT-PRIS-727/Weather2K)

## Download the dataset

This is the open-source version (after necessary adjustments and checks) of the Weather2K dataset: https://huggingface.co/datasets/BUPT-PRIS-727/Weather2K

The shape of the numpy file of Weather2K-R is (1866, 13, 13632), which means 1,866 groud weather stations, 3 constants for position information and 10 meteorological factors, and 13,632 time steps with 3-hour time resolution (Time coverage range: January 1, 2017- August 31, 2021).



|  Numpy Index   | **Long Name**                             | **Short Name**         | **Unit** |
| :------------: | :---------------------------------------- | :--------------------- | :------: |
|       0        | Latitude                                  | lat                    |   (°)    |
|       1        | Longitude                                 | lon                    |   (°)    |
|       2        | Altitude                                  | alt                    |   (m)    |
|       3        | Air pressure                              | ap                     |   hpa    |
|       4        | Air Temperature                           | t                      |   (°C)   |
|      5/6       | Maximum / Minimum temperature             | mxt / mnt              |   (°C)   |
|       7        | Relative humidity                         | rh                     |   (%)    |
|       8        | Precipitation in 3h                       | p3                     |   (mm)   |
|       9        | Wind direction                            | wd                     |   (°)    |
|       10       | Wind speed                                | ws                     | (ms<sup>-1</sup>) |
|       11       | Maximum wind direction                    | mwd                    |   (°)    |
|       12       | Maximum wind speed                        | mws                    | (ms<sup>-1</sup>) |

If you have any quesetions about the data download, please contact wuming@bupt.edu.cn



## Archive

- [Weather2K v1.0](https://github.com/Xun-Zhu/weather2k/tree/v1.0.0)


## Cite

If you are using this dataset please cite 
> Zhu X, Xiong Y, Wu M, et al. Weather2K: A Multivariate Spatio-Temporal Benchmark Dataset for Meteorological Forecasting Based on Real-Time Observation Data from Ground Weather Stations[C]//International Conference on Artificial Intelligence and Statistics. PMLR, 2023: 2704-2722.
