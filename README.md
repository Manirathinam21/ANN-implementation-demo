# ANN-implementation-demo
ANN-implementation-demo

## important commands------------
```bash
mkdir -p src/utils
touch config.yaml
touch src/__init__.py
touch src/utils/__init__.py
touch src/utils/model.py src/utils/data_mgmt.py src/utils/common.py

pip freeze
pip list
conda env create -f environment.yml
pip install -e .("w'll install packages available in setup.py")

python src/training.py
```

## To use a yaml file
```bash
pip install PyYAML ("need to run this cmd in python complie for use yaml ")
import yaml
from src.utils.common import read_config
read_config("config.yaml")
```
## To use a TENSORBOARD File
```bash
tensorboard --logdir=logs_dir/tensorboard_logs/
```
## creating envs-----

```bash
conda create --prefix ./envs python=3.7 -y
```
### activate env

```bash
conda activate ./envs
```

## Reference -

*[conda env commands](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#)