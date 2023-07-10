# Comunidade DS - FTC - Food Delivery

## Ambiente virtual
```python
# 1. Criando o ambiente virtual
python3 -m venv venv_ftc

# 2. Carregando o ambiente virtual
source venv_ftc/bin/activate

# 3.1 Instalando requisitos
pip install -r requirements.txt

# 3.2 Instalando kernel para Jupyter
pip install ipykernel

# 4. Adicionando o ambiente virtual à lista de kernels
python3 -m ipykernel install --user --name=venv_ftc

# 5. Excluindo o ambiente virtual da lista de kernels
jupyter-kernelspec uninstall venv_ftc

# 6. Executando Jupyter notebook
jupyter notebook
```

Dataset: [Food Delivery Dataset - kaggle](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset)

