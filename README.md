# ANN-implementation-demo
ANN-implementation-demo

## important commands------------
```bash
mkdir -p src/utils
touch config.yaml

pip freeze
pip list
conda env create -f environment.yml
pip install -e .
touch src/utils/model.py src/utils/data_mgmt.py src/utils/common.py
python src/training.py
```

## To use a yaml file
```bash
pip install PyYAML (" need to use this cmd in python complie ")
import yaml
from src.utils.common import read_config
read_config("config.yaml")
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