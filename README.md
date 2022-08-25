# python-estatistica
## Curso de python parte 1
### Tipos de dados
      - Quantitativa
      - Qualitativas
      - Código:
### Distribuição de Frequência
      - Dist. Freq. p/ Qualitativa
      - Dist. Freq. p/ Quantitativa (classes personalizadas e classe de amplitude fixa)
      - Histograma
### Medidas de Tendência Central
      - Média
      - Mediana
      - Moda
      - Relação entre média, mediana e moda
### Medidas Separatrizes
      - Quartis, Decis e Percentis
      - Box-plot
### Medidas de Dispersão
      - Desvio Médio Absoluto
      - Variância
      - Desvio Padrão
### Códigos
       - sorted()  coloca os valores em ordem
       - .sort_values() ordena os valores do menor para o maior
       - .shape rtorna o número de linhas e coluna do dataframe
       - .reset_index() pega o index do DF transforma em uma coluna e coloca um index numérico no lugar
       - .unique() retorna valores unicos
       - .value_counts() conta os dados por categoria
       - .value_counts(normalize=True) transforma as categorias em porcentagem
       - .mean() tira a média
       - .median() tira a mediana
       - .moda() tira a moda
       - .sample(numero do tamanho da amostra, random_state = numero) sample faz uma amostra aleatória do df ou series
       - nessa sessão mostra como renomear os index, colunas e colocar um nome na coluna do index
       - transformar uma tabela em percentual
       - usar uma variável para fazer uma estatística descritiva com 2 outra variáveis, ex: a renda média salárial entre homens e mulheres de diferentes tonalidades de pele
       - .quantile() retorna a mediana, mas vc pode passar uma lista com as partições [0.25, 0.5, 0.75]
       - .mad() retorna o desvio médio absoluto
       - .var() retorna a variância
       - .std() retorna o desvio padrão       
       
## Curso de python parte 2
### Distribuição de Probabilidade
      - Distribuição Binomial
      - Distribuição Poisson
      - Distribuição Normal
### Amostragem
      - População e Amostra
      - Quando utilizar uma amostra
      - Amostragem aleatória simples
      - Amostragem Estratificada
      - Amostragem por Conglomerados
### Estimação
      - Teorema do limite central
      - Níveis de confiança e significância
      - Erro inferencial
      - Intervalos de confiança
### Cálculo do Tamanho da Amostra
      - Variáveis quantitativas e população infinita
      - Vriáveis quantitativas e população finita
### Códigos
      - from scipy.special import comb, comb() serve ara fazer combinações fatoriais 
      - from scipy.stats import binom, binom.pmf(k, n, p)
      - binom.sf(numero faltante, n, p) leia o notebook para entender
      - from scipy.stats import poisson, poisson.pmf(k, u)
      - Z = (x - media) / desvio_padrao, from scipy.stats import norm, norm.cdf(Z)
      - norm.interval(alpha = 0.95, loc = media_amostra, scale = sigma), calculando o intervalo de confiança para a média
      - norm.ppf(probabilidade) retorna a variável padronizada 
## Curso de python parte 3
### Testes de Hipóteses
      - Teste de normalidade
      - Etapas Básicas de um Teste
### Testes Paramétricos 
      - Teste Bicaudal
      - Teste Unicaudal
      - Testes para Duas Amostras
### Testes não paramétricos
      - Teste do Qui-Quadrado
      - Teste Wilcoxon
      - Teste de Mann-Whitney
      
## Curso de python parte 4
### Rodando uma Regressão Linear
### Correlação
      - Covariância
      - Interpretação da Covariância
      - Coeficiente de Correlação de Pearson
### Regressão Linear
      - Regressão Linear Simples
      - O método de mínimos quadrados 
      - Estimadores de mínimos quadrados ordinários
      - Obtendo Previsões
      - Resíduos
      - Suposições sobre o termo de erro (u)
      - O coeficiente de determinação R²
      - Testes aplicados a modelos de Regressão
### Extras
      - Outros Testes

## Regressão Linear
### Análises Preliminares
      - Estatística Descritivas
      - Matriz de Correlação
### Comportamento da Variável Dependente (Y)
      - Análises Gráficas
            - Box-Plot de duas variáveis
            - Distribuição de Frequências
      - Configuração de cor da biblioteca seaborn
### Variável Dependente VS Variáveis Explicativas 
      - Análises Gráficas com:
            - pairplot
            - jointplot
            - lmplot
### Estimulando o Modelo de Regressão Linear para o consumo
      - train_test_split, biblioteca para treinar o modelo
      - importando LinearRegression e Metrics
      - Obtendo o coeficiente de determinação (R²)
      - Gerando previsões e obtendo o (R²) das previsões
### Obtendo Previsões Pontuais
### Interpretação dos Coeficientes Estimados
### Análise Gráfica das Previsões do Modelo - Aprendendo análise gráfica para entender se o modelo está ajustado ou não
### Comparando Modelos
### Outras métricas de Regressão 
### Salvando e carregando modelos
   
## Regressão Linear II
### Matriz de correlação
      - Comportamento da Variável Dependente (Y)
      - Distribuição de Freguências
      - Dispersão Entre as Variáveis
### Transformando os Dados
      - Verificando Relação Linear
### Criando os Dataset de Treino e Teste
      - Avaliando o Modelo Estimado
      - Modificando o Modelo e Avanliando Novamente o Ajuste
### Estimando o Modelo com os Dados de Treino
      - Obtendo Previsões Pontuais
      - Interpretação dos Coeficientes Estimados
      - Análises Gráficos dos Resultados do Modelo  
