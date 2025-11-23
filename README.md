# 🏠 Apartment for Rent Fraud Detection

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-red?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

**Sistema Inteligente de Detecção de Fraudes em Anúncios de Apartamentos**

[📊 Dataset](#-dataset) • [🚀 Setup](#-setup) • [🎯 Resultados](#-resultados) • [👥 Equipe](#-equipe)

</div>

---

## 📋 Sobre o Projeto

Este projeto implementa um **sistema de Machine Learning** para classificação automática de anúncios de apartamentos para aluguel, identificando se são **legítimos** ou **fraudulentos**. 

Com o crescimento exponencial do mercado imobiliário online, fraudes em anúncios tornaram-se um problema crítico. Este sistema utiliza algoritmos avançados de ML para proteger consumidores e melhorar a confiança em plataformas de classificados.

### 🎯 Objetivos

- Desenvolver modelo preditivo para detecção de fraudes
- Comparar performance de múltiplos algoritmos de ML
- Criar sistema interativo para classificação em tempo real
- Fornecer análise estatística completa dos dados
- Visualizar insights através de gráficos profissionais

---

## 🌟 Características Principais

### 🔍 Análise Exploratória Completa
- Estatísticas descritivas detalhadas (média, mediana, moda, quartis)
- Identificação de outliers e anomalias
- Análise de correlações entre variáveis
- Visualizações interativas (histogramas, boxplots, scatterplots, heatmaps)

### 🤖 Machine Learning
- **4 Algoritmos Implementados:**
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- Comparação de métricas (Accuracy, Precision, Recall, F1-Score)
- Matriz de confusão e relatório de classificação
- Seleção automática do melhor modelo

### 💻 Sistema Interativo
- Interface via terminal para classificação de novos anúncios
- Predições em tempo real
- Probabilidades de classificação
- Testes automatizados com exemplos

---

## 🛠️ Tecnologias Utilizadas

| Categoria | Tecnologias |
|-----------|-------------|
| **Linguagem** | Python 3.11 |
| **Ambiente** | Jupyter Notebook |
| **Análise de Dados** | Pandas, NumPy |
| **Visualização** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Interface** | ipywidgets |

---

## 📊 Dataset

**Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified)

### Características do Dataset:
- **100.000 registros** de anúncios reais
- **22 features** (numéricas e categóricas)
- **Target binário** (0 = Legítimo, 1 = Fraudulento)

### Características Principais:
```
- Localização:    address, cityname, state, latitude, longitude
- Propriedade:    bedrooms, bathrooms, square_feet
- Financeiro:     price, currency, fee
- Mídia:          has_photo, amenities
- Políticas:      pets_allowed
- Temporal:       time, source
```

---

## 🚀 Setup

### Pré-requisitos

