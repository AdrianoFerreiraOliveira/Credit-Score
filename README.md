> Credit-Score💰💳
<h4>Foi desenvolvido um modelo de Machine Learning com o objetivo de avaliar padrões de credito para usuários de uma empresa financeira.<h4/>

## <h4>Para esse desafio foi utilizado a metodologia de CRISP, como suporte para todo o estudo de caso, dessa forma foi possivel dividir toda a análise em fragmentos para investigação<h4/>

 Get Started- Bibliotecas necessárias
```
import pandas as pd

import seaborn as sns
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn import metrics
from sklearn.ensemble import RandomForestClassifier
```

>Lendo um arquivo CSV:
```
df = pd.read_csv('demo01.csv')
print ("Número de linhas e colunas da tabela: {}".format(df.shape))

df.head()
```

Dessa forma foi lido e carregado para o nosso modelo a base de dados em CSV, assim realizamos todo o tratamento de dados e utilizando a metodologia de Chrisp, fomos detalhando e minerando os dados.

> Conclusões

Nosso modelo obteve a acurácia de <strong>97,67%<strong/> sendo assim foi possivel identificar que diversos fatores podem contribuir para a aquisição de credito dos nossos cliente, na base de dados em especifico
vimos que grandes fatores para uma alta taxa de inadimplência são dados como tempo de emprego e idade, pessoas mais jovens tem maior tendência a serem inadimplentes bem como pessoas 
que possuem mais movimentação em emprego e não agregam um maior tempo de empresa aumentam os riscos de inadimplencia.

>Tecnologia utilizada
<img align="center" alt="Adriano-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">  

Inicialmente foi utilizado o Anaconda entretanto após checar a facilidade foi utilizado o Visual Studio code + extensão para o Jupyter notebook.
![image](https://user-images.githubusercontent.com/105682437/194677106-1e5cdccd-1ccd-4a88-99e8-445aff8f91ce.png)

