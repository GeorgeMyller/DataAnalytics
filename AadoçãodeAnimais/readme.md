## Análise de Dados de Adoção de Animais: Quais Fatores Influenciam as Taxas de Adoção? 🐶🐱🐰

Este Jupyter Notebook apresenta uma análise exploratória de dados (EDA) sobre um conjunto de dados de adoção de animais, com o objetivo de identificar os fatores que influenciam as taxas de adoção.

**Fonte dos Dados:** [Predict Pet Adoption Status Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-pet-adoption-status-dataset?resource=download) no Kaggle.

**Objetivo:**

O principal objetivo desta análise é responder à seguinte pergunta: 

* **Quais características dos animais de estimação e do processo de adoção estão mais fortemente correlacionadas com a probabilidade de adoção?**

**Etapas da Análise:**

1. **Preparação do Ambiente e Carga de Dados:**
    * Instalação das bibliotecas necessárias (pandas, matplotlib, seaborn, scipy).
    * Carga do conjunto de dados do arquivo CSV.

2. **Limpeza e Transformação de Dados:**
    * Verificação de valores ausentes.
    * Conversão de variáveis categóricas para o tipo apropriado.
    * Criação de novas variáveis, como "Faixas Etárias", para uma análise mais aprofundada.

3. **Análise Exploratória de Dados (EDA):**
    * **Análise Descritiva:** Sumário estatístico das variáveis numéricas.
    * **Visualização de Dados:**
        * Gráficos de barras para a frequência de categorias (tipo de animal, raça, etc.).
        * Histogramas para a distribuição de variáveis numéricas (idade, tempo no abrigo).
        * Gráficos de dispersão e mapas de calor para explorar correlações entre variáveis.

4. **Análise Estatística:**
    * **Teste Qui-Quadrado:** Avaliar a significância da relação entre variáveis categóricas (tipo de animal, raça, saúde e probabilidade de adoção).
    * **Coeficiente de Correlação:** Quantificar a força e direção da relação linear entre variáveis numéricas (idade e probabilidade de adoção).

5. **Conclusões e Insights:**
    * **Fatores de Influência:** Identificação das variáveis que demonstram maior impacto na probabilidade de adoção, como idade, saúde e tipo de animal.
    * **Padrões Observados:** Descrição das principais tendências e padrões encontrados nos dados, como a preferência por animais mais jovens e saudáveis.

**Principais Insights:**

A análise revelou que os seguintes fatores estão significativamente relacionados à probabilidade de adoção:

* **Idade:** Animais mais jovens são mais propensos a serem adotados.
* **Condição de Saúde:** Animais saudáveis ​​têm maior probabilidade de encontrar um lar.
* **Tipo de Animal:** Cães tendem a ser adotados com mais frequência do que outros animais de estimação.
* **Raça:** Algumas raças específicas demonstram maior popularidade entre os adotantes.

**Limitações:**

* O conjunto de dados pode não ser representativo de todas as situações de adoção de animais de estimação.
* A análise se concentrou principalmente em correlações, e mais pesquisas são necessárias para determinar relações de causa e efeito.

**Próximos Passos:**

* Construir modelos preditivos para estimar a probabilidade de adoção de animais individuais.
* Investigar a fundo as razões por trás das correlações observadas, utilizando técnicas de análise qualitativa.
* Desenvolver um aplicativo web interativo para visualizar os dados e os insights da análise.

**Como Executar o Notebook:**

1. Certifique-se de ter o Jupyter Notebook instalado.
2. Instale as bibliotecas necessárias: `pip install pandas matplotlib seaborn scipy`.
3. Baixe o conjunto de dados do Kaggle (link no topo).
4. Abra o Jupyter Notebook e execute todas as células.

**Observação:** O código e os resultados da análise estão disponíveis no arquivo do Jupyter Notebook.

---

Espero que este README.md seja útil para apresentar sua análise de forma clara e concisa! 😊 


## Pet Adoption Data Analysis: What Factors Influence Adoption Rates? 🐶🐱🐰

This Jupyter Notebook presents an exploratory data analysis (EDA) of a pet adoption dataset to identify factors that influence adoption rates.

**Data Source:** [Predict Pet Adoption Status Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-pet-adoption-status-dataset?resource=download) on Kaggle.

**Objective:**

The primary objective of this analysis is to answer the following question:

* **Which characteristics of pets and the adoption process are most strongly correlated with the likelihood of adoption?**

**Analysis Steps:**

1. **Environment Setup and Data Loading:**
    * Installation of necessary libraries (pandas, matplotlib, seaborn, scipy).
    * Loading the dataset from the CSV file.

2. **Data Cleaning and Transformation:**
    * Checking for missing values.
    * Converting categorical variables to appropriate data types.
    * Creating new variables, such as "Age Groups," for deeper analysis.

3. **Exploratory Data Analysis (EDA):**
    * **Descriptive Analysis:** Statistical summary of numerical variables.
    * **Data Visualization:**
        * Bar charts for the frequency of categories (pet type, breed, etc.).
        * Histograms for the distribution of numerical variables (age, time in shelter).
        * Scatter plots and heatmaps to explore correlations between variables.

4. **Statistical Analysis:**
    * **Chi-Squared Test:** Assess the significance of the relationship between categorical variables (pet type, breed, health, and adoption likelihood).
    * **Correlation Coefficient:** Quantify the strength and direction of the linear relationship between numerical variables (age and adoption likelihood).

5. **Conclusions and Insights:**
    * **Influencing Factors:** Identification of variables that show the greatest impact on adoption likelihood, such as age, health, and type of animal.
    * **Observed Patterns:** Description of the main trends and patterns found in the data, such as the preference for younger and healthier animals.

**Key Insights:**

The analysis revealed that the following factors are significantly related to the likelihood of adoption:

* **Age:** Younger animals are more likely to be adopted.
* **Health Condition:** Healthy animals have a higher chance of finding a home.
* **Type of Animal:** Dogs tend to be adopted more frequently than other pets.
* **Breed:** Certain specific breeds show greater popularity among adopters.

**Limitations:**

* The dataset may not be representative of all pet adoption situations.
* The analysis focused primarily on correlations, and further research is needed to determine cause-and-effect relationships.

**Next Steps:**

* Build predictive models to estimate the adoption likelihood of individual animals.
* Investigate the reasons behind the observed correlations in depth, using qualitative analysis techniques.
* Develop an interactive web application to visualize the data and the insights from the analysis.

**How to Run the Notebook:**

1. Ensure you have Jupyter Notebook installed.
2. Install the necessary libraries: `pip install pandas matplotlib seaborn scipy`.
3. Download the dataset from Kaggle (link at the top).
4. Open the Jupyter Notebook and run all cells.

**Note:** The code and analysis results are available in the Jupyter Notebook file.

---

I hope this README.md helps present your analysis clearly and concisely! 😊 
