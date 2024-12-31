# DIO - Conhecendo as Bibliotecas Pandas e Scikit-Learn

As bibliotecas Pandas e Scikit-Learn são fundamentais no ecossistema de ciência de dados e aprendizado de máquina em Python. 

Cada uma tem um conjunto de funcionalidades distintas, mas complementares, que permitem desde a manipulação eficiente de dados até a implementação de modelos preditivos sofisticados.

## Biblioteca Pandas

A biblioteca Pandas é uma ferramenta poderosa para análise e manipulação de dados em Python. Ela fornece estruturas de dados rápidas, flexíveis e expressivas, permitindo que os usuários trabalhem com dados tabulares de forma similar ao que seria feito em planilhas, mas com a eficiência de uma linguagem de programação.

### **Características Principais do Pandas**:

1. **Estruturas de Dados:**

   - **Series**: Estrutura unidimensional semelhante a uma lista ou vetor.

   - **DataFrame**: Estrutura bidimensional que funciona como uma tabela, com rótulos para linhas e colunas.

2. **Carregamento de Dados:**

   - Importa dados de diferentes formatos, como CSV, Excel, SQL, JSON, entre outros.

3. **Manipulação de Dados:**

   - Filtragem, ordenação, remoção de duplicados e preenchimento de valores ausentes.

4. **Análise Estatística:**

   - Cálculos como média, desvio padrão e correlações diretamente sobre os dados.

5. **Visualização:**

   - Integração com bibliotecas como Matplotlib e Seaborn para gerar gráficos diretamente a partir dos dados.

## Biblioteca Scikit-Learn

A Scikit-Learn é uma das bibliotecas mais utilizadas para aprendizado de máquina em Python. 

Ela fornece uma ampla gama de ferramentas para construção, treinamento e avaliação de modelos preditivos.

### **Características Principais do Scikit-Learn**:

1. **Modelos Preditivos:**

   - Algoritmos de classificação, regressão, agrupamento e redução de dimensionalidade.

   - Exemplos: Regressão Linear, Árvores de Decisão, K-Means, PCA (Análise de Componentes Principais).

2. **Pré-Processamento de Dados:**

   - Normalização, padronização, codificação de variáveis categóricas e tratamento de dados ausentes.

3. **Pipeline de Machine Learning:**

   - Combinação de várias etapas do fluxo de trabalho de aprendizado de máquina em uma única estrutura.

4. **Validação de Modelos:**

   - Ferramentas para avaliação de desempenho, como métricas (precisão, recall, F1-Score) e validação cruzada.

5. **Facilidade de Integração:**

   - Trabalha bem com bibliotecas como Pandas para entrada e saída de dados e com Numpy para cálculos vetorizados.

## **Integração entre Pandas e Scikit-Learn**

A integração dessas bibliotecas é um dos aspectos mais poderosos na construção de pipelines de aprendizado de máquina. 

Com o Pandas, é possível realizar a limpeza, transformação e organização dos dados. 

Esses dados são, então, utilizados no Scikit-Learn para treinar modelos preditivos e avaliar resultados. 

Essa sinergia garante flexibilidade e eficiência em projetos de ciência de dados.

**Exemplo de Workflow:**

1. Carregar dados com Pandas.

2. Realizar limpeza e transformação dos dados.

3. Dividir os dados em conjuntos de treino e teste.

4. Treinar um modelo com Scikit-Learn.

5. Avaliar a precisão do modelo.

Essas duas bibliotecas são pilares para quem deseja explorar ciência de dados e aprendizado de máquina de forma prática e eficaz.
