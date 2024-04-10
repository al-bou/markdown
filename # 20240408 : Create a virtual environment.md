# 20240408 : Create a virtual environment in jupyter using anaconda

``` bash
conda create -n myenv
conda activate myenv
pip3 install --user ipykernel
pip3 install jupyter
python -m ipykernel install --user --name=myenv
```

---
