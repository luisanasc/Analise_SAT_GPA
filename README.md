## Análise das Notas do SAT e GPA

- Introdução

Este projeto tem como objetivo analisar a relação entre as notas do SAT e as notas do GPA de estudantes universitários. A análise busca identificar se existe uma correlação significativa entre essas duas variáveis e se as notas do SAT podem ser um preditor confiável do desempenho acadêmico representado pelo GPA.

- Definição das Variáveis

SAT (Scholastic Assessment Test): Um exame padronizado utilizado nos EUA para admissão em universidades, com pontuação variando de 400 a 1600 pontos. A tabela utilizada aqui, utiliza dados fantasia que variam de 1600 à 2050 pontos, seriam apenas de testes de alunos que passaram para o ensino superior.

GPA (Grade Point Average): Média das notas acadêmicas dos alunos, variando geralmente de 0.0 a 4.0.

- Metodologia

Leitura e Limpeza dos Dados: Os dados foram importados de um arquivo CSV, tratados para remoção de inconsistências e conversão de valores numéricos.

- Análise Exploratória:

Cálculo de estatísticas descritivas como média, moda e desvio padrão.

Construção de histogramas e curvas de distribuição normal.

Análise de normalidade através de QQ plots e testes estatísticos (Shapiro-Wilk).

- Visualização dos Dados:

Histogramas comparativos das distribuições de SAT e GPA.

Gráficos de dispersão destacando percentis importantes (80%, 90% e 95%).

Linhas de tendência e distribuições estatísticas.

- Análise de Correlação:

Cálculo do coeficiente de correlação de Pearson entre SAT e GPA.

- Regressão Linear:

Ajuste de um modelo de regressão linear entre SAT e GPA.

Avaliação do coeficiente de determinação (R²) e erro quadrático médio (MSE).

## Resultados Principais

O histograma e o QQ plot indicam que a distribuição dos dados não é perfeitamente normal.

A análise de regressão linear revelou um coeficiente de correlação que sugere uma relação moderada entre SAT e GPA.

O coeficiente R² da regressão linear indica o grau de previsibilidade das notas de GPA com base no SAT.

## Conclusão

Os resultados demonstram que há uma relação entre as notas do SAT e o desempenho acadêmico representado pelo GPA, mas essa relação pode ser influenciada por outros fatores como qualidade do ensino, esforço acadêmico e outros critérios de admissão das universidades. Mais análises seriam necessárias para refinar os modelos e entender melhor as variáveis envolvidas. Seria interessante também uma pesquisa cultural sobre os hábitos de vida dessas estudantes antes e pós vida universitária como: rotina, alimentação, hábitos de estudo, saúde e lazer para trazer dados qualitativos e contextuais para a análise.
