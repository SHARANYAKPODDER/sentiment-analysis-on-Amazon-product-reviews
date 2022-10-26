

"Sentiment Analysis and Classification Project using Amazon dataset and using ML and DL models."
Here, I am specifically mentioning that you have to install the pandas_profiling from colab only because its not working in Jupyter.
you have to run this code snippet in colab,

!pip install -U pandas-profiling --user
!pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip
import pandas_profiling
from pandas_profiling.report.presentation.flavours.html.templates import create_html_assets

