# Weekly TV sales forecasting using time series decomposition with irregular seasonality

This repository contains the Python code and data used in the paper:

"Weekly TV sales forecasting using time series decomposition with irregular seasonality"  
Arthur Matsuo Yamashita Rios de Sousa, Daisuke Ando, Junichi Ozaki, Yohei Shida, Qianyun Wu, Yixuan Y. Zheng, Zhihua Zhong, Rie Maskawa, Jiwei J. Jiang, Kay Nagayama, Hideki Takayasu and Misako Takayasu.  
*International Journal of Forecasting*, 2025. DOI: https://doi.org/xxxxx/xxxxxxx  
Preprint available at https://www.researchgate.net/publication/xxxxxxxx

Abstract: In the practice of sales forecasting, simplicity and interpretability are as important as high accuracy. Here, we use time series decomposition to construct a simple and interpretable forecasting method for weekly Sony TV sales in the United States. The main challenge is to properly address irregular seasonality arising from the way a year is divided into weeks and from floating holidays and events. As a solution, we propose the concept of `analogous weeks', a general framework for grouping weeks that are similar according to some criteria, which encodes seasonality and already accounts for calendar effects. By incorporating this notion in the time series decomposition and forecasting, we achieved an average annual relative error of less than 10% for the 1-week-ahead forecast and less than 15% for forecast horizons of up to 26 weeks, outperforming other comparable seasonal models.

## Contents

- `tv_week_forecast.ipynb` — basic Jupyter notebook to replicate results of the proposed forecasting method  
- `weekly_sales.csv` — weekly TV sales dataset (masked as described in the paper)

## How to Run

Open `tv_week_forecast.ipynb` in Jupyter Notebook and run all cells from top to bottom (`weekly_sales.csv` should be in the same directory).  
Requirements: Python 3.8+, Jupyter Notebook, standard Python libraries (numpy, pandas, datetime, matplotlib).

## License

- Code: MIT License (see `LICENSE`)
- Data: CC BY-NC 4.0 (see `LICENSE-DATA`)

## Citation

A. M. Yamashita Rios de Sousa, D. Ando, J. Ozaki, Y. Shida, Q. Wu, Y. Y. Zheng, Z. Zhong, R. Maskawa, J. J. Jiang, K. Nagayama, H. Takayasu and M. Takayasu. "Weekly TV sales forecasting using time series decomposition with irregular seasonality." *International Journal of Forecasting*, vol. xx, pp. xxxx-xxxx, 2025.

```bibtex
@article{yamashita2025,
  title={Weekly TV sales forecasting using time series decomposition with irregular seasonality},
  author={A. M. Yamashita Rios de Sousa and D. Ando and J. Ozaki and Y. Shida and Q. Wu and Y. Y. Zheng and Z. Zhong and R. Maskawa and J. J. Jiang and K. Nagayama and H. Takayasu and M. Takayasu},
  journal={International Journal of Forecasting},
  volume={xx},
  pages={xxxx--xxxx},
  year={2025}
}
