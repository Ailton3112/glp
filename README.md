# glp

## Status atual :  
    Atualmente está sendo feito a experimentação de setups distintos do modelo LSTM a fim de obter uma melhor perfomance da loss (conjuntos de treino e validação) sob o     notebook Experimento_01_Predicao.ipynb
## Dificuldades : 
    1. Devido ao "peso" das experimentações do modelo pretendido (crasheando)
        - utilizar GPU pra que as experimentações sejam mais rápidas e eficientes
        - a GPU free quebra com duas horas de execução (?)
        
## Sobre os notebooks         
### O notebook RevGas.ipynb tem como objetivo:
-Análise Exploratória de dados de Pedidos de Revenda Gás
  - Pedidos por dia da semana
  - Pedidos por mês
  - Pedidos por dia do mês
  - Pedidos por ano
  - Consumo por ano, mês e dia

### O notebook RevGas_V01.ipynb tem como objetivo:
    Neste notebook, usa o dataset Produtos_Clientes.csv para construir um modelo de aprendizado de máquina não supervisionado que permite estimar se um determinado cliente comprará algo novamente na loja online no próximo trimestre.

    1.Quantos clientes online existem no conjunto de dados e qual é a sua cidade/estado de origem?
    2.Quais são as cidades/estados mais representadas no conjunto de dados?
    3.Calcule a receita que foi feita em cada mês e qual é a receita percentual com base nas várias cidades/estados?


### O notebook RevGas_npd-prediction.ipynb tem como objetivo:
    Fazer uso da base produtos_clientes.csv para dar inicio ao processo de experimentação de modelos preditivos

### O notebook Predição_REVGAS.ipynb tem como objetivo:
    Faz exploração dos dados para obter :
      1.Receita mensal
      2.Taxa de crescimento da receita mensal
      3.Receita média por período
      4.Taxa de retensão mensal
      5.Cálcul da recência, frequência e valor monetário
      6.Faz agrupamentos por segmentos
 
 ### O notebook NFE.ipynb tem como objetivo:
    Analisar Emissão de NFe para ser input para experiência de usuário (Morita)
    
 ### O notebook Experimento_RevGasToTS.ipynb tem como objetivo:
    Gera séries temporais dos dados de consumo (base de consumo de Gás GLP na cidade de Teresina entre 2013 e 2022 em uma séries temporal univariada.)
 
 ### O notebook Experimento_03_Predicao.ipynb tem como objetivo:
    1. Remove ruídos
    2. Calcula média e desvio padrão
    3. Gera histogramas e box plot
    4. Faz filtragem por estados e gerar arquivos limpos csv 
    
 ### O notebook Experimento_02_Predicao.ipynb tem como objetivo:
    1. Iniciar estudos sobre um modelo de predição para o estado do Piauí 
    
 ### O notebook OLD_RevGas_Prediction_FAST.ipynb tem como objetivo:
    1. Iniciar estudos sobre um modelo de predição sobre a base geral produtos_clientes.csv
 
 ### O notebook Experimento_01_Predicao.ipynbtem como objetivo:
    1. Experimentar modelo LSTM para predição da próxima data de compra para o csv gerado a partir do notebook Experimento_03_Predicao.ipynb 
    2. Experimentar parâmetros para melhorar a performance do modelo proposto [em andamento]
    
    
    
