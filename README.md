### Projeto de Análise de Dados de Turbinas Eólicas

Este projeto tem como objetivo analisar dados de desempenho de turbinas eólicas usando um conjunto de dados do Kaggle. Vamos realizar algumas etapas importantes de análise e visualização dos dados usando Python e bibliotecas populares como pandas, matplotlib e seaborn.

### Passos do Projeto

#### 0) Importando Bibliotecas
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

#### 1) Lendo o Arquivo
Os dados estão sendo lidos de um arquivo CSV obtido no Kaggle que contém informações como data/hora, potência ativa, velocidade do vento e valores teóricos de potência. Algumas colunas são renomeadas para melhor entendimento.

#### 2) Visualizando os Dados Reais
Vamos criar um gráfico de dispersão para visualizar a relação entre a velocidade do vento e a potência ativa das turbinas.

#### 3) Visualizando os Dados Teóricos
Outro gráfico de dispersão será criado para comparar a velocidade do vento com os valores teóricos de potência.

#### 4) Definindo Limites Aceitáveis
Criaremos limites aceitáveis de potência com base nos valores teóricos, adicionando-os ao conjunto de dados.

#### 5) Análise dos Limites
Uma análise é realizada para determinar quantas leituras de potência estão dentro dos limites aceitáveis.

#### 6) Visualizando os Dados com Limites
O gráfico de dispersão será plotado novamente, desta vez colorindo os pontos com base nos limites operacionais (dentro ou fora dos limites aceitáveis).

### Arquivos

- `raw_turbina_scala.csv`: Arquivo de dados original obtido do Kaggle.
- `README.md`: Este arquivo, fornecendo uma visão geral do projeto e das etapas realizadas.

### Executando o Código

Para executar este projeto, é necessário ter Python instalado juntamente com as bibliotecas `pandas`, `matplotlib` e `seaborn`. Certifique-se de ter o arquivo CSV `raw_turbina_scala.csv` no diretório `../data/raw/` para que o código possa ler os dados corretamente.

```bash
pip install pandas matplotlib seaborn
```

### Conclusão

Este projeto oferece uma visão inicial da análise de dados de turbinas eólicas, explorando a relação entre a velocidade do vento e a potência gerada. Além disso, introduzimos a ideia de limites operacionais e como eles podem ser visualizados para monitorar o desempenho das turbinas.
