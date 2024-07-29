# Análise de Dados dos Proprietários de Carros Nissan

## Sobre o Projeto
Este projeto analisa um conjunto de dados detalhado sobre proprietários de carros Nissan, com foco em características demográficas e atributos dos veículos. O objetivo é fornecer insights valiosos para possíveis investimentos em marketing.

## Conjunto de Dados
O conjunto de dados contém informações sobre os proprietários e seus veículos, incluindo os seguintes atributos:
- **id**: Identificador único de cada indivíduo.
- **full_name**: Nome completo do proprietário do carro.
- **age**: Idade do proprietário.
- **gender**: Gênero do proprietário (Masculino, Feminino ou Não Binário).
- **model**: Modelo específico do carro Nissan.
- **color**: Cor do carro.
- **performance**: Potência do carro em km/h.
- **km**: Quilometragem total do carro.
- **condition**: Condição do carro (Novo a Velho).
- **price**: Preço do carro em dólares.

## Análises Realizadas
1. **Carregamento e Limpeza de Dados**:
    - Verificação e remoção de valores nulos.
    - Estatísticas descritivas dos dados.

2. **Análise Demográfica**:
    - Distribuição de idades dos proprietários.
    - Distribuição por gênero.
    - Idade média por gênero.

3. **Análise de Marketing**:
    - Contagem de veículos por condição.
    - Média de preço por condição.
    - Distribuição de idade por gênero.
    - Correlação entre atributos e preço.
    - Impacto da condição no preço.

## Resultados
Os resultados das análises fornecem insights importantes para estratégias de marketing, como a segmentação demográfica e a identificação de padrões de preço e performance. 

## Visualizações
As visualizações geradas incluem histogramas, gráficos de barras, boxplots e heatmaps, que ilustram as distribuições e correlações dos atributos.

## Requisitos
- Pandas
- Matplotlib
- Seaborn

## Como Usar
1. Clone este repositório.
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o script `analysis.py` para gerar as visualizações.

---

# Nissan Car Owners Data Analysis

## About the Project
This project analyzes a detailed dataset about Nissan car owners, focusing on demographic characteristics and vehicle attributes. The goal is to provide valuable insights for potential marketing investments.

## Dataset
The dataset contains information about car owners and their vehicles, including the following attributes:
- **id**: Unique identifier for each individual.
- **full_name**: Full name of the car owner.
- **age**: Age of the car owner.
- **gender**: Gender of the car owner (Male, Female, or Non-Binary).
- **model**: Specific Nissan car model.
- **color**: Color of the car.
- **performance**: Car horsepower in km/h.
- **km**: Total kilometers the car has been driven.
- **condition**: Condition of the car (New to Old).
- **price**: Car price in dollars.

## Analyses Conducted
1. **Data Loading and Cleaning**:
    - Checking and removing null values.
    - Descriptive statistics of the data.

2. **Demographic Analysis**:
    - Age distribution of car owners.
    - Gender distribution.
    - Average age by gender.

3. **Marketing Analysis**:
    - Vehicle count by condition.
    - Average price by condition.
    - Age distribution by gender.
    - Correlation between attributes and price.
    - Impact of condition on price.

## Results
The analysis results provide key insights for marketing strategies, such as demographic segmentation and identifying price and performance patterns.

## Visualizations
Generated visualizations include histograms, bar plots, box plots, and heatmaps, illustrating the distributions and correlations of attributes.

## Requirements
- Pandas
- Matplotlib
- Seaborn

## How to Use
1. Clone this repository.
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the script `analysis.py` to generate the visualizations.
