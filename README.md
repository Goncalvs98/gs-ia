# Inteligência Artificial e Computacional

## Global Solution – 1º Semestre

**Daniel Okudaira Carapeto** – 93180  
**Gabriel Gonçalves** – 93069  
**Rodrigo Lima de Carvalho** – 96247  

### Identificação de Padrões de Poluição Plástica por Região

#### Introdução

A poluição plástica é uma preocupação ambiental significativa, afetando oceanos, rios e terras. Este relatório detalha uma abordagem para identificar padrões de poluição plástica em diferentes regiões geográficas usando técnicas de clustering, uma forma de aprendizado não supervisionado que agrupa dados com base em suas semelhanças.

#### Metodologia

1. **Análise Exploratória de Dados (EDA)**
   - **Objetivo**: Entender a estrutura e características dos dados.
   - **Dados Utilizados**:
     - Localização geográfica (latitude e longitude)
     - Quantidade de resíduos plásticos
     - Tipos de plásticos (micro, macro, etc.)
     - Fontes de poluição (doméstica, industrial, marítima, etc.)
     - Dados temporais (datas de coleta)
   - **Técnicas**:
     - Estatísticas descritivas
     - Visualizações gráficas (histogramas, boxplots, mapas de calor)
     - Análise de correlação entre variáveis
   - **Exemplos de Visualizações**:
     - Mapas de calor
     - Histogramas por tipo e fonte de resíduos
     - Gráficos de dispersão geográfica

2. **Pré-processamento dos Dados**
   - **Objetivo**: Preparar os dados para o clustering.
   - **Passos Detalhados**:
     - Tratamento de valores ausentes
     - Normalização/padronização das variáveis
     - Codificação de variáveis categóricas
     - Remoção de outliers

3. **Aplicação de Técnicas de Clustering**
   - **Algoritmos Comuns**: K-means, DBSCAN, Hierarchical Clustering
   - **Escolha do Método**: K-means pela sua simplicidade e eficácia
   - **Determinação do Número de Clusters**:
     - Método do Cotovelo (Elbow Method)
     - Método da Silhueta (Silhouette Method)
   - **Execução do Clustering**:
     - Inicialização
     - Iteração
     - Convergência

4. **Análise e Visualização dos Clusters**
   - **Objetivo**: Entender os padrões de poluição dos clusters.
   - **Visualizações**:
     - Mapas geográficos dos clusters
     - Gráficos de barras das características dos clusters
   - **Ferramentas**:
     - Matplotlib, Seaborn, Plotly
     - Ferramentas GIS

5. **Interpretação dos Resultados**
   - **Objetivo**: Analisar as características de cada cluster.
   - **Perguntas Chave**:
     - Quais regiões têm maiores níveis de poluição plástica?
     - Padrões específicos de fontes de poluição?
     - Influência das características geográficas?
   - **Uso Prático**:
     - Direcionar esforços de limpeza
     - Desenvolver políticas ambientais
     - Promover campanhas de conscientização

#### Conclusão

Este relatório apresenta uma abordagem detalhada para identificar padrões de poluição plástica usando técnicas de clustering. Com análise exploratória de dados, pré-processamento, aplicação de clustering e interpretação dos resultados, é possível compreender a distribuição da poluição plástica e implementar ações eficazes para mitigação.

#### Bibliografia

- [Clustering — Conceitos básicos, principais algoritmos e aplicações](https://medium.com/turing-talks/clustering-conceitos-b%C3%A1sicos-principais-algoritmos-e-aplica%C3%A7%C3%A3o-ace572a062a9)
- [O que é clustering?](https://developers.google.com/machine-learning/clustering/overview?hl=pt-br)
- [Silhouette Visualizer](https://www.scikit-yb.org/en/latest/api/cluster/silhouette.html)
- [Stop Using Elbow Method in K-Means Clustering](https://builtin.com/data-science/elbow-method#:~:text=The%20elbow%20method%20is%20a%20graphical%20method%20for%20finding%20the,the%20graph%20forms%20an%20elbow)
- [Elbow Method for Finding the Optimal Number of Clusters in K-Means](https://www.analyticsvidhya.com/blog/2021/01/in-depth-intuition-of-k-means-clustering-algorithm-in-machine-learning/)
- [Vídeo do Projeto](https://youtu.be/DoU4viLpWFE)

