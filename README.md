# DVC - Dl - TF - AIOPS

## commands -

### create a new env
'''bash
conda create --prefix ./env python=3.7 -y
'''

### activate new env
'''bash
conda actiate ./env
'''

### init DVC
'''
git init
dvc init
'''

### create empty files -
'''bash
mkdir -p config src/utils
touch src/stage_01_load_save.py src/utils/all_utils.py src/__init__.py src/utils/__init__.py requirements.txt setup.py dvc.yaml params.yaml .gitignore

