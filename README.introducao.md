
Risco de doenças devido a hábitos diários

  Hábitos diários podem contrinuir para o surgimento de doenças, a base escolhida contém 100000 amostras de individuos com informações associadas há 48 indicadores de estilo de vida, demográficos e biométricos.
   
Com base nas análises realizadas, é possível identificar alguns dos principais fatores associados à classificação de um indivíduo como Doete ou Saudável. Os destaques incluem: horas trabalhadas, consumo de água, circunferência da cintura, pressão arterial, nível de insulina e consumo calórico. A seguir, detalhamos os principais pontos observados:

Horas de Trabalho:
Indivíduos classificados como Doentes tendem a apresentar jornadas de trabalho mais longas, enquanto os Saudáveis se concentram em rotinas mais curtas ou até mesmo ausência de trabalho. Essa diferença pode estar relacionada ao estresse ocupacional, excesso de carga horária ou menor tempo para cuidados pessoais. Por outro lado, também pode refletir que pessoas em boas condições de saúde conseguem manter rotinas mais equilibradas ou até mesmo se afastar do trabalho como forma preventiva.

Consumo de Água:
De maneira curiosa, o consumo de água é significativamente maior entre os indivíduos Doentes. Essa associação inesperada pode indicar que a maior ingestão de água não está necessariamente ligada a um hábito saudável, mas sim a uma resposta do organismo a condições clínicas (como febre, infecções, diabetes ou uso de medicamentos que exigem maior hidratação). Isso ressalta a importância de analisar os hábitos em conjunto com o contexto clínico.

Circunferência da Cintura e Pressão Arterial:
Valores elevados nesses dois indicadores estão mais frequentemente associados a indivíduos Doentes. Ambos são marcadores amplamente reconhecidos de risco cardiovascular e metabólico, refletindo hábitos alimentares, sedentarismo ou predisposição genética.

Nível de Insulina e Consumo de Calorias:
Padrões anormais nos níveis de insulina e um consumo calórico desbalanceado também se destacam como fatores importantes na distinção entre os grupos. Tais variáveis estão diretamente ligadas ao metabolismo e ao controle glicêmico, impactando o risco de doenças como diabetes tipo 2 e obesidade.

Considerações Finais:
Classificar um indivíduo como Saudável ou Doente com base apenas em seus hábitos e medidas biométricas é um desafio complexo. Não existem fatores isolados e determinantes; em vez disso, são combinações de hábitos e condições que, em conjunto, podem levar a diferentes estados de saúde. A análise integrada e personalizada continua sendo essencial para a tomada de decisões clínicas e preventivas mais eficazes.
Etapas do Projeto de Análise e Modelagem


O projeto foi desenvolvido em 8 etapas principais, descritas a seguir:

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
