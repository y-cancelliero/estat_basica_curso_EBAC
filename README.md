# estat_basica_curso_EBAC
Projeto desenvolvido durante o curso Profissão: Cientista de Dados. O objetivo do projeto foi a análise estatística descritiva de uma base de dados de um supermercado.

## Etapas do projeto
- Etapa 1: Obtenção da média e mediana dos preços dos produtos por categoria por meio do método .groupby() e identificação das variáveis com médias e medianas diferentes;
- Etapa 2: Obtenção do desvio padrão dos preços por categoria também com .groupby();
- Etapa 3: Criação de tabela para discriminar os desvios, médias, medianas e diferenças entre médias e medianas dos produtos. A partir dela, foi possível extrair um insight: maiores desvios representavam maiores diferenças e, consequentemente, distribuições mais afastadas da normal;
- Etapa 4: Plotagem de boxplot para visualização da distribuição da categoria de maior desvio padrão com a biblioteca plotly express. A análise possibilitou a identificação de outliers no conjunto explorado.
- Etapa 5: Plotagem de gráfico de barras para visualização dos descontos por categoria com plotly express. A análise mostrou que as categorias que receberam mais desconto foram congelados e beleza e cuidado pessoal;
- Etapa 6: Plotagem de gráfico interativo com a biblioteca Dash que agrupou os dados por marca e categoria, mostrando o desconto médio, de forma a facilitar a visualização dos dados. 
