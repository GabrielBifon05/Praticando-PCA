# 📊 Análise de Componentes Principais (PCA) — Expectativa de Vida no Afeganistão

## 📌 Descrição do Projeto
Este projeto aplica **Análise de Componentes Principais (PCA)** em um dataset de indicadores relacionados à expectativa de vida no Afeganistão até 2014. O objetivo é reduzir a dimensionalidade dos dados e identificar padrões relevantes entre as variáveis.

---

## ⚙️ Etapas Realizadas

### 1. Carregamento e exploração dos dados
- Leitura do dataset (`Afegan_Raw.csv`)
- Verificação das dimensões e visualização inicial

### 2. Pré-processamento (Padronização)
- Cálculo da média e desvio padrão de cada variável
- Aplicação de **auto-escalonamento (z-score)** para normalizar os dados

### 3. Análise de Correlação
- Cálculo da matriz de correlação
- Visualização com **heatmap** para identificar relações entre variáveis

### 4. Aplicação do PCA
- Conversão dos dados para array NumPy
- Cálculo da matriz de covariância
- Aplicação do PCA com múltiplos componentes

### 5. Avaliação dos Componentes
- Análise da variância explicada por cada componente
- Cálculo da variância acumulada
- Construção do **Scree Plot** para definir o número ideal de componentes

### 6. Redução de Dimensionalidade
- Seleção de **4 componentes principais**
- Transformação dos dados originais
- Inclusão dos componentes (PCA1, PCA2, PCA3, PCA4) no dataset

---

## 📈 Resultados

- Redução da dimensionalidade mantendo a maior parte da variância dos dados
- Identificação de padrões e relações entre variáveis
- Simplificação do dataset para análises futuras
- Melhor interpretação da estrutura dos dados

---

## 🧰 Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🎯 Conclusão
A aplicação do PCA permitiu condensar a informação do dataset em poucos componentes, reduzindo redundâncias e facilitando a análise exploratória dos dados.
