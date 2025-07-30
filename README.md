
Risco de doenças devido a hábitos diários
  Hábitos diários podem contrinuir para o surgimento de doenças, a base escolhida contém 100000 amostras de individuos com informações associadas há 48 indicadores de estilo de vida, demográficos e biométricos.
  O trabalho foi dividido em 8 grandes etapas, listadas abaixo.


Etapas do Projeto de Análise e Modelagem

1. Entendimento do Problema
Definição do objetivo: classificar indivíduos como "Saudável" ou "Doente".
Compreensão das variáveis disponíveis (biométricas, comportamentais, ambientais).

2. Importação e Leitura dos Dados

3. Análise Exploratória (EDA)
  Verificação de tipos de dados, nulos e valores inconsistentes.
  Estatísticas descritivas.
  Visualizações:
  Histogramas
  Boxplots
  Gráficos de dispersão

4. Pré-processamento dos Dados
  Tratamento de valores ausentes.
  Normalização ou padronização.
  Criação de variáveis derivadas (ex: IMC corrigido).
  Codificação de variáveis categóricas.

5. Divisão em Treino e Teste
   Divisão da base em teste e treino, definindo 70% teste e 30% treino

6. Modelagem Preditiva
Modelos utilizados:
  Árvore de Decisão
  Random Forest
Avaliação por:
  Acurácia
  Recall
  F1-Score
  Matriz de Confusão

7. Interpretação dos Resultados
Fatores mais relevantes para classificação: horas de trabalho, consumo de água, cintura, pressão arterial, insulina e calorias.
Indivíduos com mais horas de trabalho tendem a ser classificados como "Doente".
