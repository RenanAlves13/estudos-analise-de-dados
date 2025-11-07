# Análise Descritiva Univariada (Capítulo 2 - Fávero & Belfiore)

Esta pasta contém scripts em Python desenvolvidos para reproduzir o exemplo prático de **Estatística Descritiva Univariada** apresentado no Capítulo 2 do livro "Manual de análise de dados".

O objetivo é demonstrar como obter as mesmas métricas e visualizações, originalmente geradas no IBM SPSS Statistics Software©, utilizando o ecossistema de análise de dados do Python (Pandas, Matplotlib, Seaborn, SciPy).

---

## 📚 Contexto e Referência

O exemplo prático que este código reproduz encontra-se na seguinte obra:

* **Livro:** Manual de análise de dados: estatística e machine learning
* **Autores:** Luiz Paulo Fávero e Patrícia Belfiore
* **Capítulo:** 2

O capítulo demonstra como obter um conjunto completo de estatísticas descritivas univariadas a partir de um conjunto de dados prático.

---

## 🐍 O que o código Python faz?

Os scripts nesta pasta geram o conjunto completo de análises descritivas univariadas, buscando replicar as saídas do SPSS mencionadas no livro.

As análises implementadas incluem:

### 1. Tabelas
* Distribuição de frequências (absolutas, relativas e acumuladas).

### 2. Gráficos
* Histograma
* Gráfico de Ramo-e-folhas (Stem-and-leaf plot)
* Boxplot (Diagrama de caixa)
* Gráfico de barras
* Gráfico de setores (Pizza)

### 3. Medidas de Tendência Central
* Média
* Moda
* Mediana

### 4. Medidas Separatrizes
* Quartis (Q1, Q2, Q3)
* Percentis

### 5. Medidas de Dispersão (Variabilidade)
* Amplitude (Range)
* Amplitude Interquartil (IQR)
* Variância
* Desvio-padrão
* Erro-padrão da média

### 6. Medidas de Forma
* Assimetria (Skewness)
* Curtose (Kurtosis)

---

## 🚀 Como Usar

### Dependências

Certifique-se de ter as principais bibliotecas de análise de dados do Python instaladas.

```bash
pip install -r requirements.txt