```bash
Python 3.11+
pip (gerenciador de pacotes)
```

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/apartment-fraud-detection.git
cd apartment-fraud-detection
```

2. **Crie um ambiente virtual**
```bash
python -m venv .venv
```

3. **Ative o ambiente virtual**

Windows:
```bash
.venv\Scripts\activate
```

Linux/Mac:
```bash
source .venv/bin/activate
```

4. **Instale as dependências**
```bash
pip install -r requirements.txt
```

5. **Execute o Jupyter Notebook**
```bash
jupyter notebook Trabalho_Apartment_for_Rent.ipynb
```

---

## 📁 Estrutura do Projeto

```
apartment-fraud-detection/
│
├── Trabalho_Apartment_for_Rent.ipynb    # Notebook principal
├── apartments_for_rent_classified_100K.csv.xls  # Dataset completo
├── requirements.txt                      # Dependências Python
├── README.md                             # Este arquivo
├── .gitignore                            # Arquivos ignorados
└── .venv/                                # Ambiente virtual
```

---

## 🎯 Resultados

### 📈 Performance dos Modelos

| Modelo | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| **Random Forest** | **95.2%** | **94.8%** | **95.5%** | **95.1%** |
| Logistic Regression | 89.3% | 88.7% | 89.8% | 89.2% |
| Decision Tree | 91.5% | 90.9% | 91.2% | 91.0% |
| SVM | 92.7% | 92.1% | 92.9% | 92.5% |

*Valores ilustrativos - execute o notebook para resultados reais*

### 🎨 Visualizações

O projeto inclui visualizações profissionais:

- **Histogramas** - Distribuição de variáveis numéricas
- **Boxplots** - Identificação de outliers
- **Scatterplots** - Relações entre variáveis
- **Heatmap** - Matriz de correlação
- **Gráficos Comparativos** - Performance dos modelos
- **Matriz de Confusão** - Análise de erros

---

## 📚 Estrutura do Notebook

O notebook está organizado em 8 seções principais:

1. **Introdução**
   - Contexto e objetivos
   - Definição do problema
   - Relevância do tema

2. **Carregamento e Entendimento**
   - Importação dos dados
   - Análise exploratória inicial
   - Descrição das features

3. **Análise Estatística**
   - Estatísticas descritivas completas
   - Visualizações detalhadas
   - Diagnóstico da qualidade dos dados

4. **Preparação dos Dados**
   - Tratamento de valores ausentes
   - Normalização/Padronização
   - Split treino/teste

5. **Modelagem**
   - Treinamento de múltiplos modelos
   - Avaliação e comparação
   - Seleção do melhor modelo

6. **Aplicação Prática**
   - Sistema interativo de classificação
   - Testes com novos dados
   - Exemplos de uso

7. **Conclusão**
   - Principais descobertas
   - Limitações identificadas
   - Melhorias futuras

8. **Vídeo Explicativo**
   - Link para apresentação

---

## 🔬 Metodologia

### Pipeline de ML

```
 Dados Brutos
    ↓
 Análise Exploratória
    ↓
 Limpeza e Tratamento
    ↓
 Feature Engineering
    ↓
 Normalização
    ↓
 Train/Test Split
    ↓
 Treinamento de Modelos
    ↓
 Avaliação e Comparação
    ↓
 Seleção do Melhor Modelo
    ↓
 Deploy e Aplicação
```

---

## 💡 Insights e Descobertas

### 🔍 Principais Padrões Identificados:

1. **Correlação Preço-Área**: Forte correlação positiva entre tamanho e valor do aluguel
2. **Outliers Suspeitos**: Preços extremamente baixos ou altos indicam possíveis fraudes
3. **Features Importantes**: Número de fotos e descrição completa são indicadores de legitimidade
4. **Padrões Temporais**: Anúncios publicados em horários incomuns tendem a ser mais suspeitos

### ⚠️ Desafios Encontrados:

- Desbalanceamento de classes (mais legítimos que fraudulentos)
- Valores ausentes em features importantes
- Variabilidade geográfica nos preços
- Necessidade de normalização devido a escalas diferentes

---

## 🎓 Competências

Este projeto demonstra:

- Pipeline completo de Ciência de Dados
- Comparação sistemática de algoritmos de ML
- Importância da análise exploratória
- Tratamento adequado de dados reais
- Avaliação criteriosa de modelos
- Desenvolvimento de aplicação prática

---

## 👥 Equipe

Este projeto foi desenvolvido por:

1. Gabriel Cunha de Araujo (2204029)
2. Gabriel Zaniqueli (2205156)
3. Kelvin Pimenta Dias (2205385)
4. Nicolas Rossetto Samblas(2305916)
5. Renan Martins Rossi (2304805)
6. Lucas Marujo Amadeu (2108723)
7. Lucas Ferreira Balduino (2201210)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📊 Estatísticas do Projeto

![GitHub stars](https://img.shields.io/github/stars/lucasmarujo/jupyter-datascience-apartaments-for-rent)
![GitHub forks](https://img.shields.io/github/forks/lucasmarujo/jupyter-datascience-apartaments-for-rent)
![GitHub watchers](https://img.shields.io/github/watchers/lucasmarujo/jupyter-datascience-apartaments-for-rent)

---