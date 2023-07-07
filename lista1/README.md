# Lista 1

1. Qual o valor da informação armazenada na linha 30 e na coluna 10?
2. Selecione as linhas 0 a 20 e as colunas 0 a 2
3. Seleciona as linhas 5 a 30 e a coluna “Delivery_person_Age”
4. Selecione as linhas 40 a 42 e as seguintes colunas: “Restaurant_latitude”,
“Restaurant_longitude”, "Delivery_location_latitude”,
“Delivery_location_longitude”
5. Qual a menor data de entrega da coluna “Order_Date” entre as linhas 0 a
50?
6. Qual a menor data de entrega da coluna “ Time_Orderd ” entre as linhas
0 a 50?
7. Quais os nomes únicos da coluna “City” entre as linhas 50 e 70?
8. Quais os nomes únicos da coluna “Weatherconditions” entre as linhas 0 e
10?
9. Quais os tipos de densidade de trânsito presente na coluna
“Road_traffic_density” entre as linhas 0 a 20?
10. Qual o ID do entregador de comida mais velho entre as colunas 50 e 70?
11. Qual o ID do entregador de comida com a melhor avaliação de entrega entre as colunas 50 e 70?
12. Quais os tipos de veículos utilizados pelos entregadores entre as inhas 0 a 30?
13. Quais os tipos de pedidos único que foram entregues entre as colunas 100 e 120?

# Sumário de comandos

## Importação de biblioteca 
* Pandas

```python
import pandas as pd
```

## Carregamento de dataframe de arquivo .csv
* read_csv

```python
df = pd.read_csv("../dataset/train.csv") 
```



## Visualização de dataframe
```python
df
```
### Tipo das colunas: [df.dtypes](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dtypes.html)
```python
df.dtypes
```





## Seleção 
### por index: [df.iloc](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.iloc.html)
```python
df.iloc[30,10]
```
#### de intervalo de dados
```python
df.iloc[:21, :3]
```
### por *labels*: [df.loc](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.loc.html)
```python
df.loc[5:30,'Delivery_person_Age']
```

```python
df.loc[40:42, ['Restaurant_latitude','Restaurant_longitude', 'Delivery_location_latitude', 'Delivery_location_longitude' ] ]
```


