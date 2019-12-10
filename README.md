# Data Loading from AWS console
1. Parquet file loading from S3
> When you compose your code in SageMaker
2. Data loading from Athena using PyAthena

# Links
1. About SageMaker: https://aws.amazon.com/sagemaker/?nc1=h_ls
> Amazon SageMaker Studio is the first fully integrated development environment (IDE) for machine learning.
2. PyAthena: https://pypi.org/project/PyAthena/

# Installation
1. Parquet file loading from S3
```python
!conda update -n base -c defaults conda -y
!conda install -c anaconda fastparquet -y
!conda install -c conda-forge python-snappy -y
```
```python
import pandas as pd
import fastparquet as fp
import s3fs
from matplotlib import pyplot as plt
```

2. Data loading from Athena using PyAthena
```python
from pyathena import connect
import pandas as pd
```